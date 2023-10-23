# Webdesign

[TOC]

In deze module leer je hoe de wereld van **webdesign** in elkaar zit en maak je je eigen website! Alles wat je leert kun je direct toepassen op je eigen site. Websites zijn inmiddels onderdeel van ons dagelijkse leven en hebben daarmee een hele belangrijke plaats gekregen. Het is daarom heel handig om te weten wat er precies achter de schermen gebeurt, op het moment dat jij op een website klikt.

Websites worden geprogrammeerd met **HTML** en **CSS**. Dit zijn twee programmeertalen waarmee alle basisfunctionaliteiten van een website toegankelijk zijn. Je kunt hiermee bijvoorbeeld tekst en plaatjes laten zien, navigeren tussen pagina's en het uiterlijk van de website aanpassen. Dit lijkt misschien heel moeilijk, maar gaandeweg deze module leer je dat het eigenlijk best makkelijk is.

Tegenwoordig zijn er naast websites ook veel **webapps** ('web applications') te vinden online. Dit zijn vaak de grotere en meer gecompliceerde websites. Denk bijvoorbeeld aan WhatsApp Web in je browser of Google Drive. Maar ook kleinere en simpelere websites, zoals die voor je rooster, zijn webapps. Wat een webapp zo anders maakt, is het gebruik van **JavaScript**. Dit is een programmeertaal die op een slimme manier HTML en CSS kan aanpassen en kan reageren op acties van de gebruiker. Zo krijg je hele interactieve websites. HTML en CSS blijven echter een belangrijke rol spelen, want hoeveel Javascript je ook gebruikt, deze twee programmeertalen vormen altijd de basis van een website.

In deze module leer je over de basis van HTML en CSS. Je leert hoe een website in elkaar zit en gaat ook je eigen website maken. Wil je na deze module nou graag verder met webdesign? Volg dan de module *JavaScript* om ook webapps te leren maken, of ga ermee aan de slag bij een van de projectmodules.

## Voorkennis

Voor deze module heb je geen voorkennis nodig. Iedereen is welkom!

## Leerdoelen

Aan het eind van deze module kun je ...

- een website bouwen met HTML en CSS.
- een goed design voor een website bedenken, en uitleggen waarom dat design goed is.

## Eindresultaat

Aan het eind van deze module heb je je eigen website gebouwd. Aan het eind van de syllabus vind je meer informatie over waar deze website aan moet voldoen, maar het onderwerp van de website mag je sowieso zelf bepalen!

## Benodigdheden

Om deze module goed te kunnen volgen, heb je de volgende programma's nodig:

- Een moderne webbrowser, zoals [Chrome](https://www.google.com/chrome/) (of een van de andere Chromium browsers, zoals [Edge](https://www.microsoft.com/edge), [Vivaldi](https://vivaldi.com/), [Opera](https://www.opera.com/) of [Brave](https://brave.com/)), [Firefox](https://www.mozilla.org/firefox/new/) of [Safari](https://www.apple.com/safari/). Internet Explorer of WebKit browsers anders dan Safari raden we af, omdat deze browsers niet altijd goed met moderne HTML en CSS versies overweg kunnen.
- Een editor met ondersteuning voor HTML en CSS. In de les gebruiken we *WebStorm*, een programma dat ook veel door professionele ontwikkelaars gebruikt wordt. Als je liever iets anders gebruikt, is dat prima, maar je docent kan je dan misschien niet helpen als iets niet goed werkt.

  Normaal gesproken is WebStorm een betaald product, maar voor onze scholen is het gratis. Maak hiervoor een account aan op *<https://www.jetbrains.com/shop/eform/students>* met je emailadres van school. Je krijgt een link toegestuurd om dit adres te verifiëren, en op de pagina waar je dan komt, moet je vervolgens nog een account maken. Vervolgens kun je gratis van alle JetbBains-producten gebruik maken.

  Dowload WebStorm via *<https://www.jetbrains.com/webstorm/download/>*. Klik op *Download* bij het juiste besturingssysteem en installeer vervolgens het programma. Wanneer je het programma voor het eerst opstart, krijg je het *Licenses* scherm te zien. Klik daar op de knop *Log in to JetBrains Account* en log in met het account dat je in de vorige stap hebt aangemaakt. Klik op de knop *Activate* om jouw licentie te activeren. Daarna kun je het venster sluiten en aan de slag met WebStorm!

## Kennismakingsopdrachten

Je doet deze module natuurlijk niet in je eentje, maar met een groep. Misschien ken je nog niemand omdat je vrienden deze module niet doen. Het is hoe dan ook een goed plan om kennis met elkaar te maken. Doe daarom in de klas de volgende oefeningen:

1.  Brainstorm met een paar klasgenoten die je nog niet kent over wat jullie al weten over websites. Welke websites vinden jullie erg mooi? Waarom zijn deze juist mooi? Wat kun je erop doen? Welke technologie zit erachter? Wat zou een bepaalde website allemaal moeten kunnen? Waar moet een programmeur rekening mee houden?
2.  Bespreek welke websites jullie allemaal gebruiken. Zoek websites op als ze nog onbekend voor je zijn.
3.  Bespreek voor elke website of het alleen met HTML en CSS gemaakt zou zijn of ook met JavaScript.
4.  Ga eens samen na of de verenigingen of organisaties waar jullie lid van zijn (zoals een sportvereniging) een website hebben. Maak je daar vaak gebruik van? En waarvoor? Kun je zien hoe deze geprogrammeerd is?
5.  Zoek een website op die niet online zou mogen staan omdat hij zo slecht is. Wie kan de slechtste site vinden?
6.  Misschien heeft iemand van jullie al een site gemaakt. Bekijk deze.

Als het goed is ben je er in deze oefeningen een beetje achter gekomen wat jullie hobby's zijn en welke websites daarbij horen. Misschien zit er wel iemand in jullie groepje die al ervaring heeft met webdesign en die al veel kan vertellen over de technologie achter zo'n website. Als dat niet zo is, is dat nog geen reden voor paniek, hoor. Je leert in deze module alles wat je moet weten.

## Zelf onderzoeken

Na de leuke informatie van de expert is het nu tijd om zelf eens te gaan snuffelen op websites. Je kan namelijk al heel veel leren over webdesign in de browser zelf. Dit doe je door de `**Developer Tools**` te gebruiken. Om te beginnen kan je de `**Inspector**` gebruiken. Hiervoor kan je in de meeste browsers op `F12` drukken. Op de website van Quadraam geeft dit met Google Chrome het volgende resultaat:

![](./image2.png)

Het paneel aan de rechterkant van het scherm is geopend op het tabje `Elements`. Alle tekst die hierin staat is al programmeercode! Dit is namelijk de HTML van deze pagina. Wanneer je met je muis boven één van de regels zweeft dan zie dat het deel van de website gemaakt met die regel code grijs oplichten. Met de pijltjes links van de regels kun je de onderdelen binnen dat onderdeel zien.

Binnen de `inspector` kan je de webpagina ook aanpassen door dubbel te klikken op de tekst. Geen zorgen, dit verandert de webpagina alleen voor jou! Wanneer je de pagina ververst met de ![](./image3.png) knop linksboven of met `F5` dan zijn al je wijzigingen weer verdwenen. Je kunt zelfs hele onderdelen van de website verwijderen! Selecteer hiervoor gewoon een regel code en druk daarna op `Delete`.

De gemarkeerde knop in het plaatje activeert een modus waarbij je ergens op de website kan klikken, waardoor de regel code die daarvoor verantwoordelijk is wordt weergeven. Dit is handig om snel te vinden hoe een bepaald deel van de website in elkaar zit.

## Onderzoeksopdrachten

1.  Gebruik de inspector op <https://www.quadraam.nl> om te kijken hoe de website is opgebouwd. Welke tekst zit waarin? Waarom zou dit zo zijn?
2.  Probeer met de inspector een stuk tekst of andere code aan te passen. Wat gebeurt er als je alle tekst verwijdert uit een blok? Kun je op andere manieren de website apart eruit laten zien?
3.  Ga zelf naar een andere website toe en open de inspector daar weer. Wat is er anders aan de website? Probeer ook hier weer verschillende regels code te veranderen.

Naast de inspector zijn er in alle browsers ook nog andere gereedschappen ingebouwd om webdesigners te helpen bij hun baan. Zo kan bijvoorbeeld bijgehouden worden hoeveel geheugen een website gebruikt in het `Performance` tabblad of welke fouten er zijn in de code in het `Console` tabblad. Het is nu tijd om te leren hoe je zelf een website maakt.

# HTML

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

### Opdracht 1 - Simpele elementen

1. Als je WebStorm voor de eerste keer opent, druk dan op: ![](./image4.png) Als je WebStorm al een keer hebt geopend, maak dan een nieuw project met File > New > Project... Gebruik de naam `WebDevelopment` voor je project, laat de rest van de instellingen hetzelfde en druk op Create. Maak een nieuwe map binnen `WebDevelopment` door met de rechtermuisknop op de map te klikken en dan New → Directory te selecteren. Noem deze map `Opdracht_1`. Maak bij elke opdracht weer een nieuwe map, op die manier kun je alle opdrachten goed gescheiden houden. Kopieer dan meteen alle bestanden van de vorige opdracht naar je nieuwe map, we bouwen namelijk verder op de website uit de vorige opdracht. Maak een nieuw bestand in de opdrachtmap door met de rechtermuisknop op de map te klikken en dan New > HTML-file. Noem het bestand `index` en druk op enter. Zo wordt de boilerplate code alvast voor je toegevoegd.

   Voor de meeste mensen geldt dat ze dingen beter onthouden en begrijpen als ze het zelf overtypen, probeer dus zo veel mogelijk zelf te typen en zo min mogelijk te kopiëren. Op die manier vergroot je de kans dat je het in één keer begrijpt. Dit geldt niet alleen voor deze module, maar is belangrijk om te doen in alle informatica modules binnen de Q-Highschool.

2. Druk in de balk bovenaan of aan de linkerkant met de rechtermuisknop op index.html Selecteer vervolgens de optie `Debug ‘index.html’`. WebStorm opent nu jouw website.

   In de meeste IDE's betekent de **debug modus** dat er een live versie van je code wordt geopend. Op die manier kun je aan je code werken terwijl je programma bezig is. In ons geval met web development betekent het dat WebStorm onze webpagina opent en bij iedere wijziging meteen voor ons ververst.

   Je ziet in WebStorm zelf dat alle tekst een aparte kleur heeft. Dit is om de code makkelijker te lezen en te begrijpen te maken. Dit heet **syntax highlighting** en is in vrijwel alle IDE's aanwezig.

   #### Indentation

   Als het goed is, zie je nu een witte pagina met de tekst `Title` in het kopje van het tabblad. Gefeliciteerd! Je eerste website is een feit. Hij is alleen nog wel een beetje saai met die witte pagina. Daar gaan we zo dadelijk wat inhoud aan toevoegen, maar eerst is het belangrijk om te leren over **indentation**. Het is belangrijk dat je code altijd indent. Dit houdt in dat voor andere programmeurs makkelijk te zien moet zijn hoe je code in elkaar zit. Voor sommige programmeertalen is het zelfs verplicht om indentation te gebruiken, ze functioneren niet goed zonder indentation. Voor indentation gebruiken wij de Tabtoets. Voor indentation gelden meestal de volgende regels:

   Zorg ervoor dat de start en end tags altijd op 'hetzelfde niveau' zitten. Dit houdt in dat ze een gelijke afstand tot de linkerzijde van het scherm moeten hebben. Een uitzondering hierop is een tag die zo kort is dat de start en end tags op dezelfde regel kunnen staan. Zet ze in dit geval op dezelfde regel. Bijvoorbeeld:

   ``` html
   <p>
       Dit is een lang stuk tekst waarbij de omringende start- en end tags op
       hetzelfde niveau moeten zitten. Op deze manier hebben ze een gelijke
       afstand tot de linkerzijde van het scherm en is de code overzichtelijk
       voor alle programmeurs die het lezen. Hieronder staat een voorbeeld van
       een korte regel tekst. Bij deze tekst zitten de start- en end tags op
       één regel.
   </p>
   <p>Een kort stuk tekst.</p>
   ```
   
   Wanneer een tag binnen een andere tag valt dan mogen deze niet op hetzelfde niveau zitten. De binnenste tag moet een grotere afstand hebben tot de linkerkant dan de buitenste tag. Bijvoorbeeld:
   
   ``` html
   <body>
       <p>Een stuk tekst</p>
   </body>
   ```
   
   En dus niet:
   
   ``` html
   <body>
   <p>Een stuk tekst</p>
   </body>
   ```
   
   De regels lijken nu een beetje ingewikkeld, maar als je goed kijkt naar de voorbeelden dan zie je het vanzelf terugkomen. De boilerplate code uit het begin van deze opdracht volgt goede indentation. Je zult merken dat de boilerplate code binnen WebStorm er iets anders uit ziet. Veel programmeurs vinden het namelijk onzinnig om de `<head>` en `<body>` met indentation binnen `<html>` te zetten. Wij houden deze structuur ook aan en hebben die drie elements allemaal op één lijn staan. De boilerplate code *zonder* indentation ziet er zo uit:
   
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
   
   Vraag de eerste paar keren dat je programmeert aan klasgenoten of desnoods aan je docent of je indentation klopt. Voor meer informatie over indentation: <https://www.granneman.com/webdev/coding/formatting-and-indenting-your-html#examples>
   
   #### Het p-element
   
   Nu gaan we dan toch echt aan de inhoud werken! Met het belangrijkste element heb je al een beetje kennisgemaakt, dat is namelijk `p`. Met dit element kun je een alinea maken.

3. Voeg in WebStorm een `p` toe binnen de body met wat tekst naar keuze. Zorg ervoor dat het er ongeveer zo uit komt te zien:

   ``` html
   <body>
       <p>
           Wat leuke tekst om je website te testen.
       </p>
   </body>
   ```
   
   Als het goed is zie je nu ook meteen je geschreven tekst op de website.
   
   #### Tekst formatteren
   
   Binnen deze alinea's kun je ook nog aanpassen hoe de tekst eruitziet op de volgende manieren:
   
   - *`<b>Tekst</b>`* binnen deze tag is de tekst dikgedrukt (**bold** in het Engels).
   - *`<i>Tekst</i>`* binnen deze tag is de tekst schuingedrukt (*italics* in het Engels).
   - *`<s>Tekst</s>`* binnen deze tag is de tekst doorgestreept (~~strikethrough~~ in het Engels).
   - *`<mark>Tekst</mark>`* binnen deze tag is de tekst gemarkeerd.
   - *`<br/>`* gaat naar een nieuwe regel, staat gelijk aan één keer op ENTER drukken.
   - Veel meer vind je op <https://www.w3schools.com/tags/ref_byfunc.asp> onder het kopje `Formatting`
   
   Deze tags mogen middenin de tekst gebruikt worden, je hoeft hier niks mee te doen voor indentation.

4. Schrijf nu een paar stukjes tekst over jezelf of iets anders binnen de alinea. Gebruik een paar van de hierboven beschreven elements om je tekst er iets leuker uit te laten zien.
5. (Optioneel) Kijk op de website van w3schools en zoek naar nog meer tags om je tekst mee op te vrolijken. Gebruik daar ook een paar van.

   #### Kopjes

   Je tekst ziet er voor nu waarschijnlijk heel ongestructureerd uit, laten we hier verandering in brengen. HTML heeft al een paar kopjes ingebouwd, deze worden gebruikt door de `h1`, `h2`, `h3`, `h4`, `h5` en `h6` in je HTML-bestand te zetten. Hierbij is `h1` het belangrijkste en grootste kopje en `h6` het minst belangrijke en kleine kopje.

6. Voeg kopjes toe aan je stuk tekst om het overzichtelijker te maken.

   #### Afbeeldingen
   
   Met alleen maar tekst blijft de website toch nog een beetje saai. Je kan gelukkig ook plaatjes toevoegen met HTML. Dit doe je met `img` Deze tag ziet er als volgt uit: `<img src="afbeeldingsbron" alt="vervangende tekst wanneer het plaatje niet geladen kan worden" width="breedte" height="hoogte"/>`. De afbeeldingsbron kan een pad zijn naar een ander bestand of een link naar een afbeelding online. De breedte en hoogte van het plaatje zijn in pixels en hoeven niet hetzelfde te zijn als het origineel. Een alt attribute moet altijd bij een img tag zitten, anders geven sommige browsers een fout.
   
   Een belangrijk aspect bij het gebruiken van foto's op het internet is de wetgeving. Je mag namelijk niet zomaar ieder plaatje dat je online vindt gebruiken in je website. Kijk voor meer informatie over de wetgeving en voor locaties van rechtenvrije foto's op <https://www.riffonline.com/nl/happening/knowledge/de-wetgeving-voor-het-gebruik-van-fotos-op-het-web/>

7. Voeg een afbeelding van het internet naar keuze toe op een plek naar keuze. Experimenteer een beetje met de breedte en de hoogte om te zien wat er met het plaatje gebeurt. Vergelijk de waardes die je invult en het resultaat dat je krijgt met de originele afmetingen van het plaatje. Welke conclusie kun je hieruit trekken?

8. Download een afbeelding vanaf het internet en zet die in een map genaamd sources in de map `Opdracht 1`. Geef hem een herkenbare naam en noteer de bestandsextentie (`.png`, `.jpg`, etc.). Voeg de afbeelding vervolgens toe aan de website met `src="sources/naam.extentie"`.

   In theorie is het mogelijk om een afbeelding te allen tijde vanaf het internet te laden op je website. Dit zorgt echter voor langere laadtijden omdat de afbeelding nog gedownload moet worden vanaf een andere website. Ook kan de website van de afbeelding opeens offline gaan, waardoor deze niet meer geladen kan worden. Zorg er daarom altijd voor dat je een lokale versie van de afbeelding in je map hebt staan, op die manier ben je altijd zelf verantwoordelijk voor de bereikbaarheid van de afbeelding en heb je een snelle website.

Nu heb je jouw eerste echte website gemaakt. Hij is nog redelijk simpel, maar je mag echt wel trots op jezelf zijn. Dit is een voorbeeld van hoe je website eruit zou kunnen zien:

![](./image5.png)

``` html
<!DOCTYPE html>
<html lang="nl">
    <head>
        <meta charset="utf-8" />
        <title>Q-highschool</title>
    </head>
    <body>
        <img 
            src="https://cdn.shortpixel.ai/client/to_webp,q_glossy,ret_img/https://q-highschool.nl/wp-content/uploads/2018/05/Logo_Q-highschool_2019.png"
            alt="q-highschool logo"
            width="200"
            height="60" />
        <p>
            De <b>Q-highschool</b> is een initiatief van Quadraam,
            Gelderse Onderwijs Groep, en maakt en organiseert innovatief onderwijs
            waaraan alle leerlingen van de dertien Quadraamscholen kunnen deelnemen.
            <br /><i>Jij</i> dus ook!<br /> Er zijn vier
            leidende principes die richting geven aan het onderwijsaanbod en de
            werkwijze binnen de Q-highschool. Deze kenmerken zijn hieronder
            beschreven en geven aan waar de Q-highschool voor staat.
        </p>
        <img src="sources/logo-quadraam.jpg" alt="foto" width="150" />
        <h3>Open leersysteem</h3>
        <p>
            Met een <b>netwerk</b> van leerlingen, hun ouders en
            medewerkers wordt de buitenwereld toegankelijk gemaakt, waardoor
            expertise en leermogelijkheden haast oneindig voorradig zijn.
        </p>
        <h3>Leren is groeien</h3>
        <p>
            Experimenteren, fouten maken, opnieuw beginnen, of het gewoon anders
            doen, mag dan ook binnen de Q-highschool.
            De<b>leerervaring</b> weegt zwaarder dan het eindresultaat.
        </p>
        <h3>Regie bij de leerling</h3>
        <p>
            Wij geloven erin dat leerlingen zelf
            <b>verantwoordelijkheid</b> kunnen nemen voor (delen van)
            hun eigen leerproces. Q-highschool biedt daarvoor de ruimte en de
            mogelijkheden.
        </p>
        <h3>Leren omdat het ertoe doet</h3>
        <p>
            Om te leren heb je hoofd, hart en handen nodig. Leren is ervaren,
            denken, doen en zijn. In de Q-highschool nemen leerlingen deel aan
            <b>leeractiviteiten die ertoe doen.</b>
        </p>
    </body>
</html>
```

### Opdracht 2 - Organisatie

Zoals je misschien al hebt gemerkt tijdens het lezen van de code in het voorbeeld is het niet op het eerste gezicht duidelijk hoe de website georganiseerd is. In HTML5 is hier een nieuw systeem voor geïntroduceerd, dit bestaat uit de zogenaamde **Semantic Elements**. Deze elements zorgen ervoor dat elke website in de basis op dezelfde manier gestructureerd kan worden zoals hiernaast. Door deze structuur kunnen computers en zoekmachines beter omgaan met de websites, waardoor de ervaring van de gebruiker verbeterd.

![HTML5 Semantic Elements](./image6.gif)

#### H​eader

`<header></header>` wordt gebruikt om de kop van een website of sectie te weergeven. Er mogen meer headers in één website gebruikt worden op verschillende plekken. `header` moet altijd in de omringende 'container' geplaatst worden voor de sectie of de website.

#### Nav

`<nav></nav>` wordt gebruikt om de hoofdnavigatie van de website weer te geven. In dit element zet je alle knoppen naar andere delen van je website.

#### Section

`<section></section>` wordt gebruikt om secties in de website uit elkaar te houden. Dit is inhoud die thematisch bij elkaar hoort. Een startpagina zou bijvoorbeeld kunnen worden verdeeld in secties voor de introductie, de inhoud en contactinformatie.

#### Article

`<article></article>` wordt gebruikt om onafhankelijke, op zichzelf staande inhoud van elkaar te scheiden. Op een blog kan bijvoorbeeld iedere blogpost een nieuw artikel zijn.

Je kan articles in sections zetten, maar dit kan ook andersom. Het artikel over een voetbalwedstrijd kan in de sportsectie zitten, maar kan tegelijkertijd ook verschillende secties bezitten over verschillende onderwerpen in de wedstrijd.

#### Aside

`<aside></aside>` wordt gebruikt om wat inhoud naast de hoofdcontent te zetten. `aside` moet altijd een verband hebben met de inhoud eromheen.

#### F​ooter

`<footer></footer>` wordt gebruikt om de voettekst van een document of sectie aan te geven. `footer` wordt veel gebruikt om de schrijver van het document, copyright informatie, contactinformatie en dat soort informatie te geven.

#### Figure en figcaption

De `<figure></figure` en `<figcaption></figcaption>` worden gebruikt om een beschrijving toe te voegen bij een plaatje op de website. Dit gaat op de volgende manier:

``` html
<figure>
    <img src="plaatje.jpg" alt="plaatje"/>
    <figcaption>Plaatje 1 - Plaatje</figcaption>
</figure>
```

Meer informatie over semantic elements kan je hier vinden: <https://www.w3schools.com/html/html5_semantic_elements.asp>

Maak een kopie van de website die je in opdracht 1 hebt gemaakt. Doe dit door binnen WebStorm met de rechtermuisknop op `Webdevelopment` te drukken en vervolgens New Directory te kiezen. Geef hem de naam `Opdracht 2` en druk op `OK`. Kopieer vervolgens het HTML-bestand uit `Opdracht 1` door er één keer op te klikken en vervolgens `CTRL + C` te gebruiken. Selecteer vervolgens de map `Opdracht 2` en gebruik `CTRL + V` om het bestand te plakken. Sluit het bestand uit de map `Opdracht 1` door bovenin de balk op het kruisje naast `index.html` te drukken. Open vervolgens het HTML-bestand `index.html` uit de map `Opdracht     2`.

> Pas het bestand aan en zorg ervoor dat hij nu voldoet aan de standaarden van semantic elements. Gebruik ieder semantic element ten minste één keer (behalve `nav`). Laat het controleren door klasgenoten of door de docent.

Hier is een voorbeeld van een goede implementatie:

![](./image7.png)

``` html
<!DOCTYPE html>
<html lang="nl">
    <head>
        <meta charset="utf-8"/>
        <title>Q-highschool</title>
    </head>
    <body>
        <header>
            <img
                src="https://cdn.shortpixel.ai/client/to_webp,q_glossy,ret_img/https://q-highschool.nl/wp-content/uploads/2018/05/Logo_Q-highschool_2019.png"
                alt="q-highschool logo"
                 width="200"
                 height="60"
            />
        </header>
        <section>
            <p>
                De <b>Q-highschool</b> is een initiatief van Quadraam,
                Gelderse Onderwijs Groep, en maakt en organiseert innovatief onderwijs
                waaraan alle leerlingen van de dertien Quadraamscholen kunnen deelnemen.
                <br/><i>Jij</i> dus ook! <br/>Er zijn vier
                leidende principes die richting geven aan het onderwijsaanbod en de
                werkwijze binnen de Q-highschool. Deze kenmerken zijn hieronder
                beschreven en geven aan waar de Q-highschool voor staat.
            </p>
            <aside>
                <figure>
                    <img src="sources/logo-quadraam.jpg" alt="foto" width="150"/>
                    <figcaption>Het logo van Quadraam</figcaption>
                </figure>
            </aside>
        </section>
        <section>
            <article>
                <h3>Open leersysteem</h3>
                <p>
                    Met een <b>netwerk</b> van leerlingen, hun ouders en
                    medewerkers wordt de buitenwereld toegankelijk gemaakt, waardoor
                    expertise en leermogelijkheden haast oneindig voorradig zijn.
                </p>
            </article>
            <article>
                <h3>Leren is groeien</h3>
                <p>
                    Experimenteren, fouten maken, opnieuw beginnen, of het gewoon anders
                    doen, mag dan ook binnen de Q-highschool. De
                    <b>leerervaring</b> weegt zwaarder dan het eindresultaat.
                </p>
            </article>
            <article>
                <h3>Regie bij de leerling</h3>
                <p>
                    Wij geloven erin dat leerlingen zelf
                    <b>verantwoordelijkheid</b> kunnen nemen voor (delen van)
                    hun eigen leerproces. Q-highschool biedt daarvoor de ruimte en de
                    mogelijkheden.
                </p>
            </article>
            <article>
                <h3>Leren omdat het ertoe doet</h3>
                <p>
                    Om te leren heb je hoofd, hart en handen nodig. Leren is ervaren,
                    denken, doen en zijn. In de Q-highschool nemen leerlingen deel aan
                    <b>leeractiviteiten die ertoe doen.</b>
                </p>
            </article>
        </section>
        <footer>© Quadraam 2019</footer>
    </body>
</html>
```

#### Div en span

Voordat semantic elements de standaard werden werd er veel gewerkt met `<div></div>` en `<span></span>`. Deze elements worden gebruikt om andere elements te groeperen, net zoals de semantic elements doen. Er zit echter wel één groot verschil tussen de twee methoden. Dat verschil is dat bij semantic elements al is vastgesteld op welke manier elements gegroepeerd moeten worden, terwijl dat met `div` en `span` niet zo is.

`div` groepeert de elements bij elkaar en zet er een witregel onder en boven, op deze manier wordt een op zichzelf staand blok gemaakt. `span` groepeert de elements in-line bij elkaar, ze worden dus achter elkaar gezet.

Je kan en mag deze elements nog steeds gebruiken om andere elements te groeperen, maar wanneer je semantic elements kan gebruiken dan is het sneller en beter om deze te gebruiken.

### Opdracht 3 - Tabellen en lijsten

Tabellen en lijsten zijn zeer handige manieren om informatie te ordenen. In HTML zijn hier dan ook verschillende elements aan toegewijd.

#### Table

In HTML maak je een tabel met `<table></table>`. Hierbinnen maak je rijen met `<tr></tr>` en kolommen met `<td></td>`. Ook kan je de tabel kopjes geven met `<th></th>`. Je kan ook de hele tabel een kop geven met `<caption></caption>`. De syntax van een tabel is als volgt:

![](./image8.png)

``` html
<table>
    <caption>Mensen</caption>
    <thead>
        <tr>
            <th>Naam</th>
            <th>Leeftijd</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Nancy</td>
            <td>60</td>
        </tr>
        <tr>
            <td>James</td>
            <td>47</td>
        </tr>
        <tr>
            <td>Thomas</td>
            <td>37</td>
        </tr>
    </tbody>
</table>
```

Dit geeft het resultaat aan de rechterkant. Er kunnen nog meer dingen worden aangepast aan de tabel. Kijk hiervoor op <https://www.w3schools.com/html/html_tables.asp> als je geïnteresseerd bent. De tabel ziet er nu ook nog redelijk saai uit. Dit gaan we echter later met CSS verbeteren.

1.  Maak een kopie van de website uit opdracht 2. Pas hem nu aan door een tabel toe te voegen, voorzie die ook meteen van inhoud.

#### Unordered list

Wanneer je met HTML slechts een lijst van bullet points wilt maken dan kan je hiervoor een unordered list gebruiken. Deze vorm van list bestaat uit een buitenste element `<ul></ul>`, die een unordered list aankondigt, en een binnenste element met `<li></li>` (list items). Deze elements bevatten uiteindelijk de inhoud. Dit doe je als volgt met het resultaat aan de rechterkant: ![](./image9.png)

``` html
<ul>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
    <li>C</li>
    <li>C#</li>
</ul>
```

1.  Voeg een unordered list toe aan de website en voorzie hem van inhoud.

#### Ordered list

Wanneer je met HTML een geordende lijst met bijvoorbeeld nummers wilt maken, dan kun je hiervoor een ordered list gebruiken. Dit bestaat uit het buitenste element `<ol></ol>`, met de binnenste elements `<li></li>`. De syntax is gelijk aan die van een unordered list. `ol` heeft alleen wel een extra attribute, namelijk `type` Hiermee kan je de type ordening specificeren als volgt:

-   `type="1"` lijst geordend met cijfers (standaard)
-   `type="A"` lijst geordend met hoofdletters
-   `type="a"` lijst geordend met kleine letters
-   `type="I"` lijst geordend met Romeinse hoofdletters
-   `type="i"` lijst geordend met Romeinse kleine letters

Dit leidt tot de volgende syntax en het volgende resultaat:

![](./image10.png)

``` html
<ol type="I">
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
    <li>C</li>
    <li>C#</li>
</ol>
```

1.  Voeg een ordered list toe aan de website en voorzie meteen van inhoud.

2.  Lijsten en tabellen zijn onwijs veelzijdig en krachtig. Ze vormen zich naar de inhoud en de browser. Experimenteer met lijsten en tabellen in je eigen website of in een nieuw bestand. Zet lijsten in andere lijsten of tabellen. Kijk goed naar wat er gebeurt en probeer er een goed begrip van te krijgen.

Meer over de lijsten vind je hier: [*https://www.w3schools.com/html/html_lists.asp*](https://www.w3schools.com/html/html_lists.asp)

### Opdracht 4 -- Navigatie

Tot nu toe bestaan de websites die we hebben gemaakt maar uit één enkele pagina die gemaakt wordt door één HTML-bestand. Binnen een grotere website voldoet één pagina meestal niet. Die pagina wordt al snel te vol en te groot. Daarom worden veel websites opgesplitst in meer pagina's. Om een nieuwe pagina toe te voegen, hoeven we slechts een nieuw HTML-bestand te maken met een andere naam.

#### Een contactpagina

1.  Maak een nieuw HTML-bestand in de map voor opdracht 4 en geef het de bestandsnaam `contact.html`

We gaan een nieuwe pagina maken die gevuld is met jouw contactinformatie, zodat mensen je kunnen bereiken via de website.

1.  Gebruik de technieken die je hebt geleerd in opdracht 1 en 2 om een goede pagina te maken met je contactgegevens. Vermeld in ieder geval je naam, emailadres en telefoonnummer.

#### Links

Nu hebben we twee pagina's: één startpagina en één contactpagina. Je kunt echter nog niet tussen deze twee pagina's wisselen, want er zijn nog geen links aanwezig op je site. Een link wordt gemaakt met `<a></a>`. Het element heeft een attribute genaamd `href`, dit moet gelijk zijn aan de locatie van de link. De elementen binnen `a` zijn de elementen waar je op moet klikken voor de link om te werken. Dit kan dus simpele tekst zijn maar ook een plaatje of tabel. Uiteindelijk ziet een link er zo uit: `<a href="koppelingslocatie">Knop</a>`.

De koppelingslocatie is in dit geval `contact.html`, omdat de bestanden in dezelfde map staan. In andere situaties moet hier het pad naar het bestand worden gebruikt. In de volgende situatie bijvoorbeeld:

-   *`*index.html*`* zit in een map genaamd `WebDevelopment`.
-   De map `contactmap` zit in de map `WebDevelopment`.
-   *`*contact.html*`* zit in de map `contactmap`.

Nu is het pad tussen `index.html` en `contact.html`: `contactmap/contact.html`.

Let op dat de namen van bestanden en mappen hierin hoofdlettergevoelig zijn. Als de naam van een bestand met een hoofdletter begint dan moet die naam ook in de koppelingslocatie met een hoofdletter.

1.  Maak een link in `index.html` naar `contact.html` en ook andersom. Probeer het nu uit.

De koppelingslocatie binnen een link mag ook een openbare site zijn zoals <https://google.com> Gebruik hiervoor de URL van de website in de browser. Vergeet dus niet om `https://` of `http://` in zo'n geval erbij te zetten: `<a href="https://www.google.com/">Google</a>`

Het gebruiken van een openbare site als link is handig, wanneer je bijvoorbeeld een Facebookpagina wilt linken op je website.

1.  Voeg op een pagina een link toe naar een externe website.

#### Navigatie via een menu

Op vrijwel iedere site waar je vandaag de dag gebruik van maakt, moet je navigeren tussen verschillende pagina's met een menubalk. Hiervoor is speciaal `nav` uit opdracht 2 in het leven geroepen. In dat element zet je alle belangrijke navigatielinks van je site. Voor de beste gebruikservaring is het een goed idee om de menubalk op iedere pagina identiek te laten zijn. Kijk bijvoorbeeld op [*https://www.youtube.com/*](https://www.youtube.com/), hier zie je ook dat de balk aan de bovenkant van de website altijd hetzelfde blijft. Een handige tip voor een simpele menubalk is om de huidige pagina ook in de menubalk terug te laten komen, maar dit normale tekst te maken in plaats van een linkje. Later gaan we dit met `CSS` op een andere manier doen. `nav` staat tussen de header en de eerste `section` of `article`. Het zou er ongeveer zo uit moeten zien:

``` html
<nav>
    Home
    <a href="contact.html">Contact</a>
    <a href="https://google.nl/">Google</a>
</nav>
```

1.  Voeg een menubalk toe aan de startpagina en aan de contactpagina, zet hierin de links gemaakt in de vorige opdracht.

### (Optioneel) Opdracht 5 -- Validatie

Het is in het algemeen bekend dat mensen fouten maken. Dit betekent dat ook jij fouten gaat maken in je HTML code. Het vervelende aan HTML is dat foutjes vaak niet meteen tot problemen leiden. Het komt dan helaas wel voor dat het later voor problemen gaat zorgen en dat het heel moeilijk is om de bron van het probleem te vinden.

Gelukkig wordt in deze module de WebStorm IDE gebruikt. In WebStorm zie je het namelijk meteen wanneer je foutjes maakt doordat er een streepje onder komt te staan met een lampje. Wanneer je op dit lampje klikt kan je verschillende mogelijkheden kiezen om je code te verbeteren. Meer over de hulp van WebStorm vind je op <https://www.jetbrains.com/help/webstorm/getting-started-with-webstorm.html>

Voordat IDE's gebruikt werden voor het maken van websites moest de HTML code geverifieerd worden door een externe website. Daarvoor werd de HTML validator van w3schools veel gebruikt. Op deze website kun je jouw HTML invoeren en uitvinden of er foutjes in zitten. Bij het checken krijg je te maken met twee verschillende soorten meldingen, de errors en de warnings. Bij errors is het de bedoeling dat je de code aanpast zodat de error verdwijnt. Dit zijn foutjes in de code die tot problemen gaan leiden. Bij warnings is het de bedoeling dat je nagaat of het van toepassing is op jouw website. Warnings worden vooral gegeven wanneer je niet de beste programmeergewoontes aanhoudt. De validator vind je hier: [*https://validator.w3.org/#validate_by_input*](https://validator.w3.org/#validate_by_input)

1.  Gebruik de validator om de code van je website uit opdracht 4 te controleren. Pas zo nodig de code aan om in ieder geval de errors weg te laten gaan.

De validator kan ook gebruikt worden om CSS te valideren op: *<https://jigsaw.w3.org/css-validator/#validate_by_input>* Omdat WebStorm deze foutjes al heel snel en makkelijk aangeeft hoef je de validator van w3schools niet te gebruiken.

# CSS

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

### Opdracht 6 - Koppeling

We gaan nu een CSS-bestand maken en die koppelen aan je HTML-bestand.

1.  Voeg een CSS-bestand toe aan de map @Opdracht_6@ door met de rechtermuisknop op de map te klikken en vervolgens New > Stylesheet te kiezen. Geef hem de naam `stylesheet` en druk op `enter`
2.  Gebruik `<link rel="stylesheet" type="text/css" href="..." />` om jouw `stylesheet.css` te koppelen aan je HTML-bestanden zoals uitgelegd hierboven.

### Opdracht 7 - Kleuren

Eén van de belangrijkste elementen van een website is het kleurenschema. Tot nu toe zijn onze websites in zwart-wit gemaakt op een paar plaatjes na. Wij gaan daar nu verandering in aanbrengen met CSS.

#### Tekst

Je kan met CSS de kleur van tekst heel eenvoudig veranderen, dit doe je met de stijlregel: `color: kleur;`

Hierbij kan `kleur` veel verschillende waarden zijn. De simpelste optie is het gebruiken van de Engelse naam voor de kleur (bijvoorbeeld `red` of `yellow`). Wanneer je achter `color:` op *CTRL*+*SPATIE* drukt, krijg je binnen WebStorm een lijstje te zien van alle kleuren die mogelijk zijn. Er zijn 140 standaard kleuren die je kan gebruiken. De lijst is ook nog terug te vinden op: [*https://www.w3schools.com/colors/colors_names.asp*](https://www.w3schools.com/colors/colors_names.asp) . Alle tekst binnen paragrafen blauw maken doe je zo:

``` css
    p {
        color: blue;
    }
```

1.  Geef de tekst in je website een kleurtje. Maak hierbij gebruik van aparte kleuren voor de verschillende kopjes, tabellen, etc.

#### (Optioneel) RGB(A)

De Engelse naam voor de kleur gebruiken, is niet de enige manier om de kleur te bepalen, een andere manier is om de zogenaamde RGB Value te gebruiken. Hierbij staan de letters in RGB voor Red, Green en Blue. De syntax voor een RGB kleur is als volgt: `color: rgb(255,255,255);`

In deze syntax staat het eerste getal voor de hoeveelheid rood, het tweede getal voor de hoeveelheid groen en het derde getal voor de hoeveelheid blauw. Deze getallen kunnen waarden zijn tussen 0 en 255, waarbij 0 betekent dat die kleur er niet in zit en 255 betekent dat die kleur er zo veel mogelijk in zit. Met RGB kleuren kun je de verschillende waarden voor rood, groen en blauw licht combineren om zo tot meer kleuren te komen. Hiervoor kan je het beste een color picker gebruiken zoals die van google, zo kan je visueel een kleur kiezen en dan de RGB waarden te kopiëren: [*https://www.google.com/search?q=rgb+color+picker*](https://www.google.com/search?q=rgb+color+picker)

RGBA is een variant op de RGB waarden. Hierbij is er een vierde getal toegevoegd tussen 0 en 1 dat bepaald hoe transparant de kleur is. Hier betekent 0 dat de kleur volledig transparant is en 1 dat de kleur niet transparant is. De syntax hiervan is als volgt: `color: rgba(255,255,255,0.5);`

1.  Pas één of meerdere van jouw aangepaste kleuren aan en gebruik nu RGB of RGBA waarden.

#### (Optioneel) HEX

De HEX manier om kleuren aan te geven lijkt veel op de RGB manier. De syntax is als volgt: `color: #ff155a;`

Op het eerste oog lijkt het heel anders, dit komt door het gebruik van hexadecimal. Hexadecimal is een manier om te tellen die voor computers is ontwikkeld. De waardes voor rood, groen en blauw blijven variabel tussen 0 en 255, alleen dit ziet er in hexadecimal uit als `00` tot `ff`. Dit betekent dat in het voorbeeld `ff` de waarde is voor rood, `15` de waarde is voor groen en `5a` de waarde is voor blauw. Ook het gebruik van HEX is het makkelijkst met de color picker, kies een kleur en kopieer de waarde: <https://www.google.com/search?q=rgb+color+picker>

1.  Pas één of meerdere van jouw aangepaste kleuren aan en gebruik nu HEX waarden.

#### (Optioneel) HSL(A)

Nog een andere manier om kleuren aan te duiden is HSL. Dit staat voor Hue, Saturation en Lightness. De syntax is als volgt: `color: hsl(360, 100%, 100%);`

![Image result for color wheel angles](./image11.png)

Hierbij staat het eerste getal voor de hue (tint in het Nederlands). Deze hue is een waarde tussen 0° en 360° op het kleurenwiel hierboven. Als je de hue van 0 tot 360 laat variëren doorloop je de kleuren van de regenboog. Het tweede getal staat voor de saturation (verzadiging in het Nederlands). Deze saturation is een waarde tussen 0% en 100%. Hierbij is 100% een hele hoge verzadiging en dus hele levendige, felle en heldere kleuren. 0% is een hele lage verzadiging en is daarom heel grauw. Het derde getal staat voor lightness (helderheid in het Nederlands). Deze lightness is ook een waarde tussen 0% en 100%. Hierbij is 100% een hele hoge helderheid en dus wit. 0% is een hele lage helderheid en dus zwart. De color picker is ook hierbij je beste vriend: <https://www.google.com/search?q=rgb+color+picker>

HSLA is weer een variant op de HSL waarden. Net zoals bij RGBA is er een vierde getal toegevoegd tussen 0 en 1 dat bepaald hoe transparant de kleur is. Hierbij betekent 0 dat de kleur volledig transparant is en 1 dat de kleur niet transparant is.

1.  Pas één of meerdere van jouw aangepaste kleuren aan en gebruik nu HSL of HSLA waarden.

#### Achtergrond

Naast de tekstkleur kan ook de achtergrondkleur van elementen aangepast worden. Dit wordt gedaan met `background-color`. Hierbij kunnen de verschillende waarden voor kleuren hierboven weer gebruikt worden. Deze property heeft op ieder element weer een andere invloed, uitproberen loont dus.

1.  Voeg een achtergrondkleur toe aan één of meerdere elementen.

#### Opacity

Voor ieder element in je webpagina kan je ook `opacity` gebruiken. Dit specificeert de doorzichtigheid van dat element. De waarde hiervan moet tussen 0 en 1 zijn, waarbij 0 betekent dat het element niet zichtbaar is en 1 betekent dat het element volledig zichtbaar is.

1.  Voeg `opacity` toe aan één of meerdere elementen.
2.  Zorg ervoor dat in je uiteindelijke CSS-bestand iedere kleuraanduiding minimaal één keer aanwezig is. Zo kan je later terugkomen naar de code en zien welke verschillende manieren ook alweer bestaan.

### Opdracht 8 - Tekst

We hebben het bij opdracht 1 over simpele elementen al een beetje gehad over het formatteren van tekst. Dit kan met HTML gedaan worden met tags, maar dit kan ook gedaan worden met CSS. Zoals je in de vorige opdracht al hebt gezien bepaal je de kleur van de tekst met `color`, maar ook andere opmaak zoals het lettertype kunnen bepaald worden.

Bij het geven van opmaak aan tekst moet de leesbaarheid van de tekst altijd voorop staan. Hier zijn een aantal basis principes voor ontwikkeld. Deze kan je hier vinden: <https://www.oogvereniging.nl/leven-werken/alle-onderwerpen/boeken-lezen/handreiking-bruikbaarheid-gedrukte-tekst/>

#### Align

Tekst kan binnen CSS met `text-align` uitgelijnd worden naar links, naar het midden of naar rechts. De waarden hiervoor zijn respectievelijk `left`, `center` en `right`.

1.  Voeg een `text-align` toe aan één of meerdere elementen naar keuze.

#### Decoration

Met `text-decoration` kan bepaald worden of er lijnen boven, door of onder te tekst geplaatst worden. De waarden hiervoor zijn respectievelijk `overline`, `line-through` en `underline`. Je kan met `text-decoration` ook de standaard lijnen onder links weghalen met de waarde `none`.

1.  Voeg een `text-decoration` toe of verwijder deze bij één of meerdere elementen naar keuze.

#### Shadow

Met `text-shadow` kan een schaduw toegevoegd worden aan tekst. Dit volgt de volgende syntax: `text-shadow: horizontale-positie verticale-positie` Hierbij zijn de posities in pixels en mogen deze ook negatief zijn. Ook heb je de mogelijkheid om de kleur van de schaduw en de hoeveelheid vervaging van de schaduw bepalen met respectievelijk `color` in kleuren en `blur-radius` in pixels.

1.  Voeg een `text-shadow` toe aan één of meerdere elementen naar keuze.

#### Font-family

Er worden op websites heel veel verschillende lettertypen gebruikt en deze worden toegepast met CSS. Er zijn drie hoofdcategorieën lettertypen die belangrijk zijn om te kennen, **Serif** en **Sans-serif** staan hiernaast. De derde is **Monospace**, alle lettertypen binnen deze categorie hebben letters die allemaal een gelijke breedte zijn.

![Image result for serif sans serif](./image12.png)

Omdat je online met veel verschillende computers en browsers te maken krijgt, is het de bedoeling dat je meer mogelijke lettertypen aangeeft voor een bepaald stuk tekst. Dit wordt gedaan met `font-family` met de volgende syntax: `font-family: "Times New Roman", Times, serif;`. Hier begin je met het lettertype dat je in het ideale geval wilt gebruiken en bouw je af naar uiteindelijk een hoofdcategorie. Alle browsers hebben ten minste één lettertype uit alle hoofdcategorieën. Door op deze manier `font-family` te gebruiken weet een browser altijd welk lettertype gebruikt moet worden. Kijk voor veilige lettertypen combinaties op de volgende pagina: [*https://www.w3schools.com/cssref/css_websafe_fonts.asp*](https://www.w3schools.com/cssref/css_websafe_fonts.asp)

1.  Voeg een `font-family` toe aan één of meerdere elementen naar keuze.

#### Font-style

Het is natuurlijk ook mogelijk om een stuk tekst met CSS schuingedrukt te laten zijn, dit wordt gedaan met `font-style`. Hiermee kan je de tekst recht of schuingedrukt maken met respectievelijk *normal* en *italic*.

1.  Voeg een `font-style` toe aan één of meerdere elementen naar keuze.

#### Font-weight

Tekst dikgedrukt maken doe je met `font-weight`. Hierbij gebruik je `normal` om de tekst niet dikgedrukt te maken en `bold` om de tekst wel dikgedrukt te maken.

1.  Voeg een `font-weight` toe aan één of meerdere elementen naar keuze.

#### Font-size

De grootte van de tekst kan uiteraard ook aangepast worden in CSS. Dit kan gedaan worden met `font-size` Hier moeten developers echter een belangrijke keuze maken. Het is namelijk mogelijk om de grootte van de tekst vast te zetten in pixels, hierbij kun je er te allen tijde zeker van zijn dat de tekst een bepaalde grootte heeft. Het is echter ook mogelijk om de grootte van de tekst te bepalen in *em*, hierbij is *1em* gelijk aan 16px. Door *em* te gebruiken kunnen gebruikers zelf in het menu van hun browser aanpassen hoe groot de tekst moet zijn. Doordat sommige mensen kleine tekst slecht kunnen lezen, is het een goed idee om de tekstgrootte in *em* te gebruiken. Als je al een bepaalde grootte in pixels in je hoofd hebt dan hoef je deze slechts te delen door 16 om je *em* waarde te verkrijgen.

1.  Voeg een `font-size` toe aan één of meerdere elementen naar keuze en gebruik daarvoor een waarde in em.

### Opdracht 9 - Randen

Met `CSS` is het mogelijk om randen te vormen om ieder element van je website. Randen zijn een essentieel onderdeel van je webdesign, ze zorgen er namelijk voor dat de lezer van je website makkelijk kan zien hoe alles georganiseerd is. Het verbetert op die manier de User Experience.

#### Border-style

Randen zijn er in allerlei verschillende vormen en met `border-style` kan je bepalen welke vorm je rand moet aannemen. `border-style` kan tussen de één en vier parameters bevatten met de volgende syntax:

``` css
border-style: rondom;
border-style: boven-beneden links-rechts;
border-style: boven links-rechts beneden;
border-style: boven rechts beneden links;
```

Bijvoorbeeld:

``` css
border-style: dotted;
border-style: dotted dotted;
border-style: dotted dotted dotted;
border-style: dotted dotted dotted dotted;
```

![](./image13.png)

Een paar van de verschillende waarden staan aan de rechterkant, kijk voor meer mogelijkheden voor randstijlen op *<https://www.w3schools.com/css/css_border.asp> *

*LET OP!* `border-style` *moet gebruikt worden als je één van de andere waarden van randen die hierna worden uitgelegd wilt gebruiken. Wanneer je dit niet toevoegt dan gebeurt er niks!*

1.  Voeg een `border-style` toe aan één of meerdere elementen naar keuze.

#### Border-width

Je kunt de dikte van de randen aanpassen met `border-width`. Dit kan in px, pt, cm, em, thin, medium of thick. Ook `border-width` kan tussen de één en vier parameters bevatten met de syntax van `border-style`

1.  Voeg een `border-width` toe aan de elementen met een rand.

#### Border-color

Je kunt de kleur van de randen ook aanpassen. Dit doe je met `border-color`. Dit kan met de verschillende manieren om kleuren weer te geven uit Opdracht 7. Ook `border-color` kan tussen de één en vier parameters bevatten met de syntax van `border-style`. Wanneer er geen border-color is gespecificeerd dan volgt de rand de kleur van het element die is gepaald met `color`.

1.  Voeg een `border-color` toe aan de elementen met een rand.

#### Border-radius

Tot nu toe hebben de randen steeds vierkante hoeken, je kan echter met `border-radius` ook ronde hoeken specificeren. Dit bepaalt de radius van de cirkels op de hoeken en heeft een maximum van 12px. Ook `border-radius` kan tussen de één en vier parameters bevatten, waarbij er met vier parameters linksboven begonnen wordt en met linksonder geëindigd wordt.

1.  Voeg een `border-radius` toe aan één of meer elementen met een rand.

#### Border

Voor simpele randen die geen verschil nodig hebben in de verschillende zijden kan je `border` gebruiken. De syntax is als volgt: `border: border-width border-style border-color`

1.  Pas een simpele rand aan en vervang de CSS code met een `border`

### Opdracht 10 - Het box model

![https://upload.wikimedia.org/wikipedia/commons/thumb/e/ed/Box-model.svg/765px-Box-model.svg.png](./image14.png)

Alle HTML-elements kunnen in principe gezien worden als dozen. In CSS wordt **het box model** gebruikt om het design en de layout van de elements te bespreken. Het box model is een doos die om het element heen zit bestaande uit de margin, border en padding. Dit zit om de content heen die door de HTML wordt bepaald. Met borders heb je al kennis gemaakt, nu ga je ook kennismaken met margin en padding.

#### Margin

De margin van een element is de ruimte die om de border heen zit die het element bezet. Binnen deze margin kunnen zich normaal gesproken geen andere elements bevinden. Margin is te bepalen met de volgende syntax `margin: boven rechts beneden links;` of:

``` css
margin-top: waarde;
margin-right: waarde;
margin-bottom: waarde;
margin-left: waarde;
```

De margin kan verschillende waarden hebben:

-   auto: de browser berekend de goede margin
-   px, pt, cm, etc.
-   %: een percentage van de breedte van het element dat eromheen zit
-   inherit: dezelfde margin als het element dat eromheen zit

Margins zijn bedoeld om een minimale hoeveelheid ruimte aan één of meer van de zijden van een element te definiëren. Om dit te faciliteren, maakt de browser gebruik van *margin collapsing*. Dit houdt in dat wanneer er twee margins boven elkaar zitten van verschillende elementen, de kleinste margin genegeerd wordt. Het resultaat is dus dat de afstand tussen de elements slechts de afstand van de grootste margin is, en niet de som van beide margins.

1.  Pas de `margin` aan van één of meerdere elementen.

#### Padding

Padding is eigenlijk het omgekeerde van een margin. Een margin bepaald de ruimte tussen de border en andere elementen, terwijl de padding de ruimte tussen de border en de content bepaalt. Padding volgt dezelfde syntax als margin.

1.  Pas de `padding` aan van één of meerdere elementen.

### Opdracht 11 - Layout

De layout van een website bepalen en programmeren is misschien wel het moeilijkste wat er is. Gelukkig zijn er in CSS een hoop gereedschappen ingebouwd om het wat makkelijker te maken. In deze opdracht leer je daarover.

#### Display

Het `display` property mag met ieder element gebruikt worden. Het is de meest belangrijke property als het op layout aankomt. `display` bepaalt namelijk of en hoe een element wordt weergeven. Ieder element valt in één van twee categorieën, namelijk `block` of @
```{=html}
<div class="inline-image">
```
@ .

Elements in de `block` categorie beginnen altijd op een nieuwe regel en gebruiken de volledige beschikbare breedte. `div`, `h1`, `p` en `section` zijn voorbeelden van block-level elements.

Elements in de @
```{=html}
<div class="inline-image">
```
@ categorie gaan altijd door op dezelfde regel en zijn zo breed als nodig is. `span`, `a` en `img` zijn voorbeelden van inline elements.

Met `display` kan je een block-level element als inline weergeven en vice versa. Een andere optie is `none`. Hiermee wordt het element helemaal niet weergeven op de website en past de rest van de layout zich zo aan alsof het element niet bestaat.

#### Position

Met `position` kan de type locatievorming voor een element bepaald worden. `position` wordt in combinatie gebruikt met `top`, `right`, `bottom` en `left` om de afstand tot die verschillende zijden te bepalen.

`position: static;` is de standaardwaarde voor `position`. Hiermee wordt het element niet op een speciale manier gepositioneerd, maar wordt het via de standaard layout van de pagina gepositioneerd.

`position: relative;` wordt gebruikt om elements relatief aan de standaardpositie te positioneren. Dit kan gebruikt worden om extra ruimte rondom een element te creëren, aangezien de omringende elements niet verplaatsen om de gaten te vullen.

`position: fixed;` wordt gebruikt om elements op een vaste plaats op het scherm te zetten. Zelf wanneer de webpagina wordt gescrold dan blijft het element op zijn plek op het scherm.

`position: absolute;` wordt gebruikt om elements op een vaste plaats binnen een gepositioneerd element te zetten. Wanneer het element niet in een gepositioneerd element zit dan wordt het gepositioneerd ten opzichte van de `body`.

`position: sticky;` wordt gebruikt om elements eerst relatief te positioneren, totdat de gebruiker voorbij het element probeert te scrollen en dan blijft het element 'vastplakken' op een bepaalde positie op het scherm.

#### Float

`float` wordt gebruikt om elements naast andere elements te laten 'drijven'. Hier kan gekozen worden tussen `float: left;` en `float: right;`.

Af en toe wil je float gebruiken maar tegelijkertijd voorkomen dat bepaalde elementen daardoor ingekort worden. Speciaal daarvoor is `clear` bedacht. Ook hierbij kan gekozen worden tussen `clear: left;` en `clear: right;`. De waarde bepaald aan welke kant er geen element gefloat mag worden.

#### Hoogte en breedte

Soms krijg je te maken met een `block` element dat eigenlijk niet de volledige breedte van de pagina in moet nemen. In dit geval kan je met `width` de breedte in `CSS` aanpassen. Hetzelfde kan je ook doen met `height` Hiervoor kan je veel verschillende waarden gebruiken, zoals pixels of percentages.

1.  Experimenteer met de gereedschappen uit deze opdracht en probeer daarmee je website een goede layout te geven. Dit is bijna de laatste stap voordat je een volledige website hebt!

### Opdracht 12 - Links

Tot nu toe hebben we bijna elk onderdeel van de website een bepaalde stijl kunnen geven. Alleen de links blijven een beetje achter. Je hebt misschien al gemerkt dat links van kleur veranderen wanneer je er op klikt en wanneer je die pagina al een keer hebt bezocht. Dit wordt bepaald in de link states.

#### Link states

Er zijn vier verschillende staten waarin links kunnen zitten:

-   `a:link` -- een normale, onbezochte link
-   `a:visited` -- een bezochte link
-   `a:hover` -- een link wanneer men er overheen zweeft met de cursor
-   `a:active` -- een link wanneer die wordt aangeklikt

Deze states kunnen gebruikt worden als selector in CSS en op die manier kun je de stijl van de link in die gevallen aanpassen. In het CSS-bestand *moeten* de selectors in dezelfde volgorde als hierboven voorkomen, anders werken ze niet.

1.  Pas de links in je `nav` aan met CSS om ze er beter uit te laten zien.

#### Links als knoppen

Je kunt deze met deze selectors links er ook uit laten zien als knoppen, door bijvoorbeeld een `background-color` of een `border` te gebruiken. Moderne websites hebben vrijwel nooit meer normale tekst als links, het zijn vaak knoppen. Kijk voor inspiratie en voorbeelden van een menubalk met CSS op [*https://www.w3schools.com/css/css_navbar.asp*](https://www.w3schools.com/css/css_navbar.asp)

1.  Pas je menubalk aan om van knoppen voorzien te zijn in plaats van tekst.

# Expert aan het woord

Speciaal voor deze module is iemand geregeld uit het vak Webdesign die jullie iets gaat vertellen. Vraag bij de docent voor meer informatie.

# Extra uitdaging

De volgende zes opdrachten zijn voor de mensen die na de uitleg van normaal HTML en CSS nog extra informatie en uitdaging kunnen gebruiken. Deze opdrachten brengen je eigen website iets dichterbij de webapps die gemaakt worden met Javascript In deze opdrachten wordt de theorie niet uitgelegd, maar krijg je in plaats daarvan de bronnen aangereikt om je eigen onderzoek te doen. Je hebt deze informatie niet nodig om het eindproduct te maken (zonder deze informatie kan je ook een 10 halen), maar het gebruiken van deze opdrachten zorgt er wel voor dat je alles beter onder de knie krijgt en een beter eindproduct kunt maken.

Ook als je extra uitdaging zoekt, hoef je deze opdrachten niet allemaal te doorlopen. Lees de beschrijvingen één voor één door en beslis daarna welke opdracht(en) je graag zou willen doen. Bekijk vervolgens de bronnen en experimenteer zelf met een toepassing binnen je eigen website.

## (Optioneel) Extra 1 -- Web Fonts

Lettertypen zijn heel bepalend in het uiterlijk van je website, daarom kan je web fonts gebruiken om alle mogelijke lettertypen te gebruiken in je website. Normaal gesproken ben je afhankelijk van de lettertypen die op de computer van de gebruiker geïnstalleerd zijn. Met web fonts voeg je lettertypen toe aan je website die de computer van de gebruiker vervolgens zelf downloadt. Bronnen:

-   Hoe gebruik je web fonts: [*https://www.w3schools.com/css/css3_fonts.asp*](https://www.w3schools.com/css/css3_fonts.asp)

-   Een font library van Google: [*https://fonts.google.com/*](https://fonts.google.com/)

## (Optioneel) Extra 2 -- Icons

Overal op websites kom je kleine figuurtjes tegen waar je op kan klikken en die bepaalde dingen aangeven. Dit zijn de zogenaamde icons. Met HTML en CSS kan je die icoontjes heel makkelijk toevoegen aan je website. Je voegt hierbij een CSS-bestand toe die online beschikbaar wordt gesteld en vervolgens gebruik je die om de verschillende icoontjes te laden. Wij raden aan om de icoontjes van Material Design van Google te gebruiken, die worden uitgelegd onderaan de website van w3schools. Bronnen:

-   Hoe gebruik je icons: [*https://www.w3schools.com/css/css_icons.asp*](https://www.w3schools.com/css/css_icons.asp)

-   Een icon library van Google: [*https://material.io/resources/icons/?style=baseline*](https://material.io/resources/icons/?style=baseline)

## (Optioneel) Extra 3 -- Dropdowns

Het is mogelijk om binnen HTML en CSS een dropdown menu te maken. Dit is een knop die, wanneer je er overheen zweeft of wanneer je er op drukt, uitklapt en meerdere andere knoppen weergeeft. Dit laat vooral zien hoe je goed gebruik kan maken van `display: none;` Het vergroot zeker je begrip van CSS Bronnen:

-   Hoe maak je een dropdown: [*https://www.w3schools.com/css/css_dropdowns.asp*](https://www.w3schools.com/css/css_dropdowns.asp)

-   Herhaling van `display`: [*https://www.w3schools.com/css/css_display_visibility.asp*](https://www.w3schools.com/css/css_display_visibility.asp)

## (Optioneel) Extra 4 -- Animaties

Het klinkt misschien heel raar, maar je kan inderdaad animaties maken met CSS Je kan hiermee zo veel properties veranderen als je wilt, zo vaak je wilt. Het is een ingewikkeld concept en zeker niet makkelijk om op te zetten, maar wanneer het eenmaal werkt dan is het dat zeker waard. Bronnen:

-   Hoe maak je een animation: [*https://www.w3schools.com/css/css3_animations.asp*](https://www.w3schools.com/css/css3_animations.asp)

## (Optioneel) Extra 5 -- Responsive Web Design

Tegenwoordig zijn er zo veel verschillende devices die websites kunnen openen dat er een hele categorie is gericht op het accommoderen van die verschillende schermgroottes. Dit heet Responsive Web Design (RWD). Het is eigenlijk een must om te weten, maar te ingewikkeld voor de normale module. Probeer dit uit als je er tijd voor hebt! Bronnen:

-   Hoe gebruik ik RWD 1: [*https://www.w3schools.com/css/css_rwd_intro.asp*](https://www.w3schools.com/css/css_rwd_intro.asp)
-   Hoe gebruik ik RWD 2: [*https://www.w3schools.com/css/css_rwd_viewport.asp*](https://www.w3schools.com/css/css_rwd_viewport.asp)
-   Hoe gebruik ik RWD 3: [*https://www.w3schools.com/css/css_rwd_grid.asp*](https://www.w3schools.com/css/css_rwd_grid.asp)
-   Hoe gebruik ik RWD 4: [*https://www.w3schools.com/css/css_rwd_mediaqueries.asp*](https://www.w3schools.com/css/css_rwd_mediaqueries.asp)
-   Hoe gebruik ik RWD 5: [*https://www.w3schools.com/css/css_rwd_images.asp*](https://www.w3schools.com/css/css_rwd_images.asp)
-   Hoe gebruik ik RWD 6: [*https://www.w3schools.com/css/css_rwd_videos.asp*](https://www.w3schools.com/css/css_rwd_videos.asp)
-   RWD Frameworks: [*https://www.w3schools.com/css/css_rwd_frameworks.asp*](https://www.w3schools.com/css/css_rwd_frameworks.asp)
-   RWD Templates: [*https://www.w3schools.com/css/css_rwd_templates.asp*](https://www.w3schools.com/css/css_rwd_templates.asp)

## (Optioneel) Extra 6 -- Bootstrap

Dit is er eentje voor de echte doorzetters. Bootstrap is een framework voor responsive web design met heel veel functionaliteit. Leren hoe je met Bootstrap moet werken is eigenlijk hetzelfde als een compleet andere programmeertaal leren binnen HTML en CSS. Maar als je veel tijd over hebt en wilt weten hoe je een perfecte responsive website maakt dan is het zeker een aanrader. Bronnen:

-   W3schools Bootstrap Tutorial: [*https://www.w3schools.com/bootstrap4/default.asp*](https://www.w3schools.com/bootstrap4/default.asp)
-   Bootstrap website: [*https://getbootstrap.com/*](https://getbootstrap.com/)
-   Bootstrap documentatie: [*https://getbootstrap.com/docs/4.3/getting-started/introduction/*](https://getbootstrap.com/docs/4.3/getting-started/introduction/)

# Eindopdracht

Na het oefenen met het maken van een website is het nu tijd om het eindproduct voor deze module te gaan maken. Zo kan je alle geleerde kennis meteen toepassen en een website maken die je nog gaat gebruiken.

De opdracht is eenvoudig: maak een website! Het onderwerp en de inhoud van de site mag je zelf bepalen, en ook het design is aan jou (maar denk wel aan wat je daarover tijdens de les hebt geleerd). 

Wat wel belangrijk is: je website moet in principe publiceerbaar zijn. Dat betekent dat je je ook aan copyright regels moet houden, en dus geen teksten of afbeeldingen kopieert die niet van jou zijn, als je daar geen toetstemming voor hebt. Dat geldt ook voor de HTML en CSS code: in principe schrijf je die zelf, tenzij je toestemming hebt om die code te kopiëren **en** je dat duidelijk vermeldt met commentaar. Zie de [Handleiding code stelen](/informatie/code-stelen-van-het-internet-of-leerling) voor meer informatie. Code die je gekopieerd hebt, telt voor de beoordeling natuurlijk niet mee in de eisen aan HTML en CSS. En voor het design krijg je ook geen punten, als dat niet je eigen design is. Je laten inspireren en zelfs elementen overnemen is prima, maar de kern moet altijd je eigen werk zijn.

## Eisen

Er zijn natuurlijk wel wat eisen aan de site, want je moet ermee laten zien dat je webdesign nu onder de knie hebt. De eisen zijn verdeeld in drie categorieën: HTML, CSS en design. Voor elk van die onderdelen kun je maximaal 3 punten krijgen. Je krijgt gratis een 1, dus met 3 punten voor elk van de onderdelen kom je op 1 + 3 + 3 + 3 = 10 als eindcijfer. Per onderdeel staat beschreven hoe het beoordeeld wordt.

### HTML

> Voor een voldoende moet je minimaal aan de **dikgedrukte** eisen voldoen.

Hoeveel werk is het?

- Gebruik minimaal **twee** verschillende webpagina’s
- **Zet op elke pagina linkjes naar de andere pagina's, bijvoorbeeld in een menu**
- Maak minimaal één link die buiten je website verwijst
- Gebruik minimaal **één** plaatje
- Maak gebruik van minimaal één tabel
- Maak gebruik van een unordered list of ordered list

Werkt het?

- **De webpagina wordt correct weergegeven in de browser**

Is de code netjes?

> Voor een voldoende moet je duidelijk een poging gedaan hebben aan de **dikgedrukte** eisen te voldoen.

- **Gebruik de structuur van `h1`, `h2`, etc. tussenkopjes**
- *Gebruik de structuur van semantic elements*
- Gebruik comments in je code <- alleen als er iets is bijzonders is
- **Gebruik goede indentation**
- Je HTML is valide volgens de [W3C HTML validator](https://validator.w3.org/#validate_by_input) (zie HTML opdracht 5)

### CSS

Hoeveel werk is het?

> Voor een voldoende moet je minimaal aan de **dikgedrukte** eisen voldoen.

- **Gebruik minimaal één CSS-bestand**
- **Geef de tekst een aangepaste stijl**
- Gebruik op ten minste 1 plek een aangepaste kleur
- Gebruik randen ten minste één keer
- Geef de verschillende link states een aangepaste stijl
- ^ **Minimaal 1 van de 3 hierboven**
- Maak gebruik van margin en padding
- Maak gebruik van `width` en/of `height`
- Gebruik een van de layout properties om elementen te positioneren
- ^ **Minimaal 1 van de 3 hierboven**
- Bonuspunten (uit de bonusopdrachten):
  - Gebruik een web font
  - Gebruik een icon
  - Maak een dropdown menu
  - Voeg animaties toe
  - Gebruik responsive webdesign technieken
  - Gebruik Bootstrap (naast je eigen CSS!)

Werkt het?

- **De webpagina wordt met de juiste stijl weergegeven in de browser**

Is de code netjes?

> Voor een voldoende moet je duidelijk een poging gedaan hebben aan de **dikgedrukte** eisen te voldoen.

- **Gebruik goede indentation**
- **Elke eigenschap is afgesloten met `;`**
- Gebruik consistente spaties en witregels
- Je CSS is valide volgens de [W3C CSS validator](https://jigsaw.w3.org/css-validator/#validate_by_input)

### Design

- Duidelijk doel
- Overzichtelijk, duidelijke structuur op de pagina
- Duidelijke navigatie tussen pagina's
- Consistent
- Tekst is leesbaar (dus bijv. niet te klein)
- Lettertype past bij de site en is goed leesbaar
- Voldoende contrast tussen kleuren (dus geen grijze tekst op een grijze achtergrond)
- Goed gebruik van afbeeldingen

Per ding 0 - 3 punten

## Geen inspiratie?

Maak een CV! Bij het solliciteren voor een nieuwe baan wordt bijna altijd om je curriculum vitae (CV) gevraagd. Voor veel mensen is dit een simpel Word-bestandje of PDF waarin de werkervaring en opleidingen van een persoon staan. Vaak wordt daar ook nog een beetje informatie over jezelf aan toegevoegd. In onze ogen is dat allemaal een beetje achterhaald, wij vinden namelijk dat iedereen binnen de informaticawereld een online CV moet hebben! Dat is dan ook de opdracht, je gaat een website maken als vervanging voor je CV.

Als je nog nooit een CV hebt gemaakt dan is [deze site](http://www.carrieretijger.nl/carriere/solliciteren/sollicitatiebrief-en-cv/cv-opstellen) misschien een goede plek om te beginnen. Als je al een CV hebt dan is het slechts een kwestie van die informatie in een goede website verwerken!

# Appendix A -- Definities

Een lijst van definities in de volgorde dat ze voor het eerst voorkomen in de module.

**Webdesign**: Het vormgeven van websites in het internet, waarbij ook het technisch ontwikkelen van websites als onderdeel wordt gezien.

**HTML**: HyperText Markup Language is een opmaaktaal voor de specificatie van documenten, voornamelijk bedoeld voor het wereldwijde web.

**CSS**: Cascading Style Sheets zijn een mogelijkheid om de vormgeving van webpagina's los te koppelen van hun feitelijke inhoud en centraal vast te leggen.

**Webapp**: Een client-side computerprogramma die wordt gedraaid in een webbrowser.

**JavaScript**: Een scripttaal om webpagina's interactief te maken en webapplicaties te ontwikkelen.

**Developer Tools**: Een groep gereedschappen binnen een webbrowser die een programmeur helpen bij het ontwikkelen van de website.

**Inspector**: Een developer tool om te zien hoe de HTML van een website is opgebouwd.

**Performance**: Een developer tool om bij te houden hoeveel geheugen een website gebruikt.

**Console**: Een developer tool waarmee waarden en errorberichten in de website uitgelezen kunnen worden.

**HyperText**: Tekst met direct activeerbare verwijzingen.

**Markup**: Een systeem voor het samenstellen van een document dat uit de syntax van het bestand uit te lezen is.

**World Wide Web:** Een aantal technische afspraken voor het wereldwijd over het internet aanbieden en verbinden van documenten en computertoepassingen in combinatie met de verzameling documenten en toepassingen die wereldwijd volgens dit systeem over het internet worden aangeboden.

**Webserver**: De computer met een programma dat via een netwerk HTTP-verzoeken ontvangt en documenten naar de client stuurt.

**Elements:** Aanwijzers in een HTML-bestand die aangeven wat voor soort informatie op een bepaalde plek weergeven moet worden.

**Tags:** De manier waarop een element in een markup taal wordt weergeven.

**Empty tag**: Een tag van een element zonder inhoud.

**Start tag**: Het begin van een element met twee tags.

**End tag**: Het einde van een element met twee tags.

**Attributes**: Opties die gebruikt kunnen worden om meer informatie toe te voegen aan een element.

**Boilerplate code**: De aanduiding voor code die regelmatig terugkeert maar niet of nauwelijks effect heeft op de inhoud.

**Metadata**: Gegevens die de karakteristieken van bepaalde gegevens beschrijven.

**Comments:** Stukken tekst die niet uitmaken voor de website, maar die er alleen zijn om extra context te geven aan de mensen die je code lezen.

**WebStorm:** Een IDE die speciaal is gemaakt om websites mee te maken.

**IDE:** Een Integrated Development Environment is een programma wat speciaal is gemaakt om software mee te schrijven met speciale gereedschappen voor programmeurs.

**Debug mode:** Een modus in een IDE dat de programmeur de mogelijkheid geeft om terwijl het programma bezig is de interne staat van het programma te wijzigen.

**Syntax highlighting:** Een onderdeel van IDE's waarbij tekst met verschillende functies verschillende kleuren krijgt toegewezen.

**Indentation:** Lege ruimte aan het begin van een regel wat de structuur van code helpt communiceren.

**Semantic Elements:** Elementen in een HTML-bestand met een vaste betekenis en een vaste plaats.

**Stijlregel:** Een regel in een CSS-bestand die een bepaald visueel aspect van een website aanpast.

**Selector:** Het deel van een CSS-stijlregel die specificeert welk element of welke elements het doel zijn.

**Property:** Het deel van een CSS-stijlregel die specificeert welk visuele aspect aangepast moet worden.

**Inline styling:** Wanneer de stijlregels binnen een HTML-bestand binnen het doelelement worden toegevoegd.

**Internal stylesheet:** Wanneer de stijlregels binnen een HTML-bestand in een apart element worden toegevoegd.

**External stylesheet:** Wanneer de stijlregels voor een HTML-bestand in een apart bestand worden toegevoegd.

**RGB:** Een systeem om kleuren te definiëren waarbij 3 getallen gebruikt worden die waarden voor Rood, Groen en Blauw licht representeren.

**RGBA:** Een systeem om kleuren te definiëren waarbij 4 getallen gebruikt worden die de waarden voor Rood licht, Groen licht, Blauw licht en transparantie representeren.

**HEX:** Een systeem om kleuren te definiëren waarbij 3 getallen in hexadecimaal formaat gebruikt worden die de waarden voor rood, groen en blauw licht representeren.

**HSL:** Een systeem om kleuren te definiëren waarbij 3 getallen gebruikt worden die de waarden voor tint, verzadiging en helderheid representeren.

**HSLA:** Een systeem om kleuren te definiëren waarbij 4 getallen gebruikt worden die de waarden voor tint, verzadiging, helderheid en transparantie representeren.

**Serif:** Een categorie van lettertypen met kleine streepjes aan de uiteinden van letters.

**Sans-serif:** Een categorie van lettertypen zonder kleine streepjes aan de uiteinden van letters.

**Monospace:** Een categorie van lettertypen waarbij alle tekens dezelfde breedte hebben.

**Het box model:** Een model wat gebruikt wordt om het design en de layout van HTML elements te bespreken die uitgaat van dozen die in elkaar zitten.

# Appendix B -- HTML Reference

Een lijst van elements en hoe ze precies toegepast moeten worden kan gevonden worden op: [*https://www.w3schools.com/tags/default.asp*](https://www.w3schools.com/tags/default.asp)

# Appendix C -- CSS Reference

Een lijst van CSS properties en hoe ze precies toegepast moeten worden kan gevonden worden op: *https://www.w3schools.com/cssref/default.asp*
