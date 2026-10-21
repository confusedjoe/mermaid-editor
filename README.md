# Mermaid Editor

**Online öffnen:** https://confusedjoe.github.io/mermaid-editor/

Einzelne HTML-Datei zum Erstellen und Bearbeiten von Mermaid-Diagrammen – einfach `mermaid-editor.html` im Browser öffnen (Internet nötig, Mermaid kommt vom CDN).

- Links Code, rechts Live-Vorschau
- Knoten und Subgraphen frei verschieben, Pfeile folgen; Positionen landen als `%% @layout {...}` im Code
- Flowchart: Knoten anfügen, verbinden, umbenennen (Doppelklick/F2), löschen (Entf), Undo/Redo
- Jedes Feld einzeln einfärben (Palette oder Füllung/Rahmen/Text frei wählbar)
- Vorlagen, Öffnen/Speichern als `.mmd`, Export als SVG/PNG
- Pan per Hintergrund ziehen, Zoom per Mausrad

## Am Handy

Link oben im Handy-Browser öffnen, am besten über «Zum Startbildschirm hinzufügen».

- Unten zwischen **Code** und **Diagramm** umschalten (roter Punkt bei Code = Fehler im Code)
- Ziehen mit einem Finger = Knoten verschieben bzw. Ansicht schieben, zwei Finger = Zoom
- Doppeltippen auf einen Knoten = umbenennen
- Werkzeugleiste oben seitlich wischen

## Mit KI bearbeiten (Claude)

Knopf **✦ KI**:

1. Wunsch eingeben, z. B. «Füge nach Verarbeiten eine Prüfung mit Fehlerzweig ein»
2. **Prompt kopieren** (oder am Handy **Teilen … → Claude-App**, oder **Claude öffnen** = claude.ai mit kopiertem Prompt) und in Claude einfügen
3. Antwort von Claude ins untere Feld einfügen → **Übernehmen** (der ```mermaid-Block wird herausgesucht; rückgängig mit ↶)

Jeder nutzt dabei sein eigenes Claude-Konto, der Editor speichert keine Zugangsdaten.

Beispieldiagramme liegen in `diagramme/`.

## Lizenz

MIT – siehe [LICENSE](LICENSE). Nutzt [Mermaid](https://github.com/mermaid-js/mermaid) (MIT) vom CDN.
