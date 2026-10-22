# ScorePal – Scoring-Prototyp

Zählkarte für 1 bis 4 Pals. Plätze: GC Bockfließ, Diamond Country Club, GC Spillern, GC Wien (Freudenau), GC Wels.
Wertung: Stableford netto oder Zählspiel brutto. 18 Loch, Loch 1–9 oder Loch 10–18.

## Auf GitHub Pages testen
1. Neues Repository auf github.com anlegen (z. B. `scorepal-scoring`).
2. `index.html` aus diesem Ordner hochladen (Add file → Upload files → Commit).
3. Settings → Pages → Source: „Deploy from a branch“, Branch `main`, Ordner `/ (root)` → Save.
4. Nach 1–2 Minuten läuft die App unter `https://<dein-name>.github.io/scorepal-scoring/`.
5. Am Handy öffnen → „Zum Home-Bildschirm“ hinzufügen.

Die Datei ist komplett eigenständig (Schriften und Styles eingebettet) und läuft auch offline weiter, sobald sie geladen ist.
Die Runde wird lokal im Browser gespeichert und übersteht Neuladen und App-Wechsel.

## Berechnung
- Spielvorgabe = HCP-Stv. × Slope / 113 + (CR − Par), gerundet. Bei 9 Loch: halber Index und halbes CR.
- Vorgabeschläge werden nach Hcp-Reihenfolge der gespielten Löcher verteilt.
- Stableford: Netto-Par = 2 Punkte. „Strich“ = 0 Punkte, zählt im Zählspiel als Netto-Doppelbogey.
- Plus-Handicap: Eingabe mit „+“, z. B. `+1,2`.

## Platzdaten
Par, Hcp, Meter, CR und Slope stammen von den Scorecards und Vorgabentabellen der Clubs (Stand Oktober 2026). Weichen die Werte vom Aushang ab, lassen sich CR und Slope im Setup unter „CR & Slope prüfen oder anpassen“ korrigieren.

---
© ScorePal Golf e.U., alle Rechte vorbehalten.
