# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

OM Project:
Bakgrund 
Ni driver ett litet IT-konsultbolag som nu har fått i uppdrag av kunden Johanna att realisera hennes 
idé om att förenkla vardagsbudgetering. Johanna har själv gått från att i princip leva ur hand i mun, 
utan att spara något alls, till att nu snart vara nära sin första miljon. 
Nu vill hon hjälpa andra att ta kontroll över sin ekonomi, och hon har därför kontaktat ert IT-bolag för 
att få hjälp med att utveckla idén och implementera den i kod. Johanna har stora förhoppningar om 
att hennes tjänst ska hjälpa människor att ta kontroll över sin ekonomi, och synliggöra och förtydliga 
de ekonomiska beslut som användarna fattar på daglig basis. Ska jag köpa det nya spelet på Steam 
eller lägga 500 kr till sparande? Ett par nya byxor, eller kanske en tavla till vardagsrummet? På så sätt 
vill Johanna ge sina kunder en enklare vardag, genom att hjälpa de att fatta medvetna beslut för att 
på bästa sätt kunna prioritera vart pengarna läggs och hjälpa till att hålla lite koll på utgifter en 
användare har. 
Utmaningen 
Johanna hoppas kunna saluföra sin idé som en betaltjänst eller liknande, där kunden betalar en 
månatlig eller årlig prenumerationsavgift för att få tillgång till applikationen. Johanna tror att här 
finns en mycket god möjlighet att erbjuda en tjänst som är enkel och smidig att använda, som 
dessutom kan ge stort mervärde i form av ökad kontroll över hushållsbudgeten. 
Dock förstår hon att för att lyckas med sin idé så måste tjänsten ha en eller flera områden där den 
klår Excel eller andra liknande verktyg som många redan idag använder för sin hushållsekonomi. Det 
skulle till exempel kunna vara möjlighet att spara betalningsmottagare ör att förenkla inmatning av 
utgifter. Tjänsten ska inte hantera betalningar, men det ska gå att skriva in vem som är mottagare av 
kundens utgifter. Det kan till exempel röra sig om Coop, ICA, IKEA eller liknande. På så sätt kan man 
enkelt skapa sig en överblick över vart kunden spenderar mest pengar. Därför tror Johanna att en 
användares budget behöver lite olika utgiftskategorier som tex ”Nöje”, ”Sparande”, ”Dagligvaror” 
eller liknande. En tanke är att Johanna vill göra detta på månadsbasis eftersom inkomster oftast 
kommer per månad i form av tex lön. Det ska också kunna gå att hantera andra inkomstkategorier i 
appen. 
Uppdraget 
Ni ska utveckla en webbapplikation som kan hantera privatpersoners ekonomi. Johanna vill vara 
delaktig i processen och vill därför att ni jobbar så kallat ”agilt”. Hon vill att ni presenterar vad ni gjort 
för henne varannan vecka och hon ska vara med och godkänna alla funktioner ni tänkt lägga till innan 
ni gör det. 
För att skapa en översikt av utveckling ska ni börja med att ta fram en backlogg med features som 
kan vara med i applikationen. Johanna kommer sen prioritera dessa åt er och utifrån den 
informationen kan ni ta fram uppgifter till sprintarna. 
Johanna har många idéer om vad som ska vara med i applikationen och förväntar sig att ni ska 
realisera dem. Med det sagt är det också okej för er att komma med idéer till applikationen. Se bara 
till att Johanna godkänner dem innan ni genomför något. Johanna har förtroende för ert tekniska 
kunnande så om ni känner att någon speciell teknik eller omskrivning av kod måste göras är hon 
bered att lyssna på era förslag. 
Sammanställa backloggen i en board på Trello. Dokumentera varje feature i Trello så att Johanna 
förstår vad det är ni tänkt göra men gör det också för er egen skull så att det inte blir något 
missförstånd. 
Nedan följer ett mejl från Johanna som blir ert källmaterial för att skapa backloggen. Ni kommer 
också få en 40 minuters session med Johanna veckan innan utvecklingen ska börja. Därefter kommer 
hon delta på era sprintplaneringar. Under planeringen kan ni diskutera nya features och förtydliga 
befintliga. 
Mejl från Johanna 
Hej, vad kul att det till slut är dags att börja ta fram applikationen. Jag är så spänd på att se vad vi 
kan åstadkomma. Jag tror verkligen att den här applikationen kommer hjälpa många människor att 
få ordning på sin egen ekonomi. 
Jag har tänkt att applikationen ska vara en webbaserad applikationen. Jag övervägde att vi skulle 
göra den som en mobil-app men jag vill gärna att applikationen ska vara tillgängliga på gamla 
vanliga datorer också. Det är dock viktigt att applikationen också fungerar på mobila applikationer då 
jag räknar med att många av användarna kommer använda applikationen via sin mobil. 
Jag har tänkt mycket på vilka funktioner som ska finnas i applikationen. Nedan är en lista med mina 
idéer. Se inte denna lista som komplett jag är säker på att jag kommer komma på fler funktioner 
längre fram och jag lyssnar gärna på om ni har några idéer också. 
 Inloggningsfunktion – Eftersom vi ska ha flera användare (förhoppningsvis) måste vi ha en 
