# Spaß mit Flaggen - Aufgabe 5 (Position)

## Ziel

Ziel der Aufgabe ist es Elemente mit Position zu positionieren.

## Aufgabenstellung

Erstelle die folgenden Nationalflaggen mit reinem HTML und CSS:

- 🇳🇱 Niederlande
- 🇮🇹 Italien
- 🇲🇺 Mauritius
- 🇯🇵 Japan
- 🇧🇯 Benin
- 🇨🇭 Schweiz
- 🇸🇪 Schweden

## Anforderungen

- Es sollte konsequent position: absolute für die Anordnung der Elemente genutzt werden.
- Es sollte weder Flexbox noch Grid noch Gradienten noch Paddings, Margins oder Borders zur Erstellung der Flaggen genutzt werden.
- Für die Grundmaße und Farben der Flaggen sollten CSS-Variablen genutzt werden.
- Es sollte CSS-Nesting genutzt werden.
- Es sollten keine Libraries oder Frameworks genutzt werden.

## Ressourcen

- <a href="https://www.w3schools.com/css/css_positioning.asp">Position | w3schools</a>
- <a href="https://www.w3schools.com/cssref/css_pr_translate.php">translate | w3schools</a>
- <a href="https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Values/transform-function/translate">translate | MDN</a>
- <a href="https://www.mediaevent.de/css/nesting.html">CSS Nesting | mediaevent</a>
- <a href="https://www.mediaevent.de/css/variable.html">CSS-Variablen | mediaevent</a>
- <a href="https://kulturbanause.de/blog/berechnungen-mit-css-calc/">Berechnungen in CSS | kulturbanause</a>

## Hinweise

### Seitenverhältnisse der Flaggen

- 🇳🇱 Niederlande 3:2
- 🇮🇹 Italien 3:2
- 🇲🇺 Mauritius 3:2
- 🇯🇵 Japan 3:2
- 🇧🇯 Benin 3:2
- 🇨🇭 Schweiz 1:1
- 🇸🇪 Schweden 16:10

## Farben der Flaggen

Die folgenden Farben können für die Erstellung der Flaggen genutzt werden:

- 🇳🇱 Niederlande: rgb(174, 28, 40), rgb(255, 255, 255), rgb(33, 70, 139)
- 🇮🇹 Italien: rgb(0, 140, 69), rgb(244, 245, 240), rgb(205, 33, 42)
- 🇲🇺 Mauritius: rgb(208, 28, 31), rgb(45, 51, 89), rgb(247, 183, 24), rgb(0, 134, 88)
- 🇯🇵 Japan: rgb(255, 255, 255), rgb(188, 0, 45)
- 🇧🇯 Benin: rgb(0, 136, 86), rgb(252, 209, 22), rgb(227, 28, 35)
- 🇨🇭 Schweiz: rgb(218, 41, 28), rgb(255, 255, 255)
- 🇸🇪 Schweden: rgb(0, 106, 167), rgb(254, 204, 0)

### Abmessungen der Elemente

- 🇯🇵 Der Durchmesser des Kreises in der japanischen Flagge beträgt 60 % der Höhe der Flagge. Der Kreis ist zentriert.
- 🇧🇯 Der grüne vertikale Streifen in der Flagge von Benin nimmt 40 % der Breite der Flagge ein.
- 🇨🇭 Für das Seitenverhältnis der weißen Balken des Kreuzes der schweizer Flagge kann 6:20 angenommen werden. Die Höhe des Kreuzes der schweizer Flagge entspricht 5/8 der Höhe der Flagge.
- 🇸🇪 Die Mitte des senkrechten Balkens in der schwedischen Flagge liegt bei 37,5% (3/8) der Flaggenbreite. Für die Breite der beiden Balken in der schwedischen Flagge können 20% der Höhe der Flagge bzw. 1/8 der Länge der Flagge angenommen werden. Das bedeutet, dass der Querbalken der Flagge sich von 5/16 bis 7/16 der Breite der Flagge erstreckt.

## Erlaubte CSS-Eigenschaften

- width, height
- background-color
- position
- top, bottom, right, left
- translate
- border-radius
