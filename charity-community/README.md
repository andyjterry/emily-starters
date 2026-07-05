# Charity / Community Organisation Starter

**Last Updated:** 2026-07-05

Mission-led homepage: hero, impact stats, programmes grid, story split with pull quote, donate CTA band (external donation link), volunteer form with interest checkboxes.

All copy is placeholder. All styling comes from emily.config.json tokens.

## Build

From this folder:

```bash
node ../../emily-css/bin/emilyui.js build
node -e "require('../../emily-css/src/index.js').purge()"
```

Then open index.html in a browser.

## Re-brand

Change colours.brand (and optionally fonts) in emily.config.json, rebuild, reload. No HTML edits needed — everything consumes semantic role tokens and pattern classes.
