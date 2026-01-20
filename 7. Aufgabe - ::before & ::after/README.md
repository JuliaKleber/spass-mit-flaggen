# Spaß mit Flaggen - Aufgabe 7 (::before & ::after)

## Ziel

Ziel der Aufgabe ist es die Pseudoklassen ::before und ::after zu nutzen, um das HTML-Template übersichtlich zu halten.

## Aufgabenstellung

Erstelle die folgenden Nationalflaggen mit reinem HTML und CSS:

- 🇳🇱 Niederlande
- 🇮🇹 Italien
- 🇧🇯 Benin
- 🇯🇵 Japan
- 🇵🇼 Palau
- 🇨🇭 Schweiz
- 🇸🇪 Schweden
- 🏴󠁧󠁢󠁳󠁣󠁴󠁿 Schottland
- 🇹🇹 Trinidad und Tobago

## Anforderungen

- Es sollte für jede Flagge nur ein einziges Div genutzt werden. Das Styling soll über dieses div und die Pseudoklassen ::before und ::after erfolgen. Nutzung von Gradienten ist nicht erlaubt.
- Für die Grundmaße und Farben der Flaggen sollten CSS-Variablen genutzt werden.
- Es sollte CSS-Nesting genutzt werden.
- Es sollten keine Libraries oder Frameworks genutzt werden.

## Ressourcen

- <a href="https://kulturbanause.de/blog/generierter-css-content-mit-before-und-after/">::before | Kulturbanause</a>
- <a href="https://www.mediaevent.de/css/nesting.html">CSS Nesting | mediaevent</a>
- <a href="https://www.mediaevent.de/css/variable.html">CSS-Variablen | mediaevent</a>
- <a href="https://kulturbanause.de/blog/berechnungen-mit-css-calc/">Berechnungen in CSS | kulturbanause</a>

## Hinweise

### Seitenverhältnisse der Flaggen

- 🇳🇱 Niederlande 3:2
- 🇮🇹 Italien 3:2
- 🇧🇯 Benin 3:2
- 🇯🇵 Japan 3:2
- 🇵🇼 Palau 8:5
- 🇨🇭 Schweiz 1:1
- 🇸🇪 Schweden 16:10
- 🏴󠁧󠁢󠁳󠁣󠁴󠁿 Schottland 3:2
- 🇹🇹 Trinidad und Tobago 5:3

### Farben der Flaggen

Die folgenden Farben können für die Erstellung der Flaggen genutzt werden:

- 🇳🇱 Niederlande: rgb(173, 29, 37), rgb(255, 255, 255), rgb(30, 71, 133)
- 🇮🇹 Italien: rgb(0, 140, 69), rgb(244, 245, 240), rgb(205, 33, 42)
- 🇧🇯 Benin: rgb(0, 136, 80), rgb(252, 210, 15), rgb(233, 9, 41)
- 🇯🇵 Japan: rgb(255, 255, 255), rgb(188, 0, 45)
- 🇵🇼 Palau: rgb(74, 172, 238), rgb(188, 0, 45)
- 🇨🇭 Schweiz: rgb(255, 0, 0), rgb(255, 255, 255)
- 🇸🇪 Schweden: rgb(0, 91, 174), rgb(255, 195, 1)
- 🏴󠁧󠁢󠁳󠁣󠁴󠁿 Schottland: rgb(0, 94, 184), rgb(255, 255, 255)
- 🇹🇹 Trinidad und Tabago: rgb(218, 26, 53), rgb(255, 255, 255), rgb(0, 0, 0)

### Abmessungen der Elemente

- 🇧🇯 Der grüne vertikale Streifen in der Flagge von Benin nimmt 40 % der Breite der Flagge ein.
- 🇯🇵 Der Durchmesser des Kreises in der japanischen Flagge beträgt 60 % der Höhe der Flagge. Der Kreis ist zentriert.
- 🇵🇼 Der Durchmesser des Kreises in der Flagge von Palau beträgt 60 % der Höhe der Flagge. Der Mittelpunkt des Kreises liegt bei 3/8 (37,5%) der Flaggenbreite und 1/2 der Flaggenhöhe.
- 🇨🇭 Für das Seitenverhältnis der weißen Balken des Kreuzes der schweizer Flagge kann 6:20 angenommen werden. Die Höhe des Kreuzes der schweizer Flagge entspricht 5/8 der Höhe der Flagge.
- 🇸🇪 Für die Breite der beiden Balken in der schwedischen Flagge können 20% der Höhe der Flagge angenommen werden.
- 🏴󠁧󠁢󠁳󠁣󠁴󠁿 Die Breite der Balken der schottischen Flagge beträgt 20% der Höhe der Flagge. Sie sind um 33.7 Grad zur Waagerechten gedreht.
- 🇹🇹 Die Streifen in der Flagge von Trinidad und Tobago sind um 41 Grad gedreht. Die Breite des weißen Streifens entspricht 33% der Höhe der Flagge und die Breite des schwarzen Streifens entspricht 22% der Höhe der Flagge.
