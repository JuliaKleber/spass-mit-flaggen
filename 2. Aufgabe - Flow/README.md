# Spaß mit Flaggen - Aufgabe 2 (CSS Box Model)

## Ziel

In dieser Aufgabe soll es darum gehen zu verstehen, wie Elemente im Document Flow angeordnet werden. Insbesondere geht es um die Ausprägungen block, inline-block und inline der CSS-Eigenschaft display.

## Aufgabenstellung

Baue die folgenden Nationalflaggen mit reinem HTML und CSS:

- 🇳🇱 Niederlande
- 🇮🇹 Italien
- 🇲🇺 Mauritius
- 🇧🇯 Benin

## Anforderungen

- Es sollte konsequent der normale <u>Document-Flow</u> zur Erstellung der Flaggen genutzt werden. Position, Flexbox, Grid, Padding usw. sind nicht erlaubt. Stattdessen sollte nur display: block, display: inline-block und display: inline genutzt werden um die Elemente zu positionieren.
- Für die Grundmaße und Farben der Flaggen sollten CSS-Variablen genutzt werden.
- Es sollte CSS-Nesting genutzt werden.
- Es sollten keine Libraries oder Frameworks genutzt werden.

## Ressourcen

- <a href="https://www.w3schools.com/css/css_boxmodel.asp">CSS Box Model | w3schools</a>
- <a href="https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/CSS_layout/Introduction">Einführung in CSS-Layout | MDN</a>
- <a href="https://www.w3schools.com/css/css_inline-block.asp">inline-block | w3schools</a>
- <a href="https://css-tricks.com/fighting-the-space-between-inline-block-elements/">Fighting the space between inline block elements | CSS Tricks</a>
- <a href="https://www.mediaevent.de/css/nesting.html">CSS Nesting | mediaevent</a>
- <a href="https://www.mediaevent.de/css/variable.html">CSS-Variablen | mediaevent</a>
- <a href="https://kulturbanause.de/blog/berechnungen-mit-css-calc/">Berechnungen in CSS | kulturbanause</a>

## Hinweise

### Seitenverhältnisse der Flaggen

- 🇳🇱 Niederlande 3:2
- 🇮🇹 Italien 3:2
- 🇲🇺 Mauritius 3:2
- 🇧🇯 Benin 3:2

### Farben der Flaggen

Die folgenden Farben können für die Erstellung der Flaggen genutzt werden:

- 🇳🇱 Niederlande: rgb(174, 28, 40), rgb(255, 255, 255), rgb(33, 70, 139)
- 🇮🇹 Italien: rgb(0, 140, 69), rgb(244, 245, 240), rgb(205, 33, 42)
- 🇲🇺 Mauritius: rgb(208, 28, 31), rgb(45, 51, 89), rgb(247, 183, 24), rgb(0, 134, 88)
- 🇧🇯 Benin: rgb(0, 136, 86), rgb(252, 209, 22), rgb(227, 28, 35)

### Abmessungen der Elemente

- 🇧🇯 Der grüne vertikale Streifen in der Flagge von Benin nimmt 40 % der Breite der Flagge ein.

### Erlaubte CSS-Eigenschaften

- display
- width, height
- background-color
- font-size
- vertical-align
- calc()
