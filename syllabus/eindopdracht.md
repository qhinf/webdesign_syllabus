# Eindopdracht

Na het oefenen met het maken van een website is het nu tijd om het eindproduct voor deze module te gaan maken. Zo kan je alle geleerde kennis meteen toepassen en een website maken die je nog gaat gebruiken.

De opdracht is eenvoudig: maak een website! Het onderwerp en de inhoud van de site mag je zelf bepalen, en ook het design is aan jou (maar denk wel aan wat je daarover tijdens de les hebt geleerd). In een begeleidend document leg je kort uit welke keuzes je in het design hebt gemaakt.

Wat wel belangrijk is: je website moet in principe publiceerbaar zijn. Dat betekent dat je je ook aan copyright regels moet houden, en dus geen teksten of afbeeldingen kopieert die niet van jou zijn, als je daar geen toetstemming voor hebt. Dat geldt ook voor de HTML en CSS code: in principe schrijf je die zelf, tenzij je toestemming hebt om die code te kopiëren **en** je dat duidelijk vermeldt met commentaar. Zie de [Handleiding code stelen](https://informatica.q-highschool.nl/informatie/code-stelen-van-het-internet-of-leerling) voor meer informatie. Code die je gekopieerd hebt, telt voor de beoordeling natuurlijk niet mee in de eisen aan HTML en CSS. En voor het design krijg je ook geen punten, als dat niet je eigen design is. Je laten inspireren en zelfs elementen overnemen is prima, maar de kern moet altijd je eigen werk zijn.

(eindopdracht_design)=
### Designverantwoording

Voeg een document toe aan je website waarin je uitlegt welke designkeuzes je hebt gemaakt. Waarom zit de navigatie daar? Wat heb je gedaan om het overzichtelijk te houden? Benoem hoe je de [basisregels](design/basisregels.md) hebt toegepast en wat de resultaten van jouw [usability tests](design/usability_testing.md) waren.

## Beoordeling

Minimale eisen:

- De website bestaat uit minimaal twee pagina's met onderlinge navigatie
- De website is gemaakt met HTML, CSS en eventueel JavaScript
  - Squarespace, Webflow, Wix, Framer etc. voldoen dus *niet* voor deze opdracht
  - Wil je dieper gaan? Gebruik van een [CMS](https://nl.wikipedia.org/wiki/Contentmanagementsysteem), [SSG](https://en.wikipedia.org/wiki/Static_site_generator), [WAF](https://en.wikipedia.org/wiki/Web_framework) of [SPA](https://en.wikipedia.org/wiki/Single-page_application) framework is toegestaan, mits je je eigen templates maakt (en kan je zelfs bonuspunten opleveren)

Eindproducten die niet aan deze voorwaarden voldoen, kunnen geen voldoende scoren. We beoordelen je website aan de hand van deze rubric:

:::{list-table}
:header-rows: 1
:stub-columns: 1
:width: 100%
:widths: 1 2 2 2

* - 
  - Onvoldoende (1)
  - Voldoende (2)
  - Goed (3)

* - Design: uitvoering\*
  - Bijvoorbeeld:
    - Het doel van de website is onduidelijk
    - Er is geen heldere structuur
    - Pagina's voelen los en onsamenhangend
  - Bijvoorbeeld:
    - Het doel van de website is duidelijk
    - Navigatie is aanwezig en consistent
    - Informatie is overzichtelijk weergegeven
    - Teksten zijn scanbaar
  - Zoals *voldoende*, plus bijvoorbeeld:
    - De site oogt professioneel en samenhangend
    - Er is een duidelijke visuele hiërarchie

* - Design: verantwoording
  - Bijvoorbeeld:
    - Alleen een beschrijving van *wat*, niet *waarom*
    - Geen usability test uitgevoerd
  - Bijvoorbeeld:
    - Legt uit welke designkeuzes zijn gemaakt en *waarom*
    - Verwijst naar de basisregels
    - Beschrijft de resultaten van een uitgevoerde usability test
  - Zoals *voldoende*, plus bijvoorbeeld:
    - De verantwoording is specifiek, met een koppeling van vuistregels aan concrete designkeuzes
    - De usability test is sterk opgezet en uitgevoerd met meerdere gebruikers uit de doelgroep
    - Goede beschrijving van aanpassingen die zijn gemaakt naar aanleiding van de usability test

* - HTML: validiteit en leesbaarheid
  - Bijvoorbeeld:
    - Structurele fouten, zoals niet-afgesloten tekst
    - Moeilijk leesbare code, bijvoorbeeld door inconsistente inspringing
  - Bijvoorbeeld:
    - Valide HTML code
    - Correcte inspringing
    - De link tussen de pagina en de browser en HTML elementen is makkelijk te herkennen
  - Zoals *voldoende*, plus bijvoorbeeld:
    - Consistente en overzichtelijke opbouow
    - Logische bestandsstructuur

* - HTML: structuur
  - Bijvoorbeeld:
    - Nauwelijks gebruik van semantic elements
    - Alinea's door `<br/><br/>` witregels
    - Geen gebruik van elementen (bijvoorbeeld lijsten of een tabel) waar dat zou passen
  - Bijvoorbeeld:
    - Er is een basisstructuur met `<header>`, `<nav>`, `<main>` en `<footer>` op alle pagina's
    - Correct gebruik van diverse HTML elementen waar ze voor bedoeld zijn
  - Zoals *voldoende*, plus bijvoorbeeld:
    - Goed gebruik van semantic elements, inclusief `<section>`, `<article>`, `<aside>`, `<figure>`
    - `<div>` en `<span>` worden alleen gebruikt bij gebrek aan een passend semantic element
    - Nette structuur van tussenkopjes: geen overgeslagen niveaus (bijv. `<h3>` onder `<h1>`)

* - CSS: visuele vormgeving
  - Bijvoorbeeld:
    - Eigen stijlen worden nauwelijks gebruikt
    - Willekeurige of onsamenhangende stijlen
  - Bijvoorbeeld:
    - Meerdere stijlregels dragen bij aan een samenhangende visuele stijl
    - Kleuren, typografie en spacing zijn consistent toegepast
  - Zoals *voldoende*, plus bijvoorbeeld:
    - Layout properties worden op een goede manier ingezet
    - Er is veel aandacht voor details, bijvoorbeeld in verschillende link states

* - CSS: structuur
  - Bijvoorbeeld:
    - Alle CSS staat inline
  - Bijvoorbeeld:
  - Zoals *voldoende*, plus bijvoorbeeld:

:::

Indien een onderdeel geheel afwezig is, bijvoorbeeld bij een ontbrekend design document of het niet gebruiken van CSS, worden voor dat criterium 0 punten toegekend.

**Bonus voor extra uitdaging**: zie {doc}`bijlage/extra` voor een aantal ideeën, maar voel je vrij om zelf met suggesties te komen. Met een zinvolle toepassing van een aantal van deze technieken in je website, kun je tot 3 bonuspunten krijgen.

Je cijfer berekenen we volgens $\frac{\text{aantal punten}}{18} \times 9 + 1$.

\* Bij design hebben we het altijd over vuistregels, dus neem deze criteria met een korrel zout: voor een geheime sekte moet de website misschien juist niet heel overzichtelijk zijn... Met een goede uitleg kun je ook daarmee goede punten scoren!

## Inleveren

Je levert je website in via de Inlever-knop op [app.q-highschool.nl](https://app.q-highschool.nl). Je kunt daar maar één bestand inleveren, dus moet je alle bestanden van je website (HTML, CSS, afbeeldingen, etc.) een .zip bestand maken.

1. Zorg dat alle bestanden in één map staan en open die map als project in **Visual Studio Code** (*Bestand → Map openen…*).
2. Open die map in de Verkenner (Windows) of Finder (macOS). Dat kan direct vanuit **Visual Studio Code**: klik in de VS Code **Explorer** met rechts op je projectmap en kies *Reveal in File Explorer* (Windows) of *Reveal in Finder* (macOS).
3. Maak een .zip bestand volgens [deze instructies](https://informatica.q-highschool.nl/informatie/meerdere-bestanden-inleveren). Vergeet niet om ook je document met uitleg over je [design](eindopdracht_design) toe te voegen aan deze map!
4. Lever het .zip-bestand in op [app.q-highschool.nl](https://app.q-highschool.nl).

## Geen inspiratie?

Maak een CV of portfolio! Bij het solliciteren voor een nieuwe baan wordt bijna altijd om je curriculum vitae (CV) gevraagd. Voor veel mensen is dit een simpel Word-bestandje of PDF waarin de werkervaring en opleidingen van een persoon staan. Vaak wordt daar ook nog een beetje informatie over jezelf aan toegevoegd. In onze ogen is dat allemaal een beetje achterhaald, wij vinden namelijk dat iedereen binnen de informaticawereld een online CV moet hebben! Dat is dan ook de opdracht, je gaat een website maken als vervanging voor je CV.

Als je nog nooit een CV hebt gemaakt dan is [deze site](http://www.carrieretijger.nl/carriere/solliciteren/sollicitatiebrief-en-cv/cv-opstellen) misschien een goede plek om te beginnen. Als je al een CV hebt dan is het slechts een kwestie van die informatie in een goede website verwerken!

Mocht je geen CV willen maken en nog steeds geen inspiratie hebben, kopieer en plak dan de volgende prompt in je favoriete AI chatbot, bijvoorbeeld Gemini of ChatGPT.

    Je bent mijn creatieve webdesign-coach. Je helpt mij om drie leuke ideeën te bedenken voor een website die ik zelf kan bouwen met HTML5 en CSS3. De ideeën moeten aansluiten bij mijn interesses en hobby’s, zodat ik gemotiveerd ben om ermee aan de slag te gaan. Geef bij elk idee kort aan waarom het goed bij mij past en welke onderdelen (zoals tekst, afbeeldingen, navigatie of kleurgebruik) ik erin kan verwerken. Geef mij ideeën en beschrijvingen.
