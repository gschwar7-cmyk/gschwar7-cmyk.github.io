# Gerald Schwarz — portfolio

A lightweight, responsive portfolio built with plain HTML, CSS, and JavaScript.
The page markup, styles, and interactive behavior are kept in separate files
for easier maintenance and browser caching.

## GitHub Pages

The site lives in [`docs/`](docs/):

- [`index.html`](docs/index.html) — page content and metadata
- [`game-development.html`](docs/game-development.html) — game development projects
- [`mechanical-design.html`](docs/mechanical-design.html) — mechanical design interests
- [`styles.css`](docs/styles.css) — layout, theme, and responsive styles
- [`script.js`](docs/script.js) — mobile navigation and current-year display

In the repository's **Settings → Pages**, publish from the `main` branch and
select the `/docs` folder. If Pages is instead configured to publish from the
repository root, [`index.html`](index.html) forwards visitors to the same site.

## Local preview

Open `docs/index.html` in a browser, or serve the repository with any static
file server.