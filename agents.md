# Working on this site

Treino PRO: a single-page workout tracker. Everything (HTML, CSS, JS) lives in
`index.html`. There is no build step, no package manager, and no framework.

## Rules

- Do not add a `package.json`, a lockfile, or a `netlify.toml` with a `[build]`
  section. The folder is published exactly as it is.
- Keep `index.html` at the root.
- The UI is in Portuguese (pt-PT); keep new text in Portuguese.
- Workout data is stored in `localStorage` (keys ending in `App` for the current
  session, `historicoTreino` for history). Do not rename these keys, or existing
  users lose their history.
- External runtime dependencies are intentional: Google Fonts (Inter), Chart.js
  from jsDelivr, and YouTube embeds for exercise videos.
- `favicon.svg` is XML: a comment inside it can never contain two hyphens in a row.
