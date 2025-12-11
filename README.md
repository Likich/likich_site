# Likich Research Log

Static personal/research site for Angelina “Lika” Parfenova. Contains the main page, a highlights feed (with screenshot-based posts), and publication data pulled from a cached JSON.

## Structure
- `index.html` — main site with nav, hero, projects, and publication list (loaded from `publications.json`).
- `highlights.html` / `highlights.json` — feed page; drop screenshots into `shots/` and update JSON entries.
- `portrait.jpeg` — badge portrait (falls back to `portrait.jpg` if present).
- `publications.json` — cached Google Scholar publications.

## Usage
Serve locally with any static server, e.g.:
```
python -m http.server 8000
```
Open `http://localhost:8000/index.html`.

