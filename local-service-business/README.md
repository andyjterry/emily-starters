# Local Service Business Starter

**Last Updated:** 2026-07-05

One-page homepage for a local trade/service business, composed entirely from `emily-components` patterns: skip link + header, hero, trust strip, services grid, split "why us" section, CTA band, contact/quote form, footer.

All copy is placeholder. All styling comes from `emily.config.json` tokens.

## Build

From this folder:

```bash
node ../../emily-css/src/index.js
```

(or `npx emily-css build` if `emily-css` is installed)

Then open `index.html` in a browser.

## Re-brand

Change `colours.brand` (and optionally `accent`, fonts) in `emily.config.json`, rebuild, reload. Nothing in `index.html` needs to change — components consume semantic role tokens and pattern classes.
