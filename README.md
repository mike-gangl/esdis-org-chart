# ESDIS 3.0 Org Chart

Interactive, collapsible org chart built from a plain-text outline.

[Webview of ESDIS 3.0 org chart](https://mike-gangl.github.io/esdis-org-chart/)

- `org.md` is the single source of truth. Edit this file.
- `index.html` renders it. No build step, no dependencies.

## Edit
Open `org.md` on GitHub, click the pencil icon, edit, and commit (or open a pull request).
Syntax: two spaces of indent per level, `- Title | optional note {type}`.
Types: `unit` (displayed as "Pillar"), `team`, `council`, `wg`, `role`, `ext`, `gap` (placeholder / to be added).

## Preview a change before committing
Open the page and click **Live edit**. Changes in the text box render immediately; use **Download org.md** to save.

## Host on GitHub Pages
Repo Settings > Pages > Deploy from branch > `main` / root. The chart will be at `https://<user>.github.io/<repo>/`.

## Run locally
Browsers block `fetch` on `file://`, so serve the folder: `python3 -m http.server` and open http://localhost:8000.
