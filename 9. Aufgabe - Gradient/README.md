# Spaß mit Flaggen - Aufgabe 9 (CSS Gradienten)

## Ziel

Ziel der Aufgabe ist es Flaggen mit Gradienten zu erstellen.

## Aufgabenstellung

Erstelle die folgenden Nationalflaggen mit reinem HTML und CSS:

- 🇳🇱 Niederlande ⭐
- 🇮🇹 Italien ⭐
- 🇲🇺 Mauritius ⭐
- 🇹🇭 Thailand ⭐
- 🇯🇵 Japan ⭐⭐
- 🇵🇼 Palau ⭐⭐
- 🇧🇯 Benin ⭐⭐
- 🇸🇪 Schweden ⭐⭐
- 🇨🇭 Schweiz ⭐⭐⭐
- 🇨🇿 Tschechische Republik ⭐⭐⭐
- 🇧🇸 Bahamas ⭐⭐⭐
- 🇹🇹 Trinidad und Tobago ⭐⭐⭐
- 🏴󠁧󠁢󠁳󠁣󠁴󠁿 Schottland ⭐⭐⭐
- 🇯🇲 Jamaika ⭐⭐⭐
- 🇸🇨 Seychellen ⭐⭐⭐⭐
- 🇲🇰 Nordmazedonien ⭐⭐⭐⭐⭐

Die Sterne symbolisieren den Schwierigkeitsgrad.

## Anforderungen

- Es sollen ausschließlich Gradienten (linear-gradient, radial-gradient, conic-gradient) zur Erstellung der Flaggen genutzt werden. Die css-Eigenschaft background-color ist jedoch auch erlaubt. Siehe auch Abschnitt 'Erlaubte CSS-Eigenschaften'.
- Pro Flagge sollte nur ein einziges HTML-Element genutzt werden. Alle Streifen, Kreise, usw. müssen über dieses Element ohne Benutzung von Pseudoelemente erzeugt werden.
- Für die Grundmaße und Farben der Flaggen sollen CSS-Variablen genutzt werden.
- Es sollen keine Libraries oder Frameworks genutzt werden.

## Ressourcen

- <a href="https://www.w3schools.com/css/css3_gradients.asp">Gradienten | w3schools</a>
- <a href="https://www.w3schools.com/cssref/func_radial-gradient.php">radial-gradient() | w3schools</a>
- <a href="https://www.w3schools.com/cssref/func_conic-gradient.php">conic-gradient() | w3schools</a>
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
- 🇸🇪 Schweden 16:10
- 🇨🇭 Schweiz 1:1
- 🇨🇿 Tschechische Republik 3:2
- 🇧🇸 Bahamas 2:1
- 🇹🇹 Trinidad und Tobago 5:3
- 🏴󠁧󠁢󠁳󠁣󠁴󠁿 Schottland 3:2
- 🇯🇲 Jamaika 2:1
- 🇸🇨 Seychellen 2:1
- 🇲🇰 Nordmazedonien 2:1

## Farben der Flaggen

Die folgenden Farben können für die Erstellung der Flaggen genutzt werden:

- 🇳🇱 Niederlande: rgb(174, 28, 40), rgb(255, 255, 255), rgb(33, 70, 139)
- 🇮🇹 Italien: rgb(0, 140, 69), rgb(244, 245, 240), rgb(205, 33, 42)
- 🇲🇺 Mauritius: rgb(208, 28, 31), rgb(45, 51, 89), rgb(247, 183, 24), rgb(0, 134, 88)
- 🇹🇭 Thailand: rgb(165, 25, 49), rgb(45, 42, 74), rgb(255, 255, 255)
- 🇯🇵 Japan: rgb(255, 255, 255), rgb(188, 0, 45)
- 🇵🇼 Palau: rgb(74, 172, 238), rgb(255, 222, 0)
- 🇧🇯 Benin: rgb(0, 136, 86), rgb(252, 209, 22), rgb(227, 28, 35)
- 🇸🇪 Schweden: rgb(0, 106, 167), rgb(254, 204, 0)
- 🇨🇭 Schweiz: rgb(218, 41, 28), rgb(255, 255, 255)
- 🇨🇿 Tschechische Republik: rgb(255, 255, 255), rgb(215, 20, 26), rgb(17,49,126)
- 🇧🇸 Bahamas: rgb(0, 169, 206), rgb(255, 199, 44), rgb(0, 0, 0),
- 🇹🇹 Trinidad und Tabago: rgb(200, 16, 46), rgb(255, 255, 255), rgb(0, 0, 0);
- 🏴󠁧󠁢󠁳󠁣󠁴󠁿 Schottland: rgb(0, 94, 184), rgb(255, 255, 255)
- 🇯🇲 Jamaika: rgb(0, 155, 58), rgb(254, 209, 0), rgb(0, 0, 0)
- 🇸🇨 Seychellen: rgb(0, 63, 135), rgb(252, 209, 22), rgb(212, 28, 48), rgb(255, 255, 255), rgb(0, 122, 61)
- 🇲🇰 Nordmazedonien: rgb(210, 0, 0), rgb(255, 230, 0)

