# Xiao Yang's website

A static personal website for GitHub Pages. No build step, no hosting lock-in.

## Structure

- `index.html` - landing page with two doors
- `academic/` - research and collaboration version (a working-paper style page)
- `industry/` - startups and product-team version
- `boolean-network-data-analysis-tutorial.html`, `Three_node_exmaple.html` - standalone tutorial pages

Each version is one self-contained `index.html` (styles and scripts inline), so edit the file in the folder you want to change. Fonts load from Google Fonts.

## Preview locally

Open `index.html` in a browser, or serve the folder with any static server (for example `python -m http.server`).

## Publish

GitHub Pages: **Settings > Pages > Deploy from a branch > `main` / root**. Pushes to `main` go live within a minute or two.
