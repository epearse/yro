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
