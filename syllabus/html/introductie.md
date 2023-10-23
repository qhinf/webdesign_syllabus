# HTML: Introductie

HTML staat voor **HyperText** **Markup** **Language**. Hierbij is HyperText de techniek waarmee een verbinding wordt gemaakt met bijvoorbeeld een andere webpagina. Markup staat voor het systeem waar de programmeertaal zich aan houdt: de manier waarop een document is opgebouwd, is hetzelfde als de website die je uiteindelijk ziet. Als een plaatje boven de tekst staat in HTML, zal dat op de website ook zo zijn. Language betekent hier programmeertaal. HTML is dus een programmeertaal waarbij verbindingen tussen componenten gemaakt kunnen worden en waarbij de uiteindelijke visuele uitkomst identiek is aan de code. Simpeler gezegd is HTML de absolute basis van de website. Met HTML worden alle onderdelen van de website 'getekend' waardoor je geen lege pagina hebt.

Alle websites op het **World Wide Web** (en veel daarbuiten) zijn in de basis gemaakt met HTML. Deze code wordt geladen vanaf een zogenoemde **Webserver**. Veel over webservers hoef je niet te weten, alleen dat het een computer is waarop bestanden kunnen worden opgeslagen en weer geladen kunnen worden. Dat opslaan en laden wordt gedaan vanaf andere computers zoals die van jou. Op deze webservers staan vooral HTML-bestanden, deze bestanden eindigen op `.html`. Het belangrijkste bestand van de hele website heet `index.html`. Dit komt door een afspraak die vroeger is gemaakt. Bij het contact maken met een webserver voor het laden van een website, geeft de server standaard dat bestand aan je computer. Dit is dan ook het bestand wat vervolgens wordt weergegeven.

Wanneer je online zelf onderzoek doet naar HTML dan ga je een paar nieuwe termen tegenkomen. Hieronder staan de belangrijkste termen uitgelegd.

## Elements en tags

**Elements** (elementen) zijn stukjes code in een HTML-bestand die aangeven wat voor soort informatie op een bepaalde plek weergegeven moeten worden. Er zijn verschillende elements voor tekst, plaatjes, kopjes, linkjes en nog veel meer. Deze elements kunnen ook in elkaar gezet worden, deze heten dan nested elements. Zo kan er bijvoorbeeld een plaatjeselement in een linkjeselement zitten, waardoor je op het plaatje kunt klikken om naar de website van het linkje te gaan. Elements worden in een HTML-bestand weergeven en gelezen als **tags**.

Een goede tag kan er als volgt uitzien: `<br/>`. Deze tag zorgt voor een witregel in je webpagina. Zoals je kan zien staan er haken om de tag heen. Deze tag is een zogenoemde **empty tag**. Dit betekent dat deze tag geen inhoud kan hebben buiten de tag zelf. Het zou in dit geval onlogisch zijn als je tekst in je witregel wilt zetten, dan is het namelijk geen witregel meer.

Er zijn ook veel tags waar wel inhoud in mag zitten. Deze tags zijn dan als volgt geformuleerd: `<p>Deze tekst wordt een paragraaf</p>`. Dit zorgt uiteindelijk in de website voor de vorming van een paragraaf met de tekst 'Deze tekst wordt een paragraaf' Op deze manier zie je twee tags, namelijk de **start tag** `<p>` en de **end tag** `</p>`. Tags die inhoud hebben zijn altijd op deze manier geformuleerd. Het is in sommige uitzonderlijke gevallen mogelijk om de end tag (of zelfs de start tag) weg te laten. Dat is echter een slecht idee, want het leidt vaak tot onvoorziene problemen. Empty tags hoeven niet afgesloten te worden (`<br>` kan ook in plaats van `<br/>`). Dit is echter ook sterk af te raden om dezelfde reden. Sluit dus altijd je empty tags en end tags af met een schuine streep!

## Attributes

**Attributes** (attributen) zijn opties die gebruikt worden om meer informatie toe te voegen aan een element. Een attribute ziet er als volgt uit: `<a href="https://www.quadraam.nl/home">Quadraam</a>`. Dit produceert een link (het element a maakt een link) met de naam 'Quadraam' die je naar de website van Quadraam brengt wanneer je erop klikt. Hierbij is het deel `href="https://www.quadraam.nl/home"` de attribute. Een attribute bevindt zich altijd binnen de start tag en heeft altijd de volgende opmaak: `attribuutnaam="waarde"`.

