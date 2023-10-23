# Opdracht 11 - Layout

De layout van een website bepalen en programmeren is misschien wel het moeilijkste wat er is. Gelukkig zijn er in CSS een hoop gereedschappen ingebouwd om het wat makkelijker te maken. In deze opdracht leer je daarover.

## Display

Het `display` property mag met ieder element gebruikt worden. Het is de meest belangrijke property als het op layout aankomt. `display` bepaalt namelijk of en hoe een element wordt weergeven. Ieder element valt in één van twee categorieën, namelijk `block` of `<div class="inline-image">`.

Elements in de `block` categorie beginnen altijd op een nieuwe regel en gebruiken de volledige beschikbare breedte. `div`, `h1`, `p` en `section` zijn voorbeelden van block-level elements.

Elements in de `<div class="inline-image">` categorie gaan altijd door op dezelfde regel en zijn zo breed als nodig is. `span`, `a` en `img` zijn voorbeelden van inline elements.

Met `display` kan je een block-level element als inline weergeven en vice versa. Een andere optie is `none`. Hiermee wordt het element helemaal niet weergeven op de website en past de rest van de layout zich zo aan alsof het element niet bestaat.

## Position

Met `position` kan de type locatievorming voor een element bepaald worden. `position` wordt in combinatie gebruikt met `top`, `right`, `bottom` en `left` om de afstand tot die verschillende zijden te bepalen.

`position: static;` is de standaardwaarde voor `position`. Hiermee wordt het element niet op een speciale manier gepositioneerd, maar wordt het via de standaard layout van de pagina gepositioneerd.

`position: relative;` wordt gebruikt om elements relatief aan de standaardpositie te positioneren. Dit kan gebruikt worden om extra ruimte rondom een element te creëren, aangezien de omringende elements niet verplaatsen om de gaten te vullen.

`position: fixed;` wordt gebruikt om elements op een vaste plaats op het scherm te zetten. Zelf wanneer de webpagina wordt gescrold dan blijft het element op zijn plek op het scherm.

`position: absolute;` wordt gebruikt om elements op een vaste plaats binnen een gepositioneerd element te zetten. Wanneer het element niet in een gepositioneerd element zit dan wordt het gepositioneerd ten opzichte van de `body`.

`position: sticky;` wordt gebruikt om elements eerst relatief te positioneren, totdat de gebruiker voorbij het element probeert te scrollen en dan blijft het element 'vastplakken' op een bepaalde positie op het scherm.

## Float

`float` wordt gebruikt om elements naast andere elements te laten 'drijven'. Hier kan gekozen worden tussen `float: left;` en `float: right;`.

Af en toe wil je float gebruiken maar tegelijkertijd voorkomen dat bepaalde elementen daardoor ingekort worden. Speciaal daarvoor is `clear` bedacht. Ook hierbij kan gekozen worden tussen `clear: left;` en `clear: right;`. De waarde bepaald aan welke kant er geen element gefloat mag worden.

## Hoogte en breedte

Soms krijg je te maken met een `block` element dat eigenlijk niet de volledige breedte van de pagina in moet nemen. In dit geval kan je met `width` de breedte in `CSS` aanpassen. Hetzelfde kan je ook doen met `height` Hiervoor kan je veel verschillende waarden gebruiken, zoals pixels of percentages.

1.  Experimenteer met de gereedschappen uit deze opdracht en probeer daarmee je website een goede layout te geven. Dit is bijna de laatste stap voordat je een volledige website hebt!
