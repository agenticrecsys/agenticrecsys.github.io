# agenticrecsys.github.io

GitHub Pages site for the **Multi-Agentic Recommender Systems** tutorial series.

Two editions are hosted:

- **SIGIR 2026** — `/sigir2026/` (latest)
- **RecSys 2025** — `/recsys2025/`

The root (`/`) redirects to the latest edition (`/sigir2026/`). Each edition
cross-links to the other from its top navigation.

## Structure

- `index.html` — redirect from `/` to the latest edition (`/sigir2026/`)
- `recsys2025.md` — RecSys 2025 edition
- `sigir2026.md` — SIGIR 2026 edition
- `_layouts/home.html` — shared, parameterized tutorial layout (hero, nav, footer driven by page front matter)
- `assets/css/site.css` — site styling

## Deployment

This repository is deployed automatically with GitHub Pages on every push to the default branch.
