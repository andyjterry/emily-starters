# emily-starters

**Last Updated:** 2026-07-05

Full page compositions assembled from `emily-components` patterns and styled entirely by `emily-css` tokens. Each starter is a working, browser-viewable example of a real site type — the fastest path from "client brand tokens" to "reviewable page".

## How a starter works

Each starter folder contains:

- `emily.config.json` — the brand token file. This is the only place brand decisions live.
- `index.html` — the page, built from copy-paste patterns. No build tooling, no framework.
- `dist/emily.css` — generated stylesheet (rebuild after config changes).

## Build and view

From inside a starter folder:

```bash
npx emily-css build     # or: node ../../emily-css/src/index.js
```

Then open `index.html` in a browser.

To re-brand for a client: edit the colours/fonts in `emily.config.json`, rebuild, done. No component edits needed — patterns consume semantic role tokens.

## Starters

| Folder | What it proves |
|---|---|
| `local-service-business/` | Homepage: header/nav, hero, services grid, trust strip, split section, CTA band, contact form, footer |

## Boundaries

- Placeholder copy only — client copy belongs in client projects.
- New reusable patterns extracted from a starter go to `emily-components`; new CSS goes to `emily-css`.
