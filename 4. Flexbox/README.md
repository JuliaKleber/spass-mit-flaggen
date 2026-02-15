# Spaß mit Flaggen - Flexbox

## Ziel

Ziel der Aufgabe ist es, zu Lernen Elemente mit Flexbox anzuordnen.

## Aufgabenstellung

Erstelle die folgenden Nationalflaggen mit reinem HTML und CSS:

- 🇳🇱 Niederlande
- 🇮🇹 Italien
- 🇲🇺 Mauritius
- 🇹🇭 Thailand
- 🇧🇯 Benin
- 🇯🇵 Japan
- 🇨🇭 Schweiz

## Anforderungen

- Es soll konsequent Flexbox zur Erstellung der Flaggen genutzt werden.
- Einschränkungen: Die Verwendung von `border`, `padding`, `position`, `display: block`, `display: inline`, `display: inline-block`, `grid`, `linear-gradient`, `clip-path` oder `svg` ist nicht erlaubt.
- Keine HTML-Änderungen: Die Struktur der bereitgestellten HTML-Datei darf nicht verändert werden.
- Modernes CSS: Nutze CSS-Variablen für Farben und Grundmaße sowie CSS-Nesting für eine saubere Struktur.
- Tools: Es sollen keine Bibliotheken oder Frameworks genutzt werden.

## Ressourcen

- <a href="https://www.joshwcomeau.com/css/interactive-guide-to-flexbox/">An Interactive Guide to Flexbox | Josh Comeau</a>
- <a href="https://flexboxfroggy.com/">Flexbox Tutorial | Flexbox Froggy</a>
- <a href="https://css-tricks.com/snippets/css/a-guide-to-flexbox/">CSS Flexbox Layout Guide | CSS-Tricks</a>
- <a href="https://www.mediaevent.de/css/nesting.html">CSS Nesting | mediaevent</a>
- <a href="https://www.mediaevent.de/css/variable.html">CSS-Variablen | mediaevent</a>
- <a href="https://kulturbanause.de/blog/berechnungen-mit-css-calc/">Berechnungen in CSS | kulturbanause</a>

## Hinweise

### Seitenverhältnisse der Flaggen

- 🇳🇱 Niederlande 3:2
- 🇮🇹 Italien 3:2
- 🇲🇺 Mauritius 3:2
- 🇹🇭 Thailand 3:2
- 🇧🇯 Benin 3:2
- 🇯🇵 Japan 3:2
- 🇨🇭 Schweiz 1:1

### Farben der Flaggen

Die folgenden Farben können für die Erstellung der Flaggen genutzt werden:

- 🇳🇱 Niederlande: rgb(173, 29, 37), rgb(255, 255, 255), rgb(30, 71, 133)
- 🇮🇹 Italien: rgb(0, 140, 69), rgb(244, 245, 240), rgb(205, 33, 42)
- 🇲🇺 Mauritius: rgb(208, 28, 31), rgb(45, 51, 89), rgb(247, 183, 24), rgb(0, 134, 88)
- 🇹🇭 Thailand: rgb(165, 25, 49), rgb(45, 42, 74), rgb(244, 245, 248)
- 🇧🇯 Benin: rgb(0, 136, 80), rgb(252, 210, 15), rgb(233, 9, 41)
- 🇯🇵 Japan: rgb(255, 255, 255), rgb(188, 0, 45)
- 🇨🇭 Schweiz: rgb(255, 0, 0), rgb(255, 255, 255)

### Abmessungen der Elemente

- 🇹🇭 Die Streifen der Nationalflagge von Thailand stehen in dem Verhältnis 1:1:2:1:1.
- 🇧🇯 Der grüne vertikale Streifen in der Flagge von Benin nimmt 40 % der Breite der Flagge ein.
- 🇯🇵 Der Durchmesser des Kreises in der japanischen Flagge beträgt 60 % der Höhe der Flagge. Der Kreis ist zentriert.
- 🇨🇭 Für das Seitenverhältnis der weißen Balken in der Schweizer Flagge kann 6:20 angenommen werden. Die Höhe des Kreuzes der schweizer Flagge entspricht 5/8 der Höhe der Flagge.

### Erlaubte CSS-Eigenschaften

- display
- flex, flex-direction, justify-content, align-items, gap und weitere flex-Eigenschaften
- width, height, aspect-ratio
- background-color
- border-radius
- calc()
