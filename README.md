# 🔖 My Bookmarks

A personal bookmark dashboard in a **single, self-contained HTML file** — no build step, no dependencies, no server. Just open `index.html` in any browser and start saving links. Everything is stored locally in your browser.

## Features

- **Add bookmarks** with a title, URL, category, and optional notes
- **Card grid layout** that's clean and modern
- **Live search** filtering by title or category
- **Category filter chips** generated automatically from your bookmarks
- **Delete** bookmarks you no longer need
- **Persistent storage** via the browser's `localStorage` — your bookmarks survive reloads
- **Sample bookmarks** seeded on first load so it's never empty
- **Responsive** — adapts from a multi-column grid down to a single column on mobile
- **Light-blue, modern UI**

## Usage

Clone or download the repo, then open the file:

```bash
open index.html        # macOS
# or just double-click index.html in your file manager
```

That's it — no installation required.

## Tech

Plain HTML, CSS, and vanilla JavaScript in one file. User-supplied text is HTML-escaped before rendering, and URLs without a scheme automatically get `https://` prepended.

## License

MIT — free to use and modify.
