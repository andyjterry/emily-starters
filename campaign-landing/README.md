# Campaign Landing Page Starter

**Last Updated:** 2026-07-05

Single conversion goal: minimal chrome (logo + phone), offer alert, message-matched hero, trust strip, problem/proof pair, one short form. noindex by default.

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
