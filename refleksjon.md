# Refleksjonsrapport

## Innledning

Jeg har virkelig likt å arbeide med denne oppgaven, og jeg har prøvd å ta i bruk teknikkene vi har lært om i undervisningen. Noen deler syntes jeg var enklere enn andre, og enkelte ganger tror jeg at jeg kanskje gjorde det litt vanskeligere for meg selv fordi jeg prøvde å bruke en teknikk som ikke nødvendigvis passet så godt til oppgaven. Her har jeg skrevet en kort refleksjon over noen av teknikkene jeg har brukt for å løse denne oppgaven.

---

## Fokus og læringsvalg

I denne oppgaven valgte jeg bevisst å bruke mest tid på de delene jeg syntes var mest utfordrende og interessante, i stedet for å fokusere på ting jeg allerede kan godt fra før, som for eksempel burgermeny, hover-effekter og lignende. Jeg ønsket å bruke oppgaven som en mulighet til å utforske nye teknikker og konsepter som jeg ikke har jobbet så mye med tidligere, som for eksempel _full-bleed_, _fluid type scale_ og _container queries_. Selv om dette førte til at enkelte deler av prosjektet tok lengre tid, føler jeg at jeg lærte mye mer av å jobbe med det som faktisk utfordret meg. Det gjorde også prosessen mer spennende og motiverende.

---

## Overordnet styling

### Full bleed

For å lage layouten til hele siden har jeg brukt _full-bleed_-teknikken vi gikk gjennom i undervisningen. Jeg startet med å lage tre kolonner: `full-start`, `content` og `full-end`. Senere i prosessen måtte jeg endre dette til fire kolonner for å plassere bildet i _index/hero_-seksjonen. _Full-bleed_-konseptet gir utrolig god mening, men jeg synes det kan være litt vanskelig å forstå hvordan jeg kan bruke det til å løse problemer på egen hånd. Jeg tror og håper at det vil bli enklere med mer øvelse!

Jeg brukte også _full-bleed_-konseptet i `CaseStudyArticle`-komponenten for å få tekstboksen til å ligge innenfor “margen” til bildet. Her støtte jeg på et problem som jeg ikke klarte å løse. Når jeg gjorde skjermen mindre, ble tekstboksen like bred som bildet, og uansett hvilke verdier jeg prøvde å endre på, fant jeg ikke løsningen. Jeg tror likevel jeg kunne ha funnet ut av det dersom jeg hadde hatt mer tid til å jobbe videre med det.

---

### Fluid typescale

Jeg tok også i bruk _fluid typescale_ ved hjelp av **Utopia**. Da jeg først satte det inn, forstod jeg ikke helt hvorfor det ikke fungerte, men etter å ha spurt ChatGPT fant jeg ut at den laveste verdien var for høy, slik at forskjellen ikke ble synlig. Etter å ha justert verdiene fungerte det som forventet.

---

## Flow-space

Når det kom til stylingen av `CaseStudyArticle`, brukte jeg _flow-space_-variabelen for å styre linjeavstanden mellom de forskjellige teksttypene. Jeg prøvde også å bruke den i den globale CSS-en, men oppdaget raskt at det skapte utfordringer når jeg skulle style andre elementer. Jeg endte derfor opp med å bruke den kun sammen med `:is(h1, …)` for at den ikke skulle komme i veien, og heller bruke den mer målrettet inne i de ulike komponentene. Jeg kom ikke helt i mål med dette, men det er definitivt noe jeg ville jobbet videre med dersom jeg hadde hatt mer tid.

---

## Nesting og CSS-selektorer

Jeg prøvde aktivt å bruke _nesting_ for å style de forskjellige komponentene, fordi jeg ønsket å øve på denne måten å strukturere CSS på. Jeg prøvde også å unngå å gi elementene mange _classes_, og heller bruke CSS-selektorer. Jeg føler selv at jeg lærte mye av dette, men det oppstod noen problemer da jeg skulle gjøre sidene mer responsive. Jeg slet da med å finne ut hvilke elementer jeg hadde gjort endringer på. Jeg tror dette skyldes at jeg fremdeles er ny til _nesting_, og at jeg noen ganger brukte det steder hvor det kanskje hadde vært mer effektivt å bruke _classes_ i stedet.

---

## Responsivitet

Jeg prøvde å bruke _container queries_ slik vi lærte i undervisningen, men jeg syntes det var litt vanskelig å forstå hvordan jeg skulle implementere det på en god måte. Derfor endte jeg opp med å bruke _container queries_ kun på én side (`FinancialCards`), og _media queries_ på de andre. Jeg tror likevel at jeg vil forstå dette bedre etter hvert som jeg får mer erfaring og prøver meg mer frem.

---

## Avsluttende betraktninger

Gjennom denne oppgaven har jeg lært mye om hvordan ulike CSS-teknikker kan brukes i praksis, og jeg har blitt mer bevisst på både styrker og svakheter ved egen arbeidsmetode. Jeg har fått bedre forståelse for hvordan _full-bleed_, _fluid type scale_, _flow-space_ og _nesting_ fungerer, men jeg ser også at det krever øvelse for å bruke dem effektivt og strukturert. Selv om jeg støtte på flere utfordringer underveis, føler jeg at jeg har utviklet meg faglig og blitt tryggere på hvordan jeg kan tenke mer helhetlig rundt styling og responsivitet.

Jeg sitter igjen med en følelse av mestring og motivasjon til å fortsette å lære mer, spesielt innen avansert CSS og hvordan man best kan kombinere ulike teknikker for å bygge fleksible og vedlikeholdbare løsninger.
