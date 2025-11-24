# Skill-Forge Website Redesign Blueprint

## Navigationsstruktur
1. **Start** – Überblick, Positionierung, Impact-Zahlen, Call-to-Action.
2. **Konzept** – Zielsetzung, Vier Kernziele, GitHub-Projekte, Förderargumente.
3. **Open Space** – Standort Kamenz, Raumkonzept entlang der fünf Schmieden, Infrastruktur & Sicherheit.
4. **Bildung** – Kurse, Zertifikate, Projektwege, Community-Beiträge.
5. **Spielerisch lernen** – Gamification-System (Badges, Quests, Ränge) plus die fünf Säulen.
6. **Kontakt** – Förder:innen, Partner, Newsletter, Ansprechpartner.

## Gestaltung
- **Typography**: Display Font "Space Grotesk" für Headlines, "Inter" für Fließtext.
- **Farben**: Tiefes Anthrazit (#0d1117) als Basis, Akzentfarben Kupfer (#d97742), Neon-Türkis (#46e6c3) und Warmgrau (#8c919b).
- **Layout**: Breite von 1200px, großzügige Whitespace, Gridcards mit Glasoptik, diagonale Divider nach Schmiede-Metapher.
- **Icons**: Lucide Icons (CDN) für Schnellkommunikation je Card.
- **Hero Images**: Unsplash-Fotos für Werkstatt, Lernen, Community; können später ersetzt werden.

## UX-Hooks
- Fördersprech: Impact-Boxen mit Kennzahlen (z. B. "200 m² offene Werkstatt").
- GitHub Spotlight: Automatisches Laden der neuesten Repos auf Konzeptseite.
- Schnellkontakt + Förderpakete auf Kontaktseite.
- CTA-Streifen am Ende jeder Seite (Newsletter, Fördergespräch, Besuch).

## Technische Eckpunkte
- Vollständig neue CSS-Datei mit CSS Custom Properties, flexiblen Grid-Utilities und Light/Dark Cards.
- Responsiver Header mit Mobile Drawer.
- Sanfte Scroll-Animationen via prefers-reduced-motion checks (nur CSS).
- Utility-Klassen für Iconchips, KPI-Tiles, Timeline-Komponenten.

Dieses Blueprint orientiert sich eng an der Vision.md und dient als Leitplanke für die Neuentwicklung aller Seiten.