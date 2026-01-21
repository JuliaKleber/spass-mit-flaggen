# Spaß mit Flaggen - Aufgabe 7 (Schatten)

## Ziel

Ziel dieser Aufgabe ist es Box-Shadow oder Text-Shadow zu nutzen, um Elemente optisch zu duplizieren und zu verschieben.

## Aufgabenstellung

Erstelle die folgenden Nationalflaggen mit reinem HTML und CSS:

- 🇳🇱 Niederlande
- 🇮🇹 Italien
- 🇲🇺 Mauritius
- 🇹🇭 Thailand
- 🇪🇺 Europäische Union

## Anforderungen

- Es sollen die CSS-Eigenschaften box-shadow und text-shadow in Kombination mit der Pseudoklasse ::before zur Erstellung der Flaggen genutzt werden.
- Pro Flagge sollte nur ein einziges HTML-Element genutzt werden. Alle Streifen müssen über dieses Element und dessen Pseudoelemente erzeugt werden.
- Die html-Datei soll nicht verändert werden. Nur das Stylesheet (styles.css) soll vervollständigt werden.
- Für die Grundmaße und Farben der Flaggen sollen CSS-Variablen genutzt werden.
- Es soll CSS-Nesting genutzt werden.
- Es sollen keine Libraries oder Frameworks genutzt werden.

## Ressourcen

- <a href="https://developer.mozilla.org/de/docs/Web/CSS/Reference/Properties/box-shadow">box-shadow | MDN</a>
- <a href="https://www.mediaevent.de/css/text-shadow.html">text-shadow | mediaevent</a>
- <a href="https://www.w3schools.com/cssref/css3_pr_text-shadow.php">text-shadow | w3schools</<a>
- <a href="https://kulturbanause.de/blog/generierter-css-content-mit-before-und-after/">::before & ::after | kulturbanause</a>
- <a href="https://www.mediaevent.de/css/nesting.html">CSS Nesting | mediaeveent</a>
- <a href="https://www.mediaevent.de/css/variable.html">CSS-Variablen | mediaevent</a>
- <a href="https://kulturbanause.de/blog/berechnungen-mit-css-calc/">Berechnungen in CSS | kulturbanause</a>

## Hinweise

### Seitenverhältnisse der Flaggen

- 🇳🇱 Niederlande 3:2
- 🇮🇹 Italien 3:2
- 🇲🇺 Mauritius: 3:2
- 🇹🇭 Thailand 3:2
- 🇪🇺 Europäische Union 3:2

### Farben der Flaggen

Die folgenden Farben können für die Erstellung der Flaggen genutzt werden:

- 🇳🇱 Niederlande: rgb(173, 29, 37), rgb(255, 255, 255), rgb(30, 71, 133)
- 🇮🇹 Italien: rgb(0, 140, 69), rgb(244, 245, 240), rgb(205, 33, 42)
- 🇲🇺 Mauritius: rgb(208, 28, 31), rgb(45, 51, 89), rgb(247, 183, 24), rgb(0, 134, 88)
- 🇹🇭 Thailand: rgb(165, 25, 49), rgb(45, 42, 74), rgb(244, 245, 248)
- 🇪🇺 Europäische Union: rgb(0, 51, 153), rgb(255, 204, 0)

### Abmessungen der Elemente

- 🇹🇭 Die Streifen der Nationalflagge von Thailand stehen in dem Verhältnis 1:1:2:1:1.
- 🇪🇺 Europäische Union: Für die Größe eines Sterns kann 9% der Flaggenbreite angenommen werden. Der Stern kann mit den Unicode \2605 erzeugt werden. Der Radius des Sternenkreis ist ca. 1/3 der Flaggenhöhe.

## Erlaubte CSS-Eigenschaften

- width, height
- background-color, color
- box-shadow
- content
- display
- text-shadow
- line-height, font-size
- position, top, left, translate
- calc()
