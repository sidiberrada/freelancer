# Mohamed Berrada — Personal Landing Page

A single-file personal profile / landing page. Everything ships in one HTML
document: styles, scripts, and the portrait (embedded as a base64 data URI), so
there are no build steps and no runtime asset requests beyond the Google Fonts
stylesheet.

## Contents

| File | Purpose |
| --- | --- |
| `index.html` | The complete page — markup, CSS tokens, and behaviour |
| `images.jfif` | Original source photo, kept for future edits (the page uses the inlined copy) |

## Running it locally

Open `index.html` in any browser — no server or dependencies required.

## Theming

The page defines a full light palette on `:root` and overrides it for dark mode
in two places: `@media (prefers-color-scheme: dark)` for the system default, and
`:root[data-theme="dark"]` so an explicit toggle wins in either direction.

## Deploying with GitHub Pages

In the repository, go to **Settings → Pages**, set the source to the `main`
branch at `/ (root)`, and save. The page will be served at
`https://<username>.github.io/<repo>/`.
