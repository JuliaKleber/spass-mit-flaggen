# Spaß mit Flaggen - Aufgabe 1 (CSS Box Model)

## Ziel

In dieser Aufgabe soll es darum gehen das CSS-Box-Model, box-sizing, padding, border und margin zu verstehen.

## Aufgabenstellung

Baue die folgenden Nationalflaggen mit reinem HTML und CSS:

- 🇦🇹 Österreich
- 🇱🇻 Lettland
- 🇳🇬 Nigeria
- 🇮🇩 Indonesien
- 🇯🇵 Japan
- 🇵🇼 Palau

## Anforderungen

- Es sollte konsequent Box-Model mit padding, margin und oder border zur Erstellung der Flaggen genutzt werden. Position, Flex-Box, Grid, Gradienten usw. sind nicht erlaubt.
- Die österreichische Flagge sollte jeweils mit content-box und border-box umgesetzt werden. Für beide box-sizing Varianten sollte die Flagge nacheinander mit padding, border und margin umgesetzt werden. Das heißt, für die österreichische Flagge sind 6 verschiedene Lösungen gefordert.
- Für alle anderen Flaggen ist nur eine Lösung mit border-box gefordert.
- Für die Grundmaße und Farben der Flaggen sollten CSS-Variablen genutzt werden.
- Es sollte CSS-Nesting genutzt werden.
- Es sollten keine Libraries oder Frameworks genutzt werden.

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

Der Einfachheit halber kann ein Seitenverhältnis für alle Flaggen von 3:2 angenommen werden.

### Farben der Flaggen

Die folgenden Farben können für die Erstellung der Flaggen genutzt werden:

- 🇦🇹 Österreich: rgb(237, 41, 57), rgb(255, 255, 255)
- 🇱🇻 Lettland: rgb(158, 27, 50), rgb(255, 255, 255)
- 🇳🇬 Nigeria: rgb(0, 135, 81), rgb(255, 255, 255)
- 🇮🇩 Indonesien: rgb(255, 0, 0), rgb(255, 255, 255)
- 🇯🇵 Japan: rgb(255, 255, 255), rgb(188, 0, 45)
- 🇵🇼 Palau: rgb(74, 172, 238), rgb(188, 0, 45)

### Abmessungen der Elemente

- 🇱🇻 Das Höhenverhältnis der Streifen in der lettischen Flagge ist 2:1:2.
- 🇯🇵 Der Durchmesser des Kreises in der japanischen Flagge beträgt 60 % der Höhe der Flagge. Der Kreis ist zentriert.
- 🇵🇼 Der Durchmesser des Kreises in der Flagge von Palau beträgt 60 % der Höhe der Flagge. Der Mittelpunkt des Kreises liegt bei 3/8 der Flaggenbreite und 1/2 der Flaggenhöhe.

### Erlaubte CSS-Eigenschaften

- box-sizing
- margin, border, padding
- width, height
- background-color
- border-radius
