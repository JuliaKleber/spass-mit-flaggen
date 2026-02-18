# clip-path

## Ziel

Ziel der Aufgabe ist es Flaggen mit clip-path zu erstellen.

## Aufgabenstellung

Erstelle die folgenden Nationalflaggen mit reinem HTML und CSS:

- 🇳🇱 Niederlande
- 🇮🇹 Italien
- 🇲🇺 Mauritius
- 🇹🇭 Thailand
- 🇧🇯 Benin
- 🇸🇪 Schweden
- 🇨🇭 Schweiz
- 🇸🇨 Seychellen
- 🇯🇵 Japan
- 🇵🇼 Palau
- 🇨🇿 Tschechische Republik
- 🇧🇸 Bahamas
- 🏴󠁧󠁢󠁳󠁣󠁴󠁿 Schottland
- 🇹🇹 Trinidad und Tobago
- 🇯🇲 Jamaika

## Anforderungen

- Die Elemente der Flaggen sollen mit clip-path erstellt werden. Gradienten sind nicht erlaubt.
- Die html-Datei soll nicht verändert werden. Nur das Stylesheet (styles.css) soll vervollständigt werden.
- Für die Grundmaße und Farben der Flaggen sollen CSS-Variablen genutzt werden.
- Es soll CSS-Nesting genutzt werden.
- Die html-Datei soll nicht verändert werden. Die Aufgabe soll durch vervollständigen der css-Datei gelöst werden. Es dürfen die Pseudeelemente ::before und ::after verwendet werden.
- Es sollen keine Libraries oder Frameworks genutzt werden.

## Ressourcen

- <a href="https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/clip-path">clip-path | MDN</a>
- <a href="https://css-tricks.com/almanac/properties/c/clip-path/">clip-path | CSS Tricks</a>
- <a href="https://kulturbanause.de/blog/generierter-css-content-mit-before-und-after/">::before & ::after | kulturbanause</a>
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
- 🇸🇪 Schweden 16:10
- 🇨🇭 Schweiz 1:1
- 🇸🇨 Seychellen 2:1
- 🇯🇵 Japan 3:2
- 🇵🇼 Palau: 8:5
- 🇨🇿 Tschechische Republik 3:2
- 🇧🇸 Bahamas 2:1
- 🏴󠁧󠁢󠁳󠁣󠁴󠁿 Schottland 5:2
- 🇹🇹 Trinidad und Tobago 5:3
- 🇯🇲 Jamaika 2:1

## Farben der Flaggen

Die folgenden Farben können für die Erstellung der Flaggen genutzt werden:

- 🇳🇱 Niederlande: rgb(173, 29, 37), rgb(255, 255, 255), rgb(30, 71, 133)
- 🇮🇹 Italien: rgb(0, 140, 69), rgb(244, 245, 240), rgb(205, 33, 42)
- 🇲🇺 Mauritius: rgb(208, 28, 31), rgb(45, 51, 89), rgb(247, 183, 24), rgb(0, 134, 88)
- 🇹🇭 Thailand: rgb(165, 25, 49), rgb(45, 42, 74), rgb(244, 245, 248)
- 🇧🇯 Benin: rgb(0, 136, 80), rgb(252, 210, 15), rgb(233, 9, 41)
- 🇸🇪 Schweden: rgb(0, 91, 174), rgb(255, 195, 1)
- 🇨🇭 Schweiz: rgb(255, 0, 0), rgb(255, 255, 255)
- 🇸🇨 Seychellen: rgb(0, 61, 136), rgb(252, 217, 85), rgb(215, 35, 35), rgb(255, 255, 255), rgb(0, 123, 58)
- 🇯🇵 Japan: rgb(255, 255, 255), rgb(188, 0, 45)
- 🇵🇼 Palau: rgb(74, 172, 238), rgb(188, 0, 45)
- 🇨🇿 Tschechische Republik: rgb(255, 255, 255), rgb(215, 20, 26), rgb(17,49,126)
- 🇧🇸 Bahamas: rgb(0, 169, 206), rgb(255, 199, 44), rgb(0, 0, 0),
- 🏴󠁧󠁢󠁳󠁣󠁴󠁿 Schottland: rgb(0, 94, 184), rgb(255, 255, 255)
- 🇹🇹 Trinidad und Tabago: rgb(218, 26, 53), rgb(255, 255, 255), rgb(0, 0, 0)
- 🇯🇲 Jamaika: rgb(25, 151, 93), rgb(255, 199, 0), rgb(45, 41, 38)

