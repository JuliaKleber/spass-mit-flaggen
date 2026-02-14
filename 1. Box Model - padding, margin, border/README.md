# Spaß mit Flaggen - Aufgabe 1 (CSS Box Model - padding, margin, border)

## Ziel

In dieser Aufgabe soll es darum gehen das CSS-Box-Model inklusive padding, border und margin zu verstehen. Hinweis: Für diese Aufgabe wurde die box-sizing Eigenschaft auf border-box gewählt.

## Aufgabenstellung

Erstelle die folgenden Nationalflaggen mit reinem HTML und CSS:

- 🇦🇹 Österreich
- 🇱🇻 Lettland
- 🇳🇬 Nigeria
- 🇮🇩 Indonesien
- 🇯🇵 Japan
- 🇵🇼 Palau
- 🇹🇭 Thailand

## Anforderungen

- Es soll konsequent das Box-Model mit padding, margin und oder border zur Erstellung der Flaggen genutzt werden. Position, Flex-Box, Grid, Gradienten usw. sind nicht erlaubt.
- Die HTML-Datei soll nicht verändert werden. Nur das Stylesheet (styles.css) soll vervollständigt werden.
- Für die Grundmaße und Farben der Flaggen sollen CSS-Variablen genutzt werden.
- Es soll CSS-Nesting genutzt werden.
- Es sollen keine Libraries oder Frameworks genutzt werden.

## Ressourcen

- <a href="https://www.w3schools.com/css/css_boxmodel.asp">CSS Box Model | w3schools</a>
- <a href="https://kulturbanause.de/blog/mit-box-sizing-border-box-das-css-box-model-verandern/">box-sizing | kulturbanause</a>
- <a href="https://www.mediaevent.de/css/nesting.html">CSS Nesting | mediaevent</a>
- <a href="https://www.mediaevent.de/css/variable.html">CSS-Variablen | mediaevent</a>
- <a href="https://kulturbanause.de/blog/berechnungen-mit-css-calc/">Berechnungen in CSS | kulturbanause</a>

## Hinweise

### Seitenverhältnisse der Flaggen

- 🇦🇹 Österreich: 3:2
- 🇱🇻 Lettland: 2:1
- 🇳🇬 Nigeria: 2:1
- 🇮🇩 Indonesien: 3:2
- 🇯🇵 Japan: 3:2
- 🇵🇼 Palau: 8:5
- 🇹🇭 Thailand 3:2

### Farben der Flaggen

Die folgenden Farben können für die Erstellung der Flaggen genutzt werden:

- 🇦🇹 Österreich: rgb(237, 41, 57), rgb(255, 255, 255)
- 🇱🇻 Lettland: rgb(158, 27, 50), rgb(255, 255, 255)
- 🇳🇬 Nigeria: rgb(0, 135, 81), rgb(255, 255, 255)
- 🇮🇩 Indonesien: rgb(255, 0, 0), rgb(255, 255, 255)
- 🇯🇵 Japan: rgb(255, 255, 255), rgb(188, 0, 45)
- 🇵🇼 Palau: rgb(74, 173, 214), rgb(255, 222, 0)
- 🇹🇭 Thailand: rgb(165, 25, 49), rgb(45, 42, 74), rgb(244, 245, 248)

### Abmessungen der Elemente

- 🇱🇻 Das Höhenverhältnis der Streifen in der lettischen Flagge ist 2:1:2.
- 🇯🇵 Der Durchmesser des Kreises in der japanischen Flagge beträgt 60 % der Höhe der Flagge. Der Kreis ist zentriert.
- 🇵🇼 Der Durchmesser des Kreises in der Flagge von Palau beträgt 60 % der Höhe der Flagge. Der Mittelpunkt des Kreises liegt bei 3/8 der Flaggenbreite und 1/2 der Flaggenhöhe.
- 🇹🇭 Die Streifen der Nationalflagge von Thailand stehen in dem Verhältnis 1:1:2:1:1.

### Erlaubte CSS-Eigenschaften

- box-sizing
- margin, border, padding
- width, height
- background-color
- border-radius
- calc()

### Tipps

Achtung Spoiler!!!

- 🇦🇹 Österreich: Darstellung der roten Streifen über die CSS-Eigenschaft border
- 🇱🇻 Lettland: Darstellung der roten Streifen über die CSS-Eigenschaft border
- 🇳🇬 Nigeria: Darstellung der grünen Streifen über die CSS-Eigenschaft border
- 🇮🇩 Indonesien: Darstellung des roten Streifens über die CSS-Eigenschaft border
- 🇯🇵 Japan: Der rote Kreis sollte jeweils eine Höhe und Breite von 100% bekommen und die Flagge sollte ein entsprechendes Padding bekommen um den Kreis die korrekte Größe zu geben und ihn zu positionieren.
- 🇵🇼 Palau: Der blaue Kreis sollte jeweils eine Höhe und Breite von 100% bekommen und die Flagge sollte ein entsprechendes Padding bekommen um den Kreis die korrekte Größe zu geben und ihn zu positionieren.
- 🇹🇭 Die roten Streifen können über die CSS-Eigenschaft Border erstellt werden. Der blaue Streifen bekommt ein margin um ihn zu positionieren.
