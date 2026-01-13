# Spaß mit Flaggen - Aufgabe 11 (clip-path)

## Ziel

Ziel der Aufgabe ist es Flaggen mit clip-path zu erstellen.

## Aufgabenstellung

Erstelle die folgenden Nationalflaggen mit reinem HTML und CSS:

- 🇳🇱 Niederlande
- 🇮🇹 Italien
- 🇲🇺 Mauritius
- 🇧🇯 Benin
- 🇸🇪 Schweden
- 🇨🇭 Schweiz
- 🇸🇨 Seychellen
- 🇯🇵 Japan
- 🇵🇼 Palau
- 🇨🇿 Tschechische Republik
- 🇧🇸 Bahamas
- 🇯🇲 Jamaika

## Anforderungen

- Die Elemente der Flaggen sollen mit clip-path erstellt werden. Gradienten sind nicht erlaubt.
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
- 🇧🇯 Benin 3:2
- 🇸🇪 Schweden 16:10
- 🇨🇭 Schweiz 1:1
- 🇸🇨 Seychellen 2:1
- 🇯🇵 Japan 3:2
- 🇵🇼 Palau: 8:5
- 🇨🇿 Tschechische Republik 3:2
- 🇧🇸 Bahamas 2:1
- 🇯🇲 Jamaika 2:1

## Farben der Flaggen

Die folgenden Farben können für die Erstellung der Flaggen genutzt werden:

- 🇳🇱 Niederlande: rgb(174, 28, 40), rgb(255, 255, 255), rgb(33, 70, 139)
- 🇮🇹 Italien: rgb(0, 140, 69), rgb(244, 245, 240), rgb(205, 33, 42)
- 🇲🇺 Mauritius: rgb(208, 28, 31), rgb(45, 51, 89), rgb(247, 183, 24), rgb(0, 134, 88)
- 🇧🇯 Benin: rgb(0, 136, 86), rgb(252, 209, 22), rgb(227, 28, 35)
- 🇸🇪 Schweden: rgb(0, 106, 167), rgb(254, 204, 0)
- 🇨🇭 Schweiz: rgb(218, 41, 28), rgb(255, 255, 255)
- 🇸🇨 Seychellen: rgb(0, 63, 135), rgb(252, 209, 22), rgb(212, 28, 48), rgb(255, 255, 255), rgb(0, 122, 61)
- 🇯🇵 Japan: rgb(255, 255, 255), rgb(188, 0, 45)
- 🇵🇼 Palau: rgb(74, 172, 238), rgb(188, 0, 45)
- 🇨🇿 Tschechische Republik: rgb(255, 255, 255), rgb(215, 20, 26), rgb(17,49,126)
- 🇧🇸 Bahamas: rgb(0, 169, 206), rgb(255, 199, 44), rgb(0, 0, 0),
- 🇯🇲 Jamaika: rgb(0, 155, 58), rgb(254, 209, 0), rgb(0, 0, 0)

### Abmessungen der Elemente

- 🇧🇯 Der grüne vertikale Streifen in der Flagge von Benin nimmt 40 % der Breite der Flagge ein.
- 🇸🇪 Die Mitte des senkrechten Balkens in der schwedischen Flagge liegt bei 37,5% (3/8) der Flaggenbreite. Für die Breite der beiden Balken in der schwedischen Flagge können 20% der Höhe der Flagge bzw. 1/8 der Länge der Flagge angenommen werden. Das bedeutet, dass der Querbalken der Flagge sich von 5/16 bis 7/16 der Breite der Flagge erstreckt.
- 🇨🇭 Für das Seitenverhältnis der weißen Balken des Kreuzes der schweizer Flagge kann 6:20 angenommen werden. Die Höhe des Kreuzes der schweizer Flagge entspricht 5/8 der Höhe der Flagge.
- 🇯🇵 Der Durchmesser des Kreises in der japanischen Flagge beträgt 60 % der Höhe der Flagge. Der Kreis ist zentriert.
- 🇵🇼 Der Durchmesser des Kreises in der Flagge von Palau beträgt 60 % der Höhe der Flagge. Der Mittelpunkt des Kreises liegt bei 3/8 (37,5%) der Flaggenbreite und 1/2 der Flaggenhöhe.
- 🇨🇿 Das Dreieck in der tschechischen Flagge ist so breit wie die Hälfte der Länge der Flagge.
- 🇧🇸 Das Dreieck der Flagge der Bahamas ist so breit wie die Länge der Flagge geteilt durch 2,2. Das entspricht 45,45%.
- 🇯🇲 Die schwarzen Dreiecke der jamaikanischen Flagge gehen von 10% der Flaggenhöhe bis 90% der Flaggenhöhe und 40% bzw. 60% der Flaggenbreite. Die grünen Dreiecke der der jamaikanischen Flagge gehen von 10% der Flaggenbreite bis 90% der Flaggenbreite und 40% bzw. 60% der Flaggenhöhe.

## Benötigte CSS-Eigenschaften

- background-color
- height, width
- clip-path
- position
- content
- calc()
