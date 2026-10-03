# Images

Two different licence situations live in this folder. Keep them straight.

## Manufacturer figures — third-party copyright

Figures from GameSir's manual. Included for reference and identification. **They remain GameSir's copyright and are not relicensed by this repo.** If you mirror or fork this, that restriction travels with them.

| File | What it should show | Source |
|---|---|---|
| `button_overview.png` | Labelled parts overview | [manuals.plus FIG-1](https://manuals.plus/wp-content/uploads/2025/01/GAMESIR-Cyclone-2-Multi-Platform-Wireless-Game-Controller-FIG-1.png) |
| `pairing_combos.png` | The per-platform pairing figures — the glyphs that don't survive text extraction | Cyclone 2 manual, connection section |
| `button_combinations.png` | The manual's Button Combination table | Cyclone 2 manual |
| `indicator_status.png` | Home indicator / charging status table | Cyclone 2 manual |


## Rules

- **Commit the files, never hotlink.** Manual URLs on this product rot fast — `gamesir.hk/pages/manuals-gamesir-cyclone2` is already dead and manuals.plus rotates its hashed paths.
- **Relative paths only** in markdown: `![alt](images/button_overview.png)`.
- **Always write real alt/ascii text.** This is a reference document; people reading it in a terminal or with a screen reader get nothing else.
- **PNG for figures and screenshots, JPG for photographs.** Keep files under ~500 KB.
- **The ASCII diagrams in [shortcuts.md](../shortcuts.md) stay primary.** Images supplement them. ASCII survives offline, greps, and diffs cleanly when someone corrects a button position — a photo can't do any of that.
