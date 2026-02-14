# Spaß mit Flaggen - Normal Flow

## Ziel

In dieser Aufgabe soll es darum gehen zu verstehen, wie Elemente im Normal Flow bzw. Document Flow angeordnet werden. Insbesondere geht es um die Ausprägungen `block`, `inline-block` und `inline` der CSS-Eigenschaft `display`.

## Aufgabenstellung

Erstelle die folgenden Nationalflaggen mit reinem HTML und CSS:

- 🇳🇱 Niederlande
- 🇮🇹 Italien
- 🇲🇺 Mauritius
- 🇹🇭 Thailand
- 🇧🇯 Benin

## Anforderungen

- Es soll konsequent der Normal Flow zur Erstellung der Flaggen genutzt werden. Es sollte nur `display: block`, `display: inline-block` und `display: inline` genutzt werden um die Elemente zu positionieren.
- Einschränkungen: Die Verwendung von `border`, `padding`, `position`, `flex`, `grid`, `linear-gradient`, `clip-path` oder `svg` ist nicht erlaubt.
- Keine HTML-Änderungen: Die Struktur der bereitgestellten HTML-Datei darf nicht verändert werden.
- Modernes CSS: Nutze CSS-Variablen für Farben und Grundmaße sowie CSS-Nesting für eine saubere Struktur.
- Tools: Es sollen keine Bibliotheken oder Frameworks genutzt werden.

## Ressourcen

- <a href="https://www.w3schools.com/css/css_boxmodel.asp">CSS Box Model | w3schools</a>
- <a href="https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/CSS_layout/Introduction">Einführung in CSS-Layout | MDN</a>
- <a href="https://www.w3schools.com/css/css_inline-block.asp">inline-block | w3schools</a>
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

### Farben der Flaggen

Die folgenden Farben können für die Erstellung der Flaggen genutzt werden:

- 🇳🇱 Niederlande: rgb(173, 29, 37), rgb(255, 255, 255), rgb(30, 71, 133)
- 🇮🇹 Italien: rgb(0, 140, 69), rgb(244, 245, 240), rgb(205, 33, 42)
- 🇲🇺 Mauritius: rgb(208, 28, 31), rgb(45, 51, 89), rgb(247, 183, 24), rgb(0, 134, 88)
- 🇹🇭 Thailand: rgb(165, 25, 49), rgb(45, 42, 74), rgb(244, 245, 248)
- 🇧🇯 Benin: rgb(0, 136, 80), rgb(252, 210, 15), rgb(233, 9, 41)

### Abmessungen der Elemente

- 🇹🇭 Die Streifen der Nationalflagge von Thailand stehen in dem Verhältnis 1:1:2:1:1.
- 🇧🇯 Der grüne vertikale Streifen in der Flagge von Benin nimmt 40 % der Breite der Flagge ein.

### Erlaubte CSS-Eigenschaften

- display
- width, height
- background-color
- font-size
- vertical-align
- calc()

## Zum Weiterlesen

- <a href="https://www.joshwcomeau.com/css/understanding-layout-algorithms/">Understanding Layout Algorithms | Josh Comeau</a>
- <a href="https://css-tricks.com/fighting-the-space-between-inline-block-elements/">Fighting the space between inline block elements | CSS Tricks</a>
