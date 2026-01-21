# Spaß mit Flaggen - Aufgabe 5 (Position)

## Ziel

Ziel der Aufgabe ist es Elemente mit Position zu positionieren.

## Aufgabenstellung

Erstelle die folgenden Nationalflaggen mit reinem HTML und CSS:

- 🇳🇱 Niederlande
- 🇮🇹 Italien
- 🇲🇺 Mauritius
- 🇹🇭 Thailand
- 🇯🇵 Japan
- 🇵🇼 Palau
- 🇧🇯 Benin
- 🇨🇭 Schweiz
- 🇸🇪 Schweden
- 🏴󠁧󠁢󠁳󠁣󠁴󠁿 Schottland
- 🇹🇹 Trinidad und Tobago
- 🇬🇧 Großbritannien

## Anforderungen

- Es sollte konsequent position: absolute für die Anordnung der Elemente genutzt werden.
- Es sollte weder Flexbox noch Grid noch Gradienten noch Paddings, Margins oder Borders zur Erstellung der Flaggen genutzt werden.
- Die html-Datei soll nicht verändert werden. Nur das Stylesheet (styles.css) soll vervollständigt werden.
- Für die Grundmaße und Farben der Flaggen sollen CSS-Variablen genutzt werden.
- Es solle CSS-Nesting genutzt werden.
- Es sollen keine Libraries oder Frameworks genutzt werden.

## Ressourcen

- <a href="https://www.w3schools.com/css/css_positioning.asp">Position | w3schools</a>
- <a href="https://www.w3schools.com/cssref/css_pr_translate.php">translate | w3schools</a>
- <a href="https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Values/transform-function/translate">translate | MDN</a>
- <a href="https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Values/transform-function/rotate">rotate | MDN</a>
- <a href="https://www.mediaevent.de/css/visualeffects-overflow.html">overflow | mediaevent</a>
- <a href="https://www.mediaevent.de/css/nesting.html">CSS Nesting | mediaevent</a>
- <a href="https://www.mediaevent.de/css/variable.html">CSS-Variablen | mediaevent</a>
- <a href="https://kulturbanause.de/blog/berechnungen-mit-css-calc/">Berechnungen in CSS | kulturbanause</a>

## Hinweise

### Seitenverhältnisse der Flaggen

- 🇳🇱 Niederlande 3:2
- 🇮🇹 Italien 3:2
- 🇲🇺 Mauritius 3:2
- 🇹🇭 Thailand 3:2
- 🇯🇵 Japan 3:2
- 🇵🇼 Palau: 8:5
- 🇧🇯 Benin 3:2
- 🇨🇭 Schweiz 1:1
- 🇸🇪 Schweden 16:10
- 🏴󠁧󠁢󠁳󠁣󠁴󠁿 Schottland 5:2
- 🇹🇹 Trinidad und Tobago 5:3
- 🇬🇧 Großbritannien 5:3

## Farben der Flaggen

Die folgenden Farben können für die Erstellung der Flaggen genutzt werden:

- 🇳🇱 Niederlande: rgb(173, 29, 37), rgb(255, 255, 255), rgb(30, 71, 133)
- 🇮🇹 Italien: rgb(0, 140, 69), rgb(244, 245, 240), rgb(205, 33, 42)
- 🇲🇺 Mauritius: rgb(208, 28, 31), rgb(45, 51, 89), rgb(247, 183, 24), rgb(0, 134, 88)
- 🇹🇭 Thailand: rgb(165, 25, 49), rgb(45, 42, 74), rgb(244, 245, 248)
- 🇯🇵 Japan: rgb(255, 255, 255), rgb(188, 0, 45)
- 🇵🇼 Palau: rgb(74, 173, 214), rgb(255, 222, 0)
- 🇧🇯 Benin: rgb(0, 136, 80), rgb(252, 210, 15), rgb(233, 9, 41)
- 🇨🇭 Schweiz: rgb(255, 0, 0), rgb(255, 255, 255)
- 🇸🇪 Schweden: rgb(0, 91, 174), rgb(255, 195, 1)
- 🏴󠁧󠁢󠁳󠁣󠁴󠁿 Schottland: rgb(0, 94, 184), rgb(255, 255, 255)
- 🇹🇹 Trinidad und Tabago: rgb(218, 26, 53), rgb(255, 255, 255), rgb(0, 0, 0)
- 🇬🇧 Großbritannien: rgb(255, 255, 255), rgb(0, 36, 125), rgb(207, 20, 43)

### Abmessungen der Elemente

- 🇹🇭 Die Streifen der Nationalflagge von Thailand stehen in dem Verhältnis 1:1:2:1:1.
- 🇯🇵 Der Durchmesser des Kreises in der japanischen Flagge beträgt 60 % der Höhe der Flagge. Der Kreis ist zentriert.
- 🇵🇼 Der Durchmesser des Kreises in der Flagge von Palau beträgt 60 % der Höhe der Flagge. Der Mittelpunkt des Kreises liegt bei 3/8 (37,5%) der Flaggenbreite und 1/2 der Flaggenhöhe.
- 🇧🇯 Der grüne vertikale Streifen in der Flagge von Benin nimmt 40 % der Breite der Flagge ein.
- 🇨🇭 Für das Seitenverhältnis der weißen Balken des Kreuzes der schweizer Flagge kann 6:20 angenommen werden. Die Höhe des Kreuzes der schweizer Flagge entspricht 5/8 der Höhe der Flagge.
- 🇸🇪 Schweden: Die Mitte des senkrechten Balkens in der schwedischen Flagge liegt bei 37,5% bzw. 3/8 der Flaggenbreite. Die Breite der beiden Balken der schwedischen Flagge entspricht 20% der Höhe der Flagge bzw. 1/8 der Länge der Flagge. Der Querbalken der Flagge erstreckt sich von 5/16 bis 7/16 der Breite der Flagge.
- 🏴󠁧󠁢󠁳󠁣󠁴󠁿 Schottland: Die Höhe der Balken entspricht 1/5 der Höhe der Flagge. Der Winkel zur Horizontalen beträgt ca. 30.9°.
- 🇹🇹 Trinidad und Tobago: Die Höhe des weißen Balkens entspricht 1/3 der Höhe der Flagge. Die Höhe des schwarzen Balkens entspricht 2/9 der Höhe der Flagge. Der Winkel zur Horizontalen beträgt ca. 40.8°.

## Erlaubte CSS-Eigenschaften

- width, height
- background-color
- position
- top, bottom, right, left
- translate
- rotate
- border-radius
- overflow
- calc()
