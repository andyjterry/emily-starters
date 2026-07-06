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
| `one-page-business/` | Whole business on one page: sticky header, services, about, testimonials, FAQ, contact |
| `professional-services/` | Credibility-led firm site: top bar, process, team, client outcomes, consultation form |
| `charity-community/` | Mission-led site: impact stats, programmes, story + pull quote, donate CTA, volunteer form |
| `portfolio-case-study/` | Work-led site: portfolio grid, featured case study, approach, contact band |
| `campaign-landing/` | Single-goal landing page: minimal chrome, offer alert, one form, noindex |

All starters share the same section vocabulary from `emily-components/templates/` — only `emily.config.json` differs per brand.

Not sure which to pick? See `emily-components/docs/starter-selection-guide.md`.

## Packaging

This repo is prepared as the future `@emilyui/starters` npm package but is **not published**
(`"private": true` guards against accidental publish until a consumer exists).

- Planned install: `npm install @emilyui/starters` — though the primary consumer is a future
  `emilyui init`, which copies a chosen starter folder into a new project rather than importing code.
- Package payload: the six built starter folders, each self-contained (`README.md`,
  `emily.config.json`, `index.html`, `dist/emily.css`). Built CSS ships on purpose — starters
  are zero-build by design.

## Images

Starters reference relative local placeholders (`images/placeholders/team-member.jpg`, `case-study.jpg`, `community-event.jpg`, …). The files are intentionally not committed — drop your own images under those names, or swap the paths. Never wire a starter to a live third-party image host; use licensed/approved images in production. Meaningful images need real alt text, decorative ones `alt=""`.

## Boundaries

- Placeholder copy only — client copy belongs in client projects.
- New reusable patterns extracted from a starter go to `emily-components`; new CSS goes to `emily-css`.
