# CSS: Introductie

CSS staat voor Cascading Style Sheets. Met CSS beschrijf je hoe elements weergeven moeten worden op je beeldscherm. Je kunt één CSS-bestand gebruiken voor veel verschillende HTML-bestanden, waardoor je makkelijk een uniforme opmaak voor heel je website hanteert. Je kunt ook meer CSS-bestanden per HTML-bestand gebruiken om zo heel gemakkelijk en snel een aangepaste opmaak voor elke pagina te maken.

CSS lost een heel groot probleem met HTML op. HTML is namelijk helemaal niet bedoeld om te beschrijven hoe een website eruit moet gaan zien, naast de basis layout. Laten we maar gewoon beginnen, dan zie je al snel hoe handig CSS is.

## Syntax

Een CSS-bestand bestaat uit **stijlregels**, waarbij iedere stijlregel een deel van de website aanpast. Met CSS wijs je die stijlregels toe aan de HTML op drie verschillende manieren. Je kan stijlregels koppelen aan elements, om deze toe te passen op alle elements met die naam. Je kan stijlregels koppelen aan `class`. Dit is een attribute die bij ieder element gebruikt kan worden om een groep elements dezelfde stijlregels te geven. Je kan ook stijlregels koppelen aan `id`. Dit is ook een attribute die bij ieder element toegevoegd kan worden. Het verschil tussen classes en `id` is dat `class` voor meerdere elements gelijk kan zijn, terwijl `id` uniek moet zijn voor ieder element. In de praktijk ziet CSS er dan zo uit:

``` css
selector {
    property: waarde;
}
```

Hierbij is de **selector** dus een element, een class of een id. De **property** specificeert welk visuele aspect aangepast moet worden. De verschillende selectors gebruik je als volgt:

-   Element selector: geen HTML, elementnaam als selector in CSS (bijvoorbeeld `p`).
-   Class selector: `class="classnaam"` in HTML, `.classnaam` als selector in CSS.
-   Id selector: `id="idnaam"` in HTML, `#idnaam` als selector in CSS.

Je kan met CSS ook meer selectors dezelfde stijlregels toewijzen. Dit doe je door de selectors achter elkaar te zetten en te scheiden met komma's:

``` css
selector1, selector2, selector3 {
    property: waarde;
}
```

Met CSS kan je, net zoals met HTML, comments toevoegen aan je code. Ook in CSS is dit belangrijk voor de leesbaarheid en begrijpbaarheid van je code. De syntax is als volgt: `/* Comment */`.

## Koppeling

Voordat de CSS-code aan de browser kan doorgeven hoe de website eruit moet zien, moet de CSS-code eerst gekoppeld worden aan een HTML-bestand. Dit gebeurt vanuit het HTML-bestand zelf. Er zijn drie manieren om dat te doen.

### 1. (Optioneel) Inline styling

Bij inline styling worden de stijlregels toegevoegd als een attribute binnen een element. Op die manier hebben ze alleen invloed op de elementen waar je de stijlregels specifiek bij zet. De syntax is als volgt: `<p style="property1: waarde1; property2: waarde2;"></p>`.

Als je goed kijkt, zie je dat inline styling eigenlijk niet zo veel afwijkt van de manier van styling in een CSS-bestand. Het grootste verschil is dat alles op één regel is gepropt, waardoor het er veel minder overzichtelijk uitziet. Deze vorm van styling is dan eigenlijk ook alleen maar handig wanneer je maximaal drie stijlregels moet toevoegen aan één element. Een ander nadeel hiervan is dat je tussen de HTML-code moet gaan zoeken, wanneer je de stijlregels wilt veranderen. Het is dus niet makkelijk aan te passen.

### 2. (Optioneel) Internal stylesheet

Met een internal stylesheet worden de stijlregels toegevoegd binnen een element in het HTML-bestand. Deze stijlregels gaan in het style-element binnen de *head*. Dit ziet er dan zo uit:

``` html
<style>
    selector {
        property1: waarde1;
        property2: waarde2;
    }
</style>
```

Een voordeel van een internal stylesheet is dat je geen extern CSS-bestand nodig hebt. Een nadeel hiervan is dat deze styles slechts door één HTML-pagina gebruikt kunnen worden, namelijk de pagina waar de CSS in staat. Hierdoor is het eigenlijk alleen geschikt wanneer een bepaalde pagina een sterk afwijkende en unieke stijl heeft. Ook zorgt dit ervoor dat er amper scheiding is tussen de HTML-code en de CSS-code, wat het moeilijk te onderhouden maakt.

### 3. External stylesheet

Met een external stylesheet worden de stijlregels in een eigen CSS-bestand gezet die dan vervolgens wordt gekoppeld aan het HTML-bestand. Dit gebeurt met `<link/>` in het `head` element van je HTML bestand. Dit `link` element heeft drie verplichte attributes, namelijk `rel` (hoe de browser de tekst moet interpreteren), `type` (wat voor soort bestand het is) en `href` (waar staat het bestand). `<link href="` wordt altijd in de head geplaatst, omdat een stylesheet een van de eerste dingen is die de website moet laden. Dit geeft de volgende syntax: `<link rel="stylesheet"type="text/css" href="stylesheet.css" />`.

Voor je eigen stylesheets hoef je alleen `href` aan te passen naar de locatie van je eigen stylesheet. De regels voor het pad dat je daar moet gebruiken zijn hetzelfde als voor `<a href="` linkjes naar andere HTML pagina's in je website. De rest van het voorbeeld kun je kopiëren. Mocht je willen weten wat de andere attributes precies betekenen en wat de mogelijkheden hiervoor zijn kijk dan op: [*https://www.w3schools.com/tags/tag_link.asp*](https://www.w3schools.com/tags/tag_link.asp)

## Zelf aan de slag

CSS bevat heel veel verschillende properties, om deze goed te begrijpen ga je ze meteen in de praktijk toepassen. Gebruik om de CSS te testen je HTML-bestand uit `Opdracht_5` maak een nieuwe website met wat content aan. Zorg ervoor dat je in ieder geval een paar keer `p` en een paar keer `a` gebruikt.

De opdrachten vind je op de volgende pagina's.
