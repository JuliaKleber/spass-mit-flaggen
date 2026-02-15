# Box-Modell: padding, margin, border

## Ziel

Ziel dieser Aufgabe ist es, ein Verständnis für das CSS-Box-Modell (`padding`, `border`, `margin`) zu entwickeln.

Wichtiger Hinweis: Für alle Aufgaben ist die Eigenschaft `box-sizing: border-box;` vordefiniert.

## Hintergrund

Der W3C-Standard für `box-sizing` ist `content-box`. Bei diesem Modell vergrößern `padding` und `border` ein Element. Um dieses Verhalten zu umgehen, setzen fast alle modernen CSS-Resets auf `border-box`. Wenn `border-box` verwendet wird, ist das Element immer gleich groß, unabhängig davon welche Maße für `padding` und `border` gewählt werden. In dieser Aufgabe arbeiten wir bewusst mit `border-box`.

## Aufgabenstellung

Erstelle die folgenden Nationalflaggen ausschließlich mit HTML und CSS:

- 🇦🇹 Österreich
- 🇱🇻 Lettland
- 🇳🇬 Nigeria
- 🇮🇩 Indonesien
- 🇯🇵 Japan
- 🇵🇼 Palau
- 🇹🇭 Thailand

## Anforderungen

- Box-Modell: Nutze konsequent `padding`, `margin` und/oder `border`, um die Elemente der Flaggen darzustellen.
- Einschränkungen: Die Verwendung von `position`, `flex`, `grid`, `linear-gradient`, `clip-path` oder `svg` ist nicht erlaubt.
- Keine HTML-Änderungen: Die Struktur der bereitgestellten HTML-Datei darf nicht verändert werden.
- Modernes CSS: Nutze CSS-Variablen für Farben und Grundmaße sowie CSS-Nesting für eine saubere Struktur.
- Tools: Es sollen keine Bibliotheken oder Frameworks genutzt werden.

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
- 🇯🇵 Der Durchmesser des Kreises in der japanischen Flagge beträgt 60 % der Höhe der Flagge. Der Kreis ist mittig zentriert.
- 🇵🇼 Der Durchmesser des Kreises in der Flagge von Palau beträgt 60 % der Höhe der Flagge. Der Mittelpunkt des Kreises liegt bei 3/8 der Flaggenbreite und 1/2 der Flaggenhöhe.
- 🇹🇭 Die Streifen der Nationalflagge von Thailand stehen in dem Verhältnis 1:1:2:1:1.

### Erlaubte CSS-Eigenschaften

- box-sizing
- margin, border, padding
- width, height
- background-color
- border-radius
- calc()

## Tipps & Lösungshinweise

- Streifen: Äußere horizontale oder vertikale Streifen lassen sich durch die `border`-Eigenschaft erzeugen.
- Kreise: Setze `width` und `height` des inneren Elements auf 100% und verwende `border-radius: 50%`. Nutze das padding des äußeren Containers, um die Größe und Position des Kreises zu steuern.

## Zum Weiterlesen

- <a href="https://www.joshwcomeau.com/css/rules-of-margin-collapse/">The Rules of Margin Collapse | Josh Comeau</a>
