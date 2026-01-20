# Spaß mit Flaggen - Aufgabe 11 (Verschiedenes)

# Ziel

In dieser Aufgabe können alle CSS-Eigenschaften genutzt werden. Ziel ist es das HTML minimal zu halten, idealerweise sollte nur ein div pro Flagge genutzt werden, und sich gleichzeitig für möglichst einfache, nachvollziehbare und korrekte CSS-Lösungen zu entscheiden.

## Aufgabenstellung

Erstelle die folgenden Nationalflaggen mit reinem HTML und CSS:

- 🇳🇱 Niederlande
- 🇮🇹 Italien
- 🇲🇺 Mauritius
- 🇹🇭 Thailand
- 🇧🇯 Benin
- 🇯🇵 Japan
- 🇵🇼 Palau
- 🇨🇿 Tschechische Republik
- 🇧🇸 Bahamas
- 🇸🇪 Schweden
- 🇬🇱 Grönland
- 🇸🇨 Seychellen
- 🇨🇭 Schweiz
- 🏴󠁧󠁢󠁳󠁣󠁴󠁿 Schottland
- 🇯🇲 Jamaika
- 🇹🇹 Trinidad und Tobago

## Anforderungen

- Mit der Ausnahme von Seychellen sollte nur ein HTML-Element pro Flagge genutzt werden.
- Um das HTML möglichst minimal zu halten, können die Pseudo-Elemente ::before und ::after genutzt werden.
- Für die Maße der Flaggen und die Farben sollen CSS-Variablen genutzt werden.
- Statt px oder em soll rem für die Flaggenhöhe und Prozentangaben, calc() oder aspect-ratio für alle anderen Abmessungen (Streifen, Kreise, usw.) genutzt werden.
- Es soll CSS-Nesting genutzt werden.
- Es dürfen keine Bilder, Icons oder SVGs genutzt werden.
- Es sollen keine Libraries oder Frameworks genutzt werden.

## Resourcen

- <a href="https://www.w3schools.com/cssref/css_units.php">CSS Units | w3schools</a>
- <a href="https://www.mediaevent.de/css/font-size-rem.html">CSS Units | mediaevent</a>
- <a href="https://kulturbanause.de/blog/generierter-css-content-mit-before-und-after/">::before & ::after | kulturbanause</a>
- <a href="https://www.mediaevent.de/css/nesting.html">CSS Nesting | mediaevent</a>
- <a href="https://www.mediaevent.de/css/variable.html">CSS-Variablen | mediaevent</a>
- <a href="https://kulturbanause.de/blog/berechnungen-mit-css-calc/">Berechnungen in CSS | kulturbanause</a>

## Hinweise

### Grundmaße der Flaggen

- 🇳🇱 Niederlande 3:2
- 🇮🇹 Italien 3:2
- 🇲🇺 Mauritius 3:2
- 🇹🇭 Thailand 3:2
- 🇧🇯 Benin 3:2
- 🇯🇵 Japan 3:2
- 🇵🇼 Palau: 8:5
- 🇨🇿 Tschechische Republik 3:2
- 🇧🇸 Bahamas 2:1
- 🇸🇪 Schweden 16:10
- 🇬🇱 Grönland 3:2
- 🇸🇨 Seychellen 2:1
- 🇨🇭 Schweiz 1:1
- 🏴󠁧󠁢󠁳󠁣󠁴󠁿 Schottland 5:2
- 🇯🇲 Jamaika 2:1
- 🇹🇹 Trinidad und Tobago 5:3

### Farben der Flaggen

Die folgenden Farben können für die Erstellung der Flaggen genutzt werden:

