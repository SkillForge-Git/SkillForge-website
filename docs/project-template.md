# Skill-Forge Projekt-Schmiede Template

Dieses Template hilft Teams von 12 bis 99 Jahren. Alles ist einfach gehalten, bleibt aber so aufgebaut, dass wir spaeter automatisch planen und Auswertungen machen koennen.

## Ordnerstruktur

```
project-name/
├── 0-admin/               # Wer macht mit? Welche Termine?
├── 1-idea-forge/          # Idea Forge · Ideenschmiede (Idee, Ziel, Materialliste)
├── 2-maker-forge/         # Maker Forge · Makerschmiede (Bau-Plan, 3D-Druck, Laser)
├── 3-copper-forge/        # Copper Forge · Kupferschmiede (Elektronik)
├── 4-code-forge/          # Code Forge · Codeschmiede (Programmcode)
├── 5-skill-forge/         # Skill Forge · Skill-Schmiede (Finale Ergebnisse)
├── assets/
│   ├── images/            # Fotos
│   ├── videos/            # Videos
│   └── data/              # Messwerte oder Tabellen
├── docs/
│   ├── checkpoints.md     # Kurzer Wochenbericht
│   ├── qa-checklist.md    # Testliste
│   └── retro.md           # Rueckblick
└── README.md              # Projekt-Steckbrief
```

Die Dateinamen bleiben immer gleich. So weiss die Website spaeter, wo sie nach Infos suchen muss.

## Datei-Inhalte in Kuzeform
- `README.md`: Kurzer Projekt-Steckbrief. Enthält Ziel, Material-Tabelle, Fortschritt und Links zu Medien.
- `checkpoints.md`: Tabelle mit Datum, was passiert ist, welche Forge, naechster Schritt.
- `qa-checklist.md`: Ein Haken pro Test.
- `retro.md`: Drei Fragen zum Rueckblick.
- Jede Forge hat eine `checklist.md` und eine Plan-Datei (z. B. `plan.md` oder `canvas.md`). Schreibe dort einfache Saetze.

## So nutzt du das Template
1. Auf GitHub **Use this template** klicken.
2. Dem Repository einen Namen geben: `jahr-ort-projekt`.
3. In jedem Ordner die Markdown-Dateien ausfuellen. Hilfsaussagen kannst du loeschen.
4. Bilder und Videos in den passenden Asset-Ordner legen.
5. Jede Woche einen kurzen Eintrag in `docs/checkpoints.md` machen.

## Warum dieser Aufbau wichtig ist
- Automatisierte Auswertungen koennen Ziel, Plan und Ergebnisse aus den Markdown-Dateien lesen.
- Fotos und Videos werden durch den Ordnernamen erkannt.
- Checklisten zeigen den Fortschritt je Forge.

## Fragen
Wenn dir etwas fehlt, eroeffne ein Issue im Template-Repository oder schreib an `info@skill-forge.de`.
