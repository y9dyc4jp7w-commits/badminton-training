# Vorversion – Archiv

## Was hier liegt
Die alte Version der App (vor dem V3 Neon Minimal Redesign).

## Wie auf GitHub archivieren

1. Auf GitHub.com ins Repository `badminton-training` gehen
2. Alle alten Dateien markieren:
   - `index.html` (alte Version)
   - `training-data.json`
   - `icon.png`, `icon_v1.png`, `icon_v2.png`, `icon_v3.png`
   - `theme-current.html`, `theme-v1.html`, `theme-v2.html`, `theme-v3.html`
3. → Einen neuen Ordner `Vorversion/` erstellen
4. Dateien in den Ordner verschieben (via GitHub "Move file")

ODER einfacher:
- Neuen Ordner `Vorversion/` auf GitHub erstellen
- Alte Dateien dorthin hochladen (Kopie)
- Dann neue Dateien im Root ersetzen

## Neue Dateistruktur (V3)

```
/ (Root)
├── index.html              ← neue App (V3 Neon Minimal)
├── data/
│   ├── index.json          ← Monatsliste
│   └── months/
│       ├── training_2026-01.json
│       ├── training_2026-02.json
│       ├── training_2026-03.json
│       ├── training_2026-04.json
│       ├── training_2026-05.json
│       └── training_2026-06.json
├── assets/
│   └── icons/
│       └── icon.png
└── Vorversion/             ← alte Dateien hier
    ├── index.html (alt)
    └── training-data.json (alt)
```