- 🇳🇱 Niederlande: rgb(173, 29, 37), rgb(255, 255, 255), rgb(30, 71, 133)
- 🇮🇹 Italien: rgb(0, 140, 69), rgb(244, 245, 240), rgb(205, 33, 42)
- 🇲🇺 Mauritius: rgb(208, 28, 31), rgb(45, 51, 89), rgb(247, 183, 24), rgb(0, 134, 88)
- 🇹🇭 Thailand: rgb(165, 25, 49), rgb(45, 42, 74), rgb(244, 245, 248)
- 🇧🇯 Benin: rgb(0, 136, 80), rgb(252, 210, 15), rgb(233, 9, 41)
- 🇯🇵 Japan: rgb(255, 255, 255), rgb(188, 0, 45)
- 🇵🇼 Palau: rgb(74, 173, 214), rgb(255, 222, 0)
- 🇨🇿 Tschechische Republik: rgb(255, 255, 255), rgb(215, 20, 26), rgb(17,49,126)
- 🇧🇸 Bahamas: rgb(0, 169, 206), rgb(255, 199, 44), rgb(0, 0, 0),
- 🇸🇪 Schweden: rgb(0, 91, 174), rgb(255, 195, 1)
- 🇬🇱 Grönland: rgb(239, 51, 64), rgb(255, 255, 255)
- 🇸🇨 Seychellen: rgb(0, 61, 136), rgb(252, 217, 85), rgb(215, 35, 35), rgb(255, 255, 255), rgb(0, 123, 58)
- 🇨🇭 Schweiz: rgb(255, 0, 0), rgb(255, 255, 255)
- 🏴󠁧󠁢󠁳󠁣󠁴󠁿 Schottland: rgb(0, 94, 184), rgb(255, 255, 255)
- 🇯🇲 Jamaika: rgb(25, 151, 93), rgb(255, 199, 0), rgb(45, 41, 38)
- 🇹🇹 Trinidad und Tabago: rgb(218, 26, 53), rgb(255, 255, 255), rgb(0, 0, 0)

### Geometrische Details

- 🇹🇭 Die Streifen der Nationalflagge von Thailand stehen in dem Verhältnis 1:1:2:1:1.
- 🇧🇯 Der grüne vertikale Streifen in der Flagge von Benin nimmt 40 % der Breite der Flagge ein.
- 🇯🇵 Der Durchmesser des Kreises in der japanischen Flagge beträgt 60 % der Höhe der Flagge. Der Kreis ist zentriert.
- 🇵🇼 Der Durchmesser des Kreises in der Flagge von Palau beträgt 60 % der Höhe der Flagge. Der Mittelpunkt des Kreises liegt bei 3/8 bzw. 37,5% der Flaggenbreite und 1/2 der Flaggenhöhe.
- 🇨🇿 Das Dreieck in der tschechischen Flagge ist so breit wie die Hälfte der Länge der Flagge.
- 🇧🇸 Die Spitze des Dreiecks der Flagge der Bahamas liegt bei der Länge der Flagge geteilt durch 2,2. Das heißt, die Spitze des Dreiecks liegt bei 45,45%.
- 🇸🇪 Schweden: Die Mitte des senkrechten Balkens in der schwedischen Flagge liegt bei 37,5% bzw. 3/8 der Flaggenbreite. Die Breite der beiden Balken der schwedischen Flagge entspricht 20% der Höhe der Flagge bzw. 1/8 der Länge der Flagge. Der Querbalken der Flagge erstreckt sich von 5/16 bis 7/16 der Breite der Flagge.
- 🇬🇱 Grönland: Der Durchmesser der Scheibe beträgt 2/3 der Flaggenhöhe und 4/9 der Flaggenbreite. Die Scheibe ist senkrecht zentriert. In horizontaler Richtung befindet sich der Mittelpunkt der Scheibe bei 7/18 von der Flaggenbreite.
- 🇸🇨 Alle fünf Farbflächen der Flagge von Seychellen sind Polygone, die in der linken unteren Ecke ihren gemeinsamen Ursprung haben.
- 🇨🇭 Für das Seitenverhältnis der beiden weißen Balken des Kreuzes der schweizer Flagge kann 6:20 angenommen werden. Die Höhe des Kreuzes der schweizer Flagge entspricht 5/8 der Höhe der Flagge.
- 🏴󠁧󠁢󠁳󠁣󠁴󠁿 Schottland: Die Höhe der Balken entspricht 1/5 der Höhe der Flagge. Der Winkel zur Horizontalen beträgt ca. 30.9°.
- 🇯🇲 Jamaika: Die Höhe der Balken entspricht 1/6 der Höhe der Flagge. Der Winkel zur Horizontalen beträgt ca. 26.5°.
- 🇹🇹 Trinidad und Tobago: Die Höhe des weißen Balkens entspricht 1/3 der Höhe der Flagge. Die Höhe des schwarzen Balkens entspricht 2/9 der Höhe der Flagge. Der Winkel zur Horizontalen beträgt ca. 40.8°.
