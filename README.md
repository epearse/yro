# Slow the Rush to YRO

Public site on Cal Poly San Luis Obispo's year-round-operations plan, prepared by Cal Poly faculty.

The whole site is one file, `index.html` — HTML, CSS and JavaScript together, with no build step. Fonts load from Google Fonts; everything else is inline.

## Hosting

- Source: this GitHub repository
- Hosting: Netlify, deploying automatically from the `main` branch (`netlify.toml` tells it to publish the repo root as-is)

## Editing

1. Edit `index.html`
2. Open it in a browser to check it (`open index.html` on a Mac)
3. Commit and push to `main`:

```sh
git add index.html
git commit -m "Describe the change"
git push
```

Netlify rebuilds within about a minute of each push.

## Before going public

See [BEFORE-GOING-PUBLIC.md](BEFORE-GOING-PUBLIC.md) for the checklist (survey link, fact checks, byline).

## Other pages in this repo

- `/ledger/` and `/model-explorer/` — the Year-Round Operations Ledger and its model explorer, copied from
  the claude.ai artifacts on 11 November 2026. Not linked from the main page; both carry `noindex`. They
  link to each other by site path, so re-copying from the artifacts means re-pointing those links.
- `/archive/2026-11-11/` — a frozen, self-contained copy of the main page and `/takeaction` as they stood
  before the November rewrite (also `noindex`). The same state is tagged `archive-2026-11-11` in git.
