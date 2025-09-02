# Oefening 5 - Validatie (Optioneel)

Het is in het algemeen bekend dat mensen fouten maken. Dit betekent dat ook jij fouten gaat maken in je HTML code. Het vervelende aan HTML is dat foutjes vaak niet meteen tot problemen leiden. Het komt dan helaas wel voor dat het later voor problemen gaat zorgen en dat het heel moeilijk is om de bron van het probleem te vinden.

Gelukkig gebruiken we in deze module **Visual Studio Code** (VS Code). In VS Code zie je het namelijk meteen wanneer je foutjes maakt: er verschijnen gekleurde golfjes onder je code en je vindt alle meldingen in het **Problems**-paneel (Windows/Linux: **Ctrl+Shift+M**, macOS: **Cmd+Shift+M**). Vaak kun je met **Ctrl+.** (macOS: **Cmd+.**) een *Quick Fix* uitvoeren om het probleem snel op te lossen.

Voordat editors zo goed werden in foutdetectie controleerden we HTML via een externe validator. Daarvoor werd de HTML validator van W3C veel gebruikt. Deze validator werkt nog steeds. Op deze website kun je jouw HTML invoeren en uitvinden of er foutjes in zitten. Bij het checken krijg je te maken met twee verschillende soorten meldingen, de **errors** en de **warnings**. Bij errors is het de bedoeling dat je de code aanpast zodat de error verdwijnt. Dit zijn foutjes in de code die tot problemen gaan leiden. Bij warnings is het de bedoeling dat je nagaat of het van toepassing is op jouw website. Warnings worden vooral gegeven wanneer je niet de beste programmeergewoontes aanhoudt. De validator vind je hier: <https://validator.w3.org/#validate_by_input>

In het hoofdstuk {ref}`benodigheden` kun je opzoeken hoe je een validator als plugin voor Visual Studio Code installeert.

:::{exercise}
Gebruik de validator om de code van je website uit Oefening 4 te controleren. Pas zo nodig de code aan om in ieder geval de errors weg te laten gaan.
:::

De validator kan ook gebruikt worden om CSS te valideren op: *<https://jigsaw.w3.org/css-validator/#validate_by_input>* Omdat VS Code veel CSS-foutjes direct aangeeft, hoef je de W3C CSS-validator niet altijd te gebruiken — maar het is een handig extra controlemiddel.