inloggningsfunktion så vi kan hålla isär olika personers data. I denna funktion ingår det att 
kunna registrera sig på sidan. 
 Lista utgifter – kanske inte det mest spännande funktionen men den bör nog vara med i alla 
fall. Jag tänker att användaren ska kunna se alla sina utgifter som gjorts tidigare. Det vore 
bra om listan gick att båda sortera och filtrera på olika värden. Vi kanske också kan ha en 
sök-funktion(?) 
 Inmatning av inkomster och utgifter – Det här är en central funktion i applikationen (så klart). 
Jag tror att det är viktigt att det är smidigt att mata in information. Det är något användaren 
kommer göra ofta och det ska inte vara med tidskrävande än vad det måste vara. 
Jag tänker att både inkomster och utgifter ska ha kategorier så att vi kan gruppera dem sen. 
Utöver kategori ska en utgift ha en mottagare, datum och belopp. Kanske även en titel eller 
kommentar(?) 
 Kategorier – På tal om kategorier behöver vi en funktion för att administrera kategorier. I 
början kanske vi kan nöja oss med ett fast angivet set av kategorier men jag tror många 
användare skulle vilja kunna ange egna kategorier också. 
 Planera månadsbudget – För att hjälpa användaren hålla koll på sina utgifter behöver vi en 
budget-funktion. Jag tänker att användaren planerar en budget per månad. I budgeten anger 
användaren vilka utgiftskategorier hen kommer planerar att lägga pengar på under månaden 
och vilket maxbelopp varje kategori ska ha. 
o För att budgeten ska fylla en funktion måste vi också ha någon funktion för att följa 
upp den. 
o Jag tänker att vi till att börja med kan visualisera summan av alla utgifter under 
pågående månad och hur när användaren är sitt maxbelopp. 
o Vi kanske också ska ha en funktion som varnar när användaren närmar sig taket 
o Det vore kanske också intressant att kunna titta på gamla budgetar för att se hur 
ofta man lyckas hålla sig inom budgeten. 
 Sparmål – Ett annat sätt att hjälpa till mig att hålla i sina pengar kan vara att ha sparmål. 
Användaren kan skapa upp ett mål och ange ett belopp och datum när målet ska vara 
uppnått. Här får vi fundera lite på hur användaren ”sätter in pengar” på sitt sparmål. 
 Jämförelse med andra användare – Vi kan inte dela alla användares utgifter med andra 
användare men vi skulle kunna räkna ut aggregerade värden och jämföra dem mellan 
användare. Till exempel: lägger jag mer eller mindre pengar på livsmedel än andra personer. 
Här får vi nog också fundera lite på exakt hur vi ska möjliggöra denna funktion. 
 Prognoser – Någon form av prognos-funktion vore bra att ha. Lägger jag mer och mer pengar 
på travet varje månad kan det vara en varningsklocka 
 Vänn-funktion – Flera användare kanske vill ha ett gemensamt sparmål 
 Skyt-funktion – Åter igen kan vi inte dela ut en användares utgiftslista men om en användare 
till exempel lyckats halvera sina utgifter på godis jämfört med förra året vill de kanske dela 
det på Facebook. 
Ser fram emot att jobba med er! 
/Johanna 


### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
