repo: ghoust640/CLASSIFIED-07
branch: main
path: /

## Last sync
date: 2026-08-10T05:08:20Z

### Updated in this project
- Diagnosed the Telegram link preview: committed `og:image` / `twitter:image` use `images/g7-link-card.png`, but the PNG is at the repo root — 404, so no card image.
- Handed over the absolute-URL fix for `index.html` lines 12 and 19 (not pushed — needs a manual commit).
- Local `G7 Dossier.dc.html` keeps the relative path, correct for the project's own `images/` folder.

## Screen map
| Project screen | Repo files |
| --- | --- |
| G7 Dossier.dc.html | index.html |
| G7 Dossier Link Card.dc.html | g7-link-card.png |
| Canvas.dc.html | Canvas.html |
| (runtime) | support.js, image-slot.js, nocturne-tokens.css |
