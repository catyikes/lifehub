# lifehub

Eine kleine Sammlung statischer HTML-Tools / Demos. Jede Datei ist eine einzelne, eigenständige HTML-Seite und kann lokal im Browser geöffnet oder über GitHub Pages bereitgestellt werden.

## Enthaltene Dateien

- [Passungen auswählen.html](Passungen%20ausw%C3%A4hlen.html) — Passungsrechner (Einheitsbohrung H7)
  - Interaktive Seite zur Auswahl und Visualisierung von ISO-Passungen (H7 mit verschiedenen Wellentoleranzen: g6, h6, js6, k6, m6, p6, s6).
  - Anzeige von Toleranzzonen, Nulllinie und berechnetem Spiel / Übermaß (Angaben in µm).
  - Datei: `Passungen auswählen.html` (vollständiges UI in HTML/CSS/JS).


## Wie du die Seiten nutzt

1) Schnell lokal öffnen
- Nach dem Klonen kannst du eine HTML-Datei einfach per Doppelklick im Browser öffnen oder über `datei -> öffnen` deines Browsers.

2) Lokaler statischer Server (empfohlen für Entwicklung)
```bash
git clone https://github.com/catyikes/lifehub.git
cd lifehub
# mit Python 3
python -m http.server 8000
# dann im Browser öffnen:
# http://localhost:8000/Passungen%20ausw%C3%A4hlen.html
```

3) GitHub Pages (öffentliches Hosting)
- Gehe zu: Repository → Settings → Pages, wähle Branch `main` und Root `/` und speichere. Nach kurzer Zeit sind die Seiten unter `https://catyikes.github.io/lifehub/` erreichbar. Beispiel:
  - https://catyikes.github.io/lifehub/Passungen%20ausw%C3%A4hlen.html


## Eigene Tools / Dateien hinzufügen
- Lege weitere statische HTML-Dateien in dieses Repo (z. B. `tools/mein-tool.html`) und committe sie.
- Optional: erstelle eine `index.html`-Seite, die alle Tools mit Vorschaubild und Beschreibung listet.

## Backup / Versionierung
- Nutze Git (commit/push) um Änderungen zu verfolgen. Exportiere einzelne Seiten bei Bedarf als ZIP oder verwalte Versionen über Branches.

---

Wenn du willst, kann ich:
- eine `index.html` mit Vorschauliste aller Tools erstellen und ins Repo hinzufügen,
- die vorhandene Datei umbenennen (z. B. `passung.html`) und Links aktualisieren,
- oder die `comments_table.html` (Kommentar-UI) in das Repo einfügen und verlinken.
