# Spaß mit Flaggen - Aufgabe 5 (box-shadow)

## Ziel

Ziel dieser Aufgabe ist es Box-Shadow zu nutzen, um Elemente optisch zu duplizieren und zu verschieben.

## Aufgabenstellung

Baue die folgenden Nationalflaggen mit reinem HTML und CSS:

- 🇩🇪 Deutschland
- 🇮🇪 Irland
- 🇲🇺 Mauritius
- 🇹🇭 Thailand

## Anforderungen

- Es sollte die CSS-Eigenschaft box-shadow in Kombination mit der Pseudoklasse ::before zur Erstellung der Flaggen genutzt werden.
- Pro Flagge sollte nur ein einziges HTML-Element genutzt werden. Alle Streifen müssen über dieses Element und dessen Pseudoelemente erzeugt werden.
- Für die Grundmaße und Farben der Flaggen sollten CSS-Variablen genutzt werden.
- Es sollte CSS-Nesting genutzt werden.
- Es sollten keine Libraries oder Frameworks genutzt werden.

## Ressourcen

- <a href="https://developer.mozilla.org/de/docs/Web/CSS/Reference/Properties/box-shadow">box-shadow | MDN</a>
  generierter-css-content-mit-before-und-after/">::before | Kulturbanause</a>
- <a href="https://www.mediaevent.de/css/nesting.html">CSS Nesting | mediaeveent</a>
- <a href="https://www.mediaevent.de/css/variable.html">CSS-Variablen | mediaevent</a>
- <a href="https://kulturbanause.de/blog/berechnungen-mit-css-calc/">Berechnungen in CSS | kulturbanause</a>

## Hinweise

### Seitenverhältnisse der Flaggen

- 🇩🇪 Deutschland: 5:3
- 🇮🇪 Irland: 2:1
- 🇲🇺 Mauritius: 3:2
- 🇹🇭 Thailand 3:2

### Farben der Flaggen

Die folgenden Farben können für die Erstellung der Flaggen genutzt werden:

- 🇩🇪 Deutschland: rgb(0, 0, 0), rgb(255, 0, 0), rgb(255, 204, 0)
- 🇮🇪 Irland: rgb(22, 155, 98), rgb(255, 255, 255), rgb(255, 136, 62)
- 🇲🇺 Mauritius: rgb(208, 28, 31), rgb(45, 51, 89), rgb(247, 183, 24), rgb(0, 134, 88)
- 🇹🇭 Thailand: rgb(165, 25, 49), rgb(45, 42, 74), rgb(255, 255, 255)

### Abmessungen der Elemente


- 🇹🇭 Die Streifen der Nationalflagge von Thailand stehen in dem Verhältnis 1:1:2:1:1.

## Erlaubte CSS-Eigenschaften

- background-color
- box-shadow
- content
- display
- width, height
- calc()
