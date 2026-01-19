# Spaß mit Flaggen - Aufgabe 4 (CSS Grid)

## Ziel

Ziel der Aufgabe ist es, zu Lernen Elemente mit Grid anzuordnen.

## Aufgabenstellung

Erstelle die folgenden Nationalflaggen ausschließlich mit HTML und CSS:

- 🇳🇱 Niederlande
- 🇮🇹 Italien
- 🇲🇺 Mauritius
- 🇹🇭 Thailand
- 🇧🇯 Benin
- 🇯🇵 Japan
- 🇵🇼 Palau
- 🇨🇭 Schweiz
- 🇸🇪 Schweden

## Anforderungen

- Es sollte konsequent Grid zur Erstellung der Flaggen genutzt werden.
- Für die Grundmaße der Flaggen und die Farben sollten CSS-Variablen genutzt werden.
- Es sollte CSS-Nesting genutzt werden.
- Es sollten keine Libraries oder Frameworks genutzt werden.

## Ressourcen

- <a href="https://cssgridgarden.com/#de">Grid Tutorial | Grid Garden</a>
- <a href="https://css-tricks.com/css-grid-layout-guide/">Grid | CSS Tricks</a>
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
- 🇵🇼 Pal- 🇹🇭 Thailand 3:2
au: 8:5
- 🇨🇭 Schweiz 1:1
- 🇸🇪 Schweden 16:10

Der Einfachheit halber kann ein Seitenverhältnis für alle Flaggen von 3:2 angenommen werden.

### Farben der Flaggen

Die folgenden Farben können für die Erstellung der Flaggen genutzt werden:

- 🇳🇱 Niederlande: rgb(174, 28, 40), rgb(255, 255, 255), rgb(33, 70, 139)
- 🇮🇹 Italien: rgb(0, 140, 69), rgb(244, 245, 240), rgb(205, 33, 42)
- 🇲🇺 Mauritius: rgb(208, 28, 31), rgb(45, 51, 89), rgb(247, 183, 24), rgb(0, 134, 88)
- 🇹🇭 Thailand: rgb(165, 25, 49), rgb(45, 42, 74), rgb(255, 255, 255)
- 🇧🇯 Benin: rgb(0, 136, 86), rgb(252, 209, 22), rgb(227, 28, 35)
- 🇯🇵 Japan: rgb(255, 255, 255), rgb(188, 0, 45)
- 🇵🇼 Palau: rgb(74, 172, 238), rgb(255, 222, 0)
- 🇨🇭 Schweiz: rgb(218, 41, 28), rgb(255, 255, 255)
- 🇸🇪 Schweden: rgb(0, 106, 167), rgb(254, 204, 0)

### Abmessungen der Elemente

- 🇹🇭 Die Streifen der Nationalflagge von Thailand stehen in dem Verhältnis 1:1:2:1:1.
- 🇧🇯 Der grüne vertikale Streifen in der Flagge von Benin nimmt 40 % der Breite der Flagge ein.
- 🇯🇵 Der Durchmesser des Kreises in der japanischen Flagge beträgt 60 % der Höhe der Flagge. Der Kreis ist zentriert.
- 🇵🇼 Der Durchmesser des Kreises in der Flagge von Palau beträgt 60 % der Höhe der Flagge. Der Mittelpunkt des Kreises liegt bei 3/8 (37,5%) der Flaggenbreite und 1/2 der Flaggenhöhe.
- 🇨🇭 Für das Seitenverhältnis der weißen Balken des Kreuzes der schweizer Flagge kann 6:20 angenommen werden. Die Höhe des Kreuzes der schweizer Flagge entspricht 5/8 der Höhe der Flagge.
- 🇸🇪 Die Mitte des senkrechten Balkens in der schwedischen Flagge liegt bei 37.5% der Flaggenbreite.
- 🇸🇪 Für die Breite der beiden Balken in der schwedischen Flagge können 20% der Höhe der Flagge bzw. 1/8 der Länge der Flagge angenommen werden.

### Erlaubte CSS-Eigenschaften

- display
- grid-template, grid-template-rows, grid-template-columns, gird-template-areas
- grid-column-start, grid-column-end, grid-column
- grid-row-start, grid-row-end, grid-row
- grid-area, place-items
- width, height, aspect-ratio
- background-color
- border-radius
- calc()
