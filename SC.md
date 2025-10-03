# screencast

## Basiseisen
### 1. Semantiek
In mijn HTML gebruik ik semantische elementen. Je ziet hier de `<header>` voor de hero, de `<nav>` voor de navigatie, `<main>` als hoofdinhoud, verschillende `<section>`s, en `<article>`s voor de productkaarten. Ook gebruik ik `<figure>` en `<figcaption>` voor afbeeldingen met bijschriften. Daarnaast hebben alle afbeeldingen een alt-tekst, bijvoorbeeld ‘Product – Bocchi the Rock! Anime T-Shirt’.
 
### 2. CSS-selectors
In mijn CSS gebruik ik verschillende soorten selectors. Bijvoorbeeld element-selectors zoals `header {}`, class-selectors zoals `.cards {}`, en attribute-selectors zoals `.field:has(input[required]) > label::after`. Ook gebruik ik pseudo-classes zoals a:hover en input:invalid. Op deze manier toon ik aan dat ik meerdere soorten selectors kan toepassen.

### 3. Toegankelijkheid
Mijn heading-structuur loopt logisch van `<h1>` in de hero, naar `<h2>` voor de secties, en `<h3>` voor de producttitels. Alle formulieren hebben een bijbehorend `<label>` gekoppeld met een for-attribuut. Ook heb ik alt-teksten toegevoegd voor afbeeldingen. In de browser kun je zien dat je met Tab door de form en de navigatie kan gaan, waardoor de site goed bruikbaar is voor toetsenbordgebruikers.

### 4. Formulier
Hier is mijn formulier. Je ziet labels voor alle velden, en de inputs zijn voorzien van required en juiste types, zoals `type="email"` en `type="date"`. Als ik een verplicht veld leeg laat, zie je dat de CSS een rode rand toevoegt dankzij `:invalid`. Vul ik het correct in, dan wordt de rand groen door `:valid`. Ook is er een checkbox om akkoord te gaan met de voorwaarden en radiobuttons voor de nieuwsbrief.

### 5. Flexbox
Voor de layout heb ik flexbox gebruikt. In de CSS zie je bijvoorbeeld dat de nav met `display:flex` de items naast elkaar zet. De productcards staan in een `flex-container` met `flex-wrap` zodat ze zich aanpassen aan de breedte. Ook gebruik ik flexbox voor de formulier-velden en de footer. Met de devtools kan je goed zien dat deze containers flex zijn.

### 6. Responsiveness
Mijn site is responsive door verschillende media queries. Als ik de browser verklein, zie je dat de navigatie onder elkaar komt te staan, de producten in één kolom verschijnen, en de footer en formulier zich aanpassen. Bij 500 pixels gaat de navigatie bijvoorbeeld volledig in een kolom, en onder de 700 pixels stapelen de form-velden netjes. Zo werkt de site op mobiel en desktop.

### 7. Transitions
Ik heb transitions en hover-effecten toegevoegd. Als ik met de muis over een knop ga, verandert de achtergrondkleur en de tekstkleur vloeiend. Hetzelfde geldt voor de navigatielinks in de navbar. Dit maakt de interactie gebruiksvriendelijker en visueel aantrekkelijker.

### 8. AI-verantwoording
Voor deze opdracht heb ik geen AI gebruikt om code te genereren. Ik heb alle HTML en CSS zelf geschreven. Ik heb wel gebruikgemaakt van online bronnen zoals Reddit en Stack Overflow om oplossingen te vinden en ideeën te krijgen. Als ik AI zou gebruiken, zou dat alleen zijn om teksten te verbeteren of om vragen te stellen, nooit om code te genereren.