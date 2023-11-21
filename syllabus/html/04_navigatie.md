# Oefening 4 - Navigatie

Tot nu toe bestaan de websites die we hebben gemaakt maar uit één enkele pagina die gemaakt wordt door één HTML-bestand. Binnen een grotere website voldoet één pagina meestal niet. Die pagina wordt al snel te vol en te groot. Daarom worden veel websites opgesplitst in meer pagina's. Om een nieuwe pagina toe te voegen, hoeven we slechts een nieuw HTML-bestand te maken met een andere naam.

## Een contactpagina

:::{exercise}
Maak een nieuw HTML-bestand in de map voor Oefening 4 en geef het de bestandsnaam `contact.html`
:::

We gaan een nieuwe pagina maken die gevuld is met jouw contactinformatie, zodat mensen je kunnen bereiken via de website.

:::{exercise}
Gebruik de technieken die je hebt geleerd in Oefening 1 en 2 om een goede pagina te maken met je contactgegevens. Vermeld in ieder geval je naam, emailadres en telefoonnummer.
:::

## Links

Nu hebben we twee pagina's: één startpagina en één contactpagina. Je kunt echter nog niet tussen deze twee pagina's wisselen, want er zijn nog geen links aanwezig op je site. Een link wordt gemaakt met `<a></a>`. Het element heeft een attribute genaamd `href`, dit moet gelijk zijn aan de locatie van de link. De elementen binnen `a` zijn de elementen waar je op moet klikken voor de link om te werken. Dit kan dus simpele tekst zijn maar ook een plaatje of tabel. Uiteindelijk ziet een link er zo uit: `<a href="koppelingslocatie">Knop</a>`.

De koppelingslocatie is in dit geval `contact.html`, omdat de bestanden in dezelfde map staan. In andere situaties moet hier het pad naar het bestand worden gebruikt. In de volgende situatie bijvoorbeeld:

-   *`*index.html*`* zit in een map genaamd `WebDevelopment`.
-   De map `contactmap` zit in de map `WebDevelopment`.
-   *`*contact.html*`* zit in de map `contactmap`.

Nu is het pad tussen `index.html` en `contact.html`: `contactmap/contact.html`.

Let op dat de namen van bestanden en mappen hierin hoofdlettergevoelig zijn. Als de naam van een bestand met een hoofdletter begint dan moet die naam ook in de koppelingslocatie met een hoofdletter.

:::{exercise}
Maak een link in `index.html` naar `contact.html` en ook andersom. Probeer het nu uit.
:::

De koppelingslocatie binnen een link mag ook een openbare site zijn zoals <https://google.com> Gebruik hiervoor de URL van de website in de browser. Vergeet dus niet om `https://` of `http://` in zo'n geval erbij te zetten: `<a href="https://www.google.com/">Google</a>`

Het gebruiken van een openbare site als link is handig, wanneer je bijvoorbeeld een Facebookpagina wilt linken op je website.

:::{exercise}
Voeg op een pagina een link toe naar een externe website.
:::

## Navigatie via een menu

Op vrijwel iedere site waar je vandaag de dag gebruik van maakt, moet je navigeren tussen verschillende pagina's met een menubalk. Hiervoor is speciaal `nav` uit Oefening 2 in het leven geroepen. In dat element zet je alle belangrijke navigatielinks van je site. Voor de beste gebruikservaring is het een goed idee om de menubalk op iedere pagina identiek te laten zijn. Kijk bijvoorbeeld op [*https://www.youtube.com/*](https://www.youtube.com/), hier zie je ook dat de balk aan de bovenkant van de website altijd hetzelfde blijft. Een handige tip voor een simpele menubalk is om de huidige pagina ook in de menubalk terug te laten komen, maar dit normale tekst te maken in plaats van een linkje. Later gaan we dit met `CSS` op een andere manier doen. `nav` staat tussen de header en de eerste `section` of `article`. Het zou er ongeveer zo uit moeten zien:

``` html
<nav>
    Home
    <a href="contact.html">Contact</a>
    <a href="https://google.nl/">Google</a>
</nav>
```

:::{exercise}
Voeg een menubalk toe aan de startpagina en aan de contactpagina, zet hierin de links gemaakt in de vorige Oefening.
:::
