# teplica

Sound system design projects for venues (P2P Tech client work). Each venue or object has its own folder (`sound/` = Теплица, `vo-9-liniya-60/` = 9-я линия В.О., 60). Everything is in Russian. Keep it that way.

## Per-project folder layout

- `README.md`: the design (zones, equipment, wiring), linked from the root README.
- `bom.csv` / `ESTIMATE.md` / `smeta-*.xlsx`: equipment list and estimate. Keep them consistent with each other.
- Diagrams: edit the `.svg`, re-export the `.png` next to it.
- Client PDF: rebuild it after changing the design, and note the page count in the session summary.

## Rules

- `SESSION-SUMMARY.md` is the log of decisions. Add a dated row when the design or the totals change.
- Prices: say where they came from (store, date). The client's Google Sheet is the source of truth for what was agreed. Note whether it was updated.
- New venue = new folder + a line in the root README.
