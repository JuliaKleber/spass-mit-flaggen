# Dreiecke

## Aufgabenstellung

Erstelle die folgenden Nationalflaggen mit reinem HTML und CSS:

- 🇨🇿 Tschechische Republik
- 🇧🇸 Bahamas

## Anforderungen

- Jede Flagge soll drei Mal erzeugt werden. Ein Mal mit der css-Eigenschaft border, ein Mal mit clip-path und ein Mal mit Gradienten.
- Es sollte ::before oder ::after für die Dreiecke genutzt werden.
- Es gibt keine Vorgaben für die Erzeugung der Streifen.
- Für die Maße der Flaggen und Farben sollen CSS-Variablen genutzt werden.
- Es sollen keine Libraries oder Frameworks genutzt werden.

## Ressourcen

- <a href="https://www.html-seminar.de/css-dreieck-ohne-grafiken-ueber-css.htm">Dreiecke mit Border erstellen | html-seminar</a>
- <a href="https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/clip-path">clip-path | MDN</a>
- <a href="https://css-tricks.com/almanac/properties/c/clip-path/">clip-path | CSS Tricks</a>
- <a href="https://www.w3schools.com/cssref/func_conic-gradient.php">conic-gradient() | w3schools</a>
- <a href="https://kulturbanause.de/blog/generierter-css-content-mit-before-und-after/">::before & ::after | kulturbanause</a>
- <a href="https://www.mediaevent.de/css/nesting.html">CSS Nesting | mediaevent</a>
- <a href="https://www.mediaevent.de/css/variable.html">CSS-Variablen | mediaevent</a>
- <a href="https://kulturbanause.de/blog/berechnungen-mit-css-calc/">Berechnungen in CSS | kulturbanause</a>

## Hinweise

### Seitenverhältnisse der Flaggen

- 🇨🇿 Tschechische Republik: 3:2
- 🇧🇸 Bahamas: 2:1

## Farben der Flaggen

Die folgenden Farben können für die Erstellung der Flaggen genutzt werden:

- 🇨🇿 Tschechische Republik: rgb(255, 255, 255), rgb(215, 20, 26), rgb(17,49,126)
- 🇧🇸 Bahamas: rgb(0, 169, 206), rgb(255, 199, 44), rgb(0, 0, 0),

### Abmessungen der Elemente

- 🇨🇿 Das Dreieck in der tschechischen Flagge ist so breit wie die Hälfte der Länge der Flagge.
- 🇧🇸 Das Dreieck der Flagge der Bahamas ist die Länge der Flagge geteilt durch 2,2.

## Benötigte CSS-Eigenschaften

- background-color
- height, width
- border, border-top, border-bottom, border-left
- clip-path
- position, bottom, top, left, right
- ::before, ::after
- content
- calc()
