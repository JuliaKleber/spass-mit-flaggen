# Spaß mit Flaggen - Aufgabe 7 (Rotationen)

## Ziel

Ziel der Aufgabe ist es Rotationen zu benutzen.

## Aufgabenstellung

Erstelle die folgenden Nationalflaggen mit reinem HTML und CSS:

- 🏴󠁧󠁢󠁳󠁣󠁴󠁿 Schottland
- 🇹🇹 Trinidad und Tobago

## Anforderungen

- Die Flaggen sollen unter Zuhilfenahme von position: absolute und rotate implementiert werden.
- Für die Grundmaße und Farben der Flaggen sollen CSS-Variablen genutzt werden.
- Es soll CSS-Nesting genutzt werden.
- Es sollen keine Libraries oder Frameworks genutzt werden.

## Ressourcen

- <a href="https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Values/transform-function/rotate">rotate | MDN</a>
- <a href="https://www.w3schools.com/css/css_positioning.asp">Position | w3schools</a>
- <a href="https://www.mediaevent.de/css/visualeffects-overflow.html">overflow | mediaevent</a>
- <a href="https://www.mediaevent.de/css/nesting.html">CSS Nesting | mediaevent</a>
- <a href="https://www.mediaevent.de/css/variable.html">CSS-Variablen | mediaevent</a>
- <a href="https://kulturbanause.de/blog/berechnungen-mit-css-calc/">Berechnungen in CSS | kulturbanause</a>

## Hinweise

### Seitenverhältnisse der Flaggen

- 🏴󠁧󠁢󠁳󠁣󠁴󠁿 Schottland 3:2
- 🇹🇹 Trinidad und Tobago 5:3

## Farben der Flaggen

Die folgenden Farben können für die Erstellung der Flaggen genutzt werden:

- 🏴󠁧󠁢󠁳󠁣󠁴󠁿 Schottland: rgb(0, 94, 184), rgb(255, 255, 255)
- 🇹🇹 Trinidad und Tabago: rgb(200, 16, 46), rgb(255, 255, 255), rgb(0, 0, 0);

### Abmessungen der Elemente

- 🏴󠁧󠁢󠁳󠁣󠁴󠁿 Die Breite der Balken der schottischen Flagge beträgt 20% der Höhe der Flagge. Sie sind um 33.7 Grad zur Waagerechten gedreht.
- 🇹🇹 Die Streifen in der Flagge von Trinidad und Tobago sind um 41 Grad gedreht. Die Breite des weißen Streifens entspricht 33% der Höhe der Flagge und die Breite des schwarzen Streifens entspricht 22% der Höhe der Flagge.

## Benötigte CSS-Eigenschaften

- background-color
- height, width
- position
- top, bottom, right, left
- transformations: rotate, translate
- overflow
- calc()
