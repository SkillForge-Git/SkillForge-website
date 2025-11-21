# Skill-Forge Projekt-Schmiede

Dieses Repository ist das Startpaket fuer alle Skill-Forge-Projekte. Es ist bewusst einfach gehalten: kurze Texte, feste Ordner, klare Tabellen. So koennen auch Kids ab 12 Jahren loslegen, waehrend wir spaeter trotzdem automatisch Anzeigen und Stats bauen koennen.

> **Hinweis:** Klicke auf GitHub auf **Use this template**, gib deinem Projekt einen Namen (z. B. `2025-kamenz-sensorbox`) und fuelle danach nur die vorhandenen Dateien.

## So funktioniert es
1. **Idee festhalten:** In `1-idea-forge/canvas.md` (Idea Forge · Ideenschmiede) dein Ziel, die Nutzenden und das geplante Ergebnis beschreiben.
2. **Checklisten nutzen:** In jedem Forge-Ordner gibt es eine `checklist.md`. Setze Haken, wenn etwas fertig ist.
3. **Kurze Updates schreiben:** Einmal pro Woche etwas in `docs/checkpoints.md` eintragen.
4. **Bilder & Videos ablegen:** In den Ordnern unter `assets/` speichern.
5. **Am Ende alles sammeln:** In `5-skill-forge/handover.md` steht, was fuer den Abschluss wichtig ist.

## Verzeichnisstruktur
```
project-name/
├── 0-admin/
├── 1-idea-forge/        (Idea Forge · Ideenschmiede)
├── 2-maker-forge/       (Maker Forge · Makerschmiede)
├── 3-copper-forge/      (Copper Forge · Kupferschmiede)
├── 4-code-forge/        (Code Forge · Codeschmiede)
├── 5-skill-forge/       (Skill Forge · Skill-Schmiede)
├── assets/
│   ├── data/
│   ├── images/
│   └── videos/
├── docs/
│   ├── checkpoints.md
│   ├── qa-checklist.md
│   └── retro.md
└── README.md (dieser Steckbrief)
```

Loesche keine Ordner. Die Website findet spaeter anhand dieser Namen alle Infos.

## README-Template
Die Datei `README.md` ist der Projekt-Steckbrief. Fuell die Abschnitte mit einfachen Saetzen aus:

```
# Projektname

Kurzer Satz: Was bauen wir? Fuer wen?

## Plan
- Ziel:
- Was brauchen wir?
- Wann wollen wir fertig sein?

## Team
- Namen oder Nicknames
- Ansprechpartner

## Fortschritt
- Idea Forge (Ideenschmiede): ...
- Maker Forge (Makerschmiede): ...
- Copper Forge (Kupferschmiede): ...
- Code Forge (Codeschmiede): ...
- Skill Forge (Skill-Schmiede): ...

## Dokumentation
- Checkpoints: Link zur Datei docs/checkpoints.md
- Tests: Link zur Datei docs/qa-checklist.md
- Rueckblick: Link zur Datei docs/retro.md

## Medien
- Wichtigste Fotos (Dateiname in assets/images)
- Videos (Datei in assets/videos oder Link)

## Lessons Learned
Was nehmen wir mit?
```

## Automatisierung
Im Ordner `.github/workflows/` liegt ein Beispiel-Workflow. Er ist ausgeschaltet, bis ihr ihn braucht. Wenn ihr spaeter Tests oder Exporte automatisieren wollt, koennt ihr dort weiterarbeiten.

## Hilfe
Wenn etwas unklar ist, fragt ein Team-Mitglied, schreibt ein Issue oder meldet euch unter `info@skill-forge.de`.