### Abmessungen der Elemente

- 🇹🇭 Die Streifen der Nationalflagge von Thailand stehen in dem Verhältnis 1:1:2:1:1.
- 🇧🇯 Der grüne vertikale Streifen in der Flagge von Benin nimmt 40 % der Breite der Flagge ein.
- 🇸🇪 Schweden: Die Mitte des senkrechten Balkens in der schwedischen Flagge liegt bei 37,5% bzw. 3/8 der Flaggenbreite. Die Breite der beiden Balken der schwedischen Flagge entspricht 20% der Höhe der Flagge bzw. 1/8 der Länge der Flagge. Der Querbalken der Flagge erstreckt sich von 5/16 bis 7/16 der Breite der Flagge.
- 🇨🇭 Für das Seitenverhältnis der weißen Balken des Kreuzes der schweizer Flagge kann 6:20 angenommen werden. Die Höhe des Kreuzes der schweizer Flagge entspricht 5/8 der Höhe der Flagge.
- 🇸🇨 Alle fünf Farbflächen der Flagge von Seychellen sind Polygone, die in der linken unteren Ecke ihren gemeinsamen Ursprung haben. Die Eckpunkte der Polygone liegen jeweils bei 1/3 bzw. 2/3 der Flaggenbreite und Flaggenhöhe.
- 🇯🇵 Der Durchmesser des Kreises in der japanischen Flagge beträgt 60 % der Höhe der Flagge. Der Kreis ist zentriert.
- 🇵🇼 Der Durchmesser des Kreises in der Flagge von Palau beträgt 60 % der Höhe der Flagge. Der Mittelpunkt des Kreises liegt bei 3/8 (37,5%) der Flaggenbreite und 1/2 der Flaggenhöhe.
- 🇨🇿 Das Dreieck in der tschechischen Flagge ist so breit wie die Hälfte der Länge der Flagge.
- 🇧🇸 Das Dreieck der Flagge der Bahamas ist so breit wie die Länge der Flagge geteilt durch 2,2. Das entspricht 45,45%.
- 🏴󠁧󠁢󠁳󠁣󠁴󠁿 Die linken und rechten Dreiecke der schottischen Flagge gehen von 10% der Flaggenhöhe bis 90% der Flaggenhöhe und 40% bzw. 60% der Flaggenbreite. Die oberen und unteren Dreiecke der der gehen von 10% der Flaggenbreite bis 90% der Flaggenbreite und 40% bzw. 60% der Flaggenhöhe.
- 🇹🇹 Der weiße Streifen in der Flagge von Trinidad und Tobago geht von der linken oberen Ecke zu 30% der oberen Flaggenseite, zur rechten unteren Ecke und 70% der unteren Flaggenbreite. Der schwarze Streifen hat 2/3 der Breite des weißen Streifens.
- 🇯🇲 Die schwarzen Dreiecke der jamaikanischen Flagge gehen von 10% der Flaggenhöhe bis 90% der Flaggenhöhe und 40% bzw. 60% der Flaggenbreite. Die grünen Dreiecke der der jamaikanischen Flagge gehen von 10% der Flaggenbreite bis 90% der Flaggenbreite und 40% bzw. 60% der Flaggenhöhe.

## Benötigte CSS-Eigenschaften

- background-color
- height, width
- clip-path
- position
- content
- calc()
