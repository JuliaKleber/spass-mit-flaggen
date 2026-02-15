# Spaß mit Flaggen - Normal Flow

## Ziel

In dieser Aufgabe geht es um die Anordnung von Elementen im Normal Flow (Dokumentfluss). Insbesondere geht es um die Ausprägungen `block`, `inline-block` und `inline` der CSS-Eigenschaft `display`.

## Aufgabenstellung

Erstelle die folgenden Nationalflaggen ausschließlich mit HTML und CSS:

- 🇳🇱 Niederlande
- 🇮🇹 Italien
- 🇲🇺 Mauritius
- 🇹🇭 Thailand
- 🇧🇯 Benin

## Anforderungen

- Es soll konsequent der Normal Flow zur Erstellung der Flaggen genutzt werden. Es sollte nur `display: block`, `display: inline-block` und `display: inline` genutzt werden um die Elemente der Flaggen anzuordnen.
- Einschränkungen: Die Verwendung von `border`, `padding`, `position`, `flex`, `grid`, `linear-gradient`, `clip-path` oder `svg` ist nicht erlaubt.
- Keine HTML-Änderungen: Die Struktur der bereitgestellten HTML-Datei darf nicht verändert werden.
- Modernes CSS: Nutze CSS-Variablen für Farben und Grundmaße sowie CSS-Nesting für eine saubere Struktur.
- Tools: Es sollen keine Bibliotheken oder Frameworks genutzt werden.

## Ressourcen

- <a href="https://www.deutrik.de/id/4910990/Display-Block-vs-Inline-vs-Inline-Block-Alles-was-du-wissen-musst/">Display Block vs. Inline vs. Inline-Block: Alles was du wissen musst | Deutrik</a>
- <a href="https://kulturbanause.de/blog/block-inline-elemente-in-html/">Block- & Inline-Elemente in HTML | kulturbanause</a>
- <a href="https://css-tricks.com/fighting-the-space-between-inline-block-elements/">Fighting the space between inline block elements | CSS Tricks</a>

- <a href="https://www.mediaevent.de/css/nesting.html">CSS Nesting | mediaevent</a>
- <a href="https://www.mediaevent.de/css/variable.html">CSS-Variablen | mediaevent</a>
- <a href="https://kulturbanause.de/blog/berechnungen-mit-css-calc/">Berechnungen in CSS | kulturbanause</a>

## Hinweise & Spezifikationen

### Seitenverhältnisse der Flaggen

- 🇳🇱 Niederlande 3:2
- 🇮🇹 Italien 3:2
- 🇲🇺 Mauritius 3:2
- 🇹🇭 Thailand 3:2
- 🇧🇯 Benin 3:2

### Farben der Flaggen

Die folgenden Farben können für die Erstellung der Flaggen genutzt werden:

- 🇳🇱 Niederlande: rgb(173, 29, 37), rgb(255, 255, 255), rgb(30, 71, 133)
- 🇮🇹 Italien: rgb(0, 140, 69), rgb(244, 245, 240), rgb(205, 33, 42)
- 🇲🇺 Mauritius: rgb(208, 28, 31), rgb(45, 51, 89), rgb(247, 183, 24), rgb(0, 134, 88)
- 🇹🇭 Thailand: rgb(165, 25, 49), rgb(45, 42, 74), rgb(244, 245, 248)
- 🇧🇯 Benin: rgb(0, 136, 80), rgb(252, 210, 15), rgb(233, 9, 41)

### Abmessungen der Elemente

- 🇹🇭 Die Höhe der Streifen der Nationalflagge von Thailand stehen im Verhältnis 1:1:2:1:1.
- 🇧🇯 Der grüne vertikale Streifen in der Flagge von Benin nimmt 40 % der Breite der Flagge ein.

### Erlaubte CSS-Eigenschaften

- display
- width, height
- background-color
- calc()
- font-size

### Tipps und Lösungsansätze

Um die Elemente der Flaggen von Italien und Benin so anzuordnen, dass keine Lücken zwischen den Elementen sind oder unerwartete Zeilenumbrüche, kann der folgende Artikel hilfreich sein:

<a href="https://css-tricks.com/fighting-the-space-between-inline-block-elements/">Fighting the space between inline block elements | CSS Tricks</a>

## Zum Weiterlesen

- <a href="https://www.joshwcomeau.com/css/understanding-layout-algorithms/">Understanding Layout Algorithms | Josh Comeau</a>