### Abmessungen der Elemente

- 🇹🇭 Die Streifen der Nationalflagge von Thailand stehen in dem Verhältnis 1:1:2:1:1.
- 🇯🇵 Der Durchmesser des Kreises in der japanischen Flagge beträgt 60 % der Höhe der Flagge. Der Kreis ist zentriert.
- 🇵🇼 Der Durchmesser des Kreises in der Flagge von Palau beträgt 60 % der Höhe der Flagge. Der Mittelpunkt des Kreises liegt bei 3/8 (37,5%) der Flaggenbreite und 1/2 der Flaggenhöhe.
- 🇧🇯 Der grüne vertikale Streifen in der Flagge von Benin nimmt 40 % der Breite der Flagge ein.
- 🇸🇪 Die Mitte des senkrechten Balkens in der schwedischen Flagge liegt bei 37,5% (3/8) der Flaggenbreite. Für die Breite der beiden Balken in der schwedischen Flagge können 20% der Höhe der Flagge bzw. 1/8 der Länge der Flagge angenommen werden. Das bedeutet, dass der Querbalken der Flagge sich von 5/16 bis 7/16 der Breite der Flagge erstreckt.
- 🇨🇭 Für das Seitenverhältnis der weißen Balken des Kreuzes der schweizer Flagge kann 6:20 angenommen werden. Die Höhe des Kreuzes der schweizer Flagge entspricht 5/8 der Höhe der Flagge.
- 🇨🇿 Das Dreieck in der tschechischen Flagge ist so breit wie die Hälfte der Länge der Flagge. Als Winkel für den konischen Gradienten können 236° und 304° angenommen werden.
- 🇧🇸 Die Spitze des Dreiecks der Flagge der Bahamas liegt bei der Länge der Flagge geteilt durch 2,2. Das heißt, die Spitze des Dreiecks liegt bei 45,45%. Als Winkel für den konischen Gradienten können 241° und 299° Grad angenommen werden.
- 🇹🇹 Die Streifen in der Flagge von Trinidad und Tobago sind um 41 Grad gedreht. Die Breite des weißen Streifens entspricht 17% des Gradienten und die Breite des schwarzen Streifens entspricht ca. 12% des Gradienten.
- 🏴󠁧󠁢󠁳󠁣󠁴󠁿 Für die Breite der Balken der schottischen Flagge kann 12% des Gradienten angenommen werden. Sie sind um 33.7 Grad zur Waagerechten gedreht.
- 🇯🇲 Für den Winkel der Balken des Andreaskreuzes der jamaikanischen Flagge zur Horizontalen kann 26.6° angenommen werden. Für die Breite der Balken kann 10% des Gradienten angenommen werden.
- 🇸🇨 Alle fünf Farbflächen der Flagge von Seychellen sind Polygone, die in der linken unteren Ecke ihren gemeinsamen Ursprung haben. Für die Winkel der Segmente der Flagge von Seychellen können 33,7°, 53,1°, 71,6° und 80,5° angenommen werden.

## Erlaubte CSS-Eigenschaften

- width, height
- background-color
- background-image
- background-size
- background-repeat
- background-position
- calc()
