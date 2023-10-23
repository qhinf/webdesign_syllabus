# Opdracht 8 - Tekst

We hebben het bij opdracht 1 over simpele elementen al een beetje gehad over het formatteren van tekst. Dit kan met HTML gedaan worden met tags, maar dit kan ook gedaan worden met CSS. Zoals je in de vorige opdracht al hebt gezien bepaal je de kleur van de tekst met `color`, maar ook andere opmaak zoals het lettertype kunnen bepaald worden.

Bij het geven van opmaak aan tekst moet de leesbaarheid van de tekst altijd voorop staan. Hier zijn een aantal basis principes voor ontwikkeld. Deze kan je hier vinden: <https://www.oogvereniging.nl/leven-werken/alle-onderwerpen/boeken-lezen/handreiking-bruikbaarheid-gedrukte-tekst/>

## Align

Tekst kan binnen CSS met `text-align` uitgelijnd worden naar links, naar het midden of naar rechts. De waarden hiervoor zijn respectievelijk `left`, `center` en `right`.

1.  Voeg een `text-align` toe aan één of meerdere elementen naar keuze.

## Decoration

Met `text-decoration` kan bepaald worden of er lijnen boven, door of onder te tekst geplaatst worden. De waarden hiervoor zijn respectievelijk `overline`, `line-through` en `underline`. Je kan met `text-decoration` ook de standaard lijnen onder links weghalen met de waarde `none`.

1.  Voeg een `text-decoration` toe of verwijder deze bij één of meerdere elementen naar keuze.

## Shadow

Met `text-shadow` kan een schaduw toegevoegd worden aan tekst. Dit volgt de volgende syntax: `text-shadow: horizontale-positie verticale-positie` Hierbij zijn de posities in pixels en mogen deze ook negatief zijn. Ook heb je de mogelijkheid om de kleur van de schaduw en de hoeveelheid vervaging van de schaduw bepalen met respectievelijk `color` in kleuren en `blur-radius` in pixels.

1.  Voeg een `text-shadow` toe aan één of meerdere elementen naar keuze.

## Font-family

Er worden op websites heel veel verschillende lettertypen gebruikt en deze worden toegepast met CSS. Er zijn drie hoofdcategorieën lettertypen die belangrijk zijn om te kennen, **Serif** en **Sans-serif** staan hiernaast. De derde is **Monospace**, alle lettertypen binnen deze categorie hebben letters die allemaal een gelijke breedte zijn.

![Image result for serif sans serif](../assets/image12.png)

Omdat je online met veel verschillende computers en browsers te maken krijgt, is het de bedoeling dat je meer mogelijke lettertypen aangeeft voor een bepaald stuk tekst. Dit wordt gedaan met `font-family` met de volgende syntax: `font-family: "Times New Roman", Times, serif;`. Hier begin je met het lettertype dat je in het ideale geval wilt gebruiken en bouw je af naar uiteindelijk een hoofdcategorie. Alle browsers hebben ten minste één lettertype uit alle hoofdcategorieën. Door op deze manier `font-family` te gebruiken weet een browser altijd welk lettertype gebruikt moet worden. Kijk voor veilige lettertypen combinaties op de volgende pagina: [*https://www.w3schools.com/cssref/css_websafe_fonts.asp*](https://www.w3schools.com/cssref/css_websafe_fonts.asp)

1.  Voeg een `font-family` toe aan één of meerdere elementen naar keuze.

## Font-style

Het is natuurlijk ook mogelijk om een stuk tekst met CSS schuingedrukt te laten zijn, dit wordt gedaan met `font-style`. Hiermee kan je de tekst recht of schuingedrukt maken met respectievelijk *normal* en *italic*.

1.  Voeg een `font-style` toe aan één of meerdere elementen naar keuze.

## Font-weight

Tekst dikgedrukt maken doe je met `font-weight`. Hierbij gebruik je `normal` om de tekst niet dikgedrukt te maken en `bold` om de tekst wel dikgedrukt te maken.

1.  Voeg een `font-weight` toe aan één of meerdere elementen naar keuze.

## Font-size

De grootte van de tekst kan uiteraard ook aangepast worden in CSS. Dit kan gedaan worden met `font-size` Hier moeten developers echter een belangrijke keuze maken. Het is namelijk mogelijk om de grootte van de tekst vast te zetten in pixels, hierbij kun je er te allen tijde zeker van zijn dat de tekst een bepaalde grootte heeft. Het is echter ook mogelijk om de grootte van de tekst te bepalen in *em*, hierbij is *1em* gelijk aan 16px. Door *em* te gebruiken kunnen gebruikers zelf in het menu van hun browser aanpassen hoe groot de tekst moet zijn. Doordat sommige mensen kleine tekst slecht kunnen lezen, is het een goed idee om de tekstgrootte in *em* te gebruiken. Als je al een bepaalde grootte in pixels in je hoofd hebt dan hoef je deze slechts te delen door 16 om je *em* waarde te verkrijgen.

1.  Voeg een `font-size` toe aan één of meerdere elementen naar keuze en gebruik daarvoor een waarde in em.
