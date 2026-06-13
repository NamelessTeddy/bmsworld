# BMS World

A simple static site that hosts BMS difficulty tables, intended to be used with BMS players that support the `bmstable` meta tag (e.g. LR2, beatoraja).

I may end up adding a table of my personal chart recommendations in the future, but for now readers can consider this as currently not being maintained.

Hosted at: https://namelessteddy.github.io/bmsworld/

## Structure

- **`index.html`** — landing page listing available difficulty tables
- **`bms-table.html`** / **`data.json`** / **`header.json`** — the main 発狂BMS難易度表 (★) table data and viewer
- **`insane1/`** — a separate copy/attempt at hosting the 発狂BMS難易度表 (★) table

## Notes

### Insane1 table

The `insane1/` directory is an incomplete attempt at importing the Insane1 (発狂BMS難易度表) table. The source data for that table keeps getting moved around — the URL for the table data changes over time — so I couldn't get a stable import working at the time. The `insane1/header.json` currently just points back to the local `data.json` as a placeholder.