Wanneer je meer leert over de verschillende elements dan leer je ook snel meer over de verschillende attributes die daarbij horen.

## HTML-bestanden

Een HTML-bestand heeft altijd een standaard opbouw, dit wordt ook wel de **boilerplate code** genoemd:

``` html
<!DOCTYPE html>
<html lang="nl">
    <head>
        <meta charset="utf-8"/>
        <title>Hello World</title>
    </head>
    <body>
    </body>
</html>
```

Dit ziet er behoorlijk ingewikkeld uit, maar dit is uiteindelijk best simpel.

``` html
<!DOCTYPE html>
```

Deze regel geeft aan de browser aan welke versie HTML er gebruikt wordt. Wij gebruiken in deze module HTML5. Omdat HTML5 de nieuwste versie is mag er in het `doctype` gewoon `html` gezet worden in plaats van `html5`. Wanneer je bijvoorbeeld HTML4 gebruikt wordt het `html4`.

``` html
<html lang="nl">
</html>
```

Deze regels geven het begin en eind van de website aan. Binnen de start tag zit nog een attribute genaamd `lang`. Deze attribute wordt gebruikt om de primaire taal van een website aan te geven. Op deze manier kunnen browsers en zoekmachines zich daarop aanpassen. `lang` is niet verplicht maar wordt wel sterk aangeraden. Voor meer informatie: [*https://www.w3schools.com/tags/ref_language_codes.asp*](https://www.w3schools.com/tags/ref_language_codes.asp)

``` html
<head>
</head>
```

Deze regels geven het begin en einde van de kop van het HTML-bestand aan. In de kop van het HTML-bestand kan geen inhoud van de website gezet worden, want deze inhoud wordt niet weergeven op de website. In plaats daarvan wordt de kop van het HTML-bestand gebruikt als plaats voor dingen zoals metadata, een icoontje voor de webpagina of de titel van de webpagina.

``` html
<meta charset="utf-8"/>
```

Meta elements worden gebruikt om metadata toe te wijzen. **Metadata** is extra informatie die in dit geval aan de browser wordt doorgegeven aan de website. In dit geval laat `meta` weten hoe de tekst van dit bestand is gecodeerd. Dit is in ons geval `utf-8`. Voor meer informatie: [*https://www.w3schools.com/html/html_charset.asp*](https://www.w3schools.com/html/html_charset.asp)

``` html
<title>Hello World</title>
```

`title` wordt gebruikt om de titel van de website door te geven aan de browser. De titel van de website is wat er bovenin de browser op het tabblad staat bij de website.

``` html
<body>
</body>
```

`body` is waar alle inhoud van de website geplaatst moet worden. Binnen deze twee tags maak je dus eigenlijk heel je website.

Een website maken is dus eigenlijk heel simpel. Gebruik bij het maken van een HTML-bestand gewoon de bovenstaande code en zet je eigen elements binnen de body tags. Pas de titel aan in het head-element en dan heb je een functionerende website.

In een HTML-bestand kom je vaak de volgende stukken code tegen: `<!-- Comment -->`. Dit zijn **comments** in de HTML code. Comments worden gebruikt om je code uit te leggen en leesbaar te maken voor andere programmeurs. *Het is belangrijk dat je veel comments gebruikt in je code en je wordt hier dan ook op beoordeeld in de eindopdracht.*

## Zelf aan de slag

Nu is het tijd om zelf te gaan bouwen aan een website en om de verschillende elements te leren kennen. *Wanneer je een element of tag niet helemaal begrijpt, kun je in Appendix B meer informatie over de tags vinden en over de wijze waarop je ze moet gebruiken.*

In deze module gebruiken we het programma **WebStorm** om de websites makkelijk en snel te kunnen programmeren. WebStorm is een voorbeeld van een **IDE**, een Integrated Development Environment. Dit zijn programma's die het voor programmeurs makkelijker maken om te programmeren, bijvoorbeeld door de code meteen te controleren op foutjes. WebStorm is een zeer krachtig programma waar je veel verschillende dingen mee kan. Je kunt er zelfs de webapps zoals besproken in de introductie mee maken. In het begin ziet WebStorm er heel gecompliceerd uit, maar geen paniek! In deze module leer je stap voor stap hoe je met WebStorm werkt, en veel van de functies ga je nu nog niet gebruiken.

De opdrachten vind je op de volgende pagina's.
