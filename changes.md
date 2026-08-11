Änderungsverzeichnis (Kurzfassung)
Erstellt: 2026-08-11T20:44:15+02:00

- 31301bb: README-Inhalte in index.html integriert
  - "Teilnehmer"-Sektion hinzugefügt
  - "Anreise & Unterkunft" erweitert (Hotel, Kosten, Zimmeraufteilung)
  - Datei: index.html (modifiziert)

- f35f9ee: Inline-Styles extrahiert
  - Inline <style> in styles.css ausgelagert
  - index.html angepasst
  - Datei: styles.css (neu)

- 9f948f7: Styles in mehrere Dateien aufgeteilt
  - Erstellt: css/base.css, css/layout.css, css/components.css, css/utilities.css
  - index.html lädt nun die CSS-Dateien aus css/
  - Removed: styles.css

- f28d9ae: Reset und Variablen eingeführt
  - Erstellt: css/reset.css, css/variables.css
  - base.css nutzt CSS-Variablen (var(--...))
  - index.html: Links zu reset.css und variables.css hinzugefügt

- a5f4961: variables.css dokumentiert
  - Detaillierte Kommentare, Nutzungshinweise, Spacing-Scale, Layout- und Misc-Tokens
  - Datei: css/variables.css (modifiziert)

- 09d19ce: Abschluss / Aufräumen
  - Entfernt: root styles.css
  - Hinzugefügt: README.md, .github/copilot-instructions.md
  - Abschlusscommit: alle offenen Änderungen gebündelt und gepusht

Status: Alle Änderungen wurden committed und nach origin/main gepusht.

Wichtige Pfade:
- index.html
- css/ (reset.css, variables.css, base.css, layout.css, components.css, utilities.css)
- README.md
- .github/copilot-instructions.md

Hinweis: Variablen in css/variables.css sind dokumentiert; empfohlen ist künftige Anpassungen dort vorzunehmen.

- 81419e9: Accessibility & Security Verbesserungen
  - Korrigiert: title ("Wiesnturnier 2026") und meta description hinzugefügt
  - Semantik: <div class="container"> → <main class="container">
  - Daten: Termine mit <time datetime="YYYY-MM-DD"> ausgezeichnet
  - A11y: Dekorative Emojis mit aria-hidden, .icon Elemente mit aria-hidden
  - Kontakt: Kontaktblock in <address>, Telefonnummern als tel:, E-Mail als mailto:
  - Security: Externe Links mit target="_blank" bekommen rel="noopener noreferrer"
  - Commit & Push: Änderungen committed (81419e9) und nach origin/main gepusht

Status: Alle Änderungen wurden committed und nach origin/main gepusht. Letzter Commit: 81419e9
