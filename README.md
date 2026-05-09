# jensmueller.io

Personal website and blog of Jens Müller, built with [Quarto](https://quarto.org/) and published to [jensmueller.io](https://www.jensmueller.io) via GitHub Pages.

## Structure

- `index.qmd` — landing page (about / bio)
- `blog/` — blog posts, one folder per post
- `projects/` — project pages
- `impressum/` — legal notice
- `html/` — shared templates and styles (SCSS, listing template)
- `img/` — images and assets
- `_quarto.yml` — site-wide Quarto config

## Local development

Requires [Quarto](https://quarto.org/docs/get-started/).

```bash
# Live preview at http://localhost:22222
quarto preview

# Render to ./_site
quarto render
```

## Publishing

Configured to publish to the `gh-pages` branch:

```bash
quarto publish gh-pages
```

## Credits

Site template adapted from [Marvin Schmitt](https://marvinschmitt.com/); blog listing based on [Andrew Heiss](https://www.andrewheiss.com/). Both shared under CC-BY-SA 4.0.
