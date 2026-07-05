# Professional Services Starter

**Last Updated:** 2026-07-05

Credibility-led homepage: utility top bar, hero, credentials strip, services grid, process, team, client outcomes, consultation form. Composed from the homepage and about templates.

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
