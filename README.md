# 🕹️ Arcade Prompt & Play

Public home page for all the browser games: **https://crisai2026.github.io**

## Adding a game

Edit `index.html` and, inside the `GAMES` list, copy a `{ ... }` block and change:

- `repo`: repository name on github.com/crisai2026
- `name`, `emoji`, `color`, `updated` (date YYYY-MM-DD)
- `tags`: categories (3d, action, sim, adventure, platform, rpg, calm, strategy, rhythm, 2p)
- `play`: `"auto"` = https://crisai2026.github.io/&lt;repo&gt;/ (needs GitHub Pages turned on in that repo), another link, or `""`
- `en` / `es`: description in English and Spanish
- `by`: who made it (optional)
- `hidden: true` to hide it without deleting it

The page checks by itself which games have GitHub Pages turned on and disables the ▶ button for the ones that don't.
