# AerialDojo-200K

**A Large-Scale Benchmark Suite for Open-World Aerial Object-Goal Search**

[Project website](./index.html)

This repository hosts the paper's project website, including the overview,
construction procedure, dataset statistics, unified benchmark, interactive
leaderboard, simulator scene gallery, and citation.

## Run locally

```sh
python -m http.server 8765
```

Open <http://localhost:8765/>. The website is static and needs no build step.
Images and fonts are bundled locally.

## Update the website

- `index.html`: page content and figures.
- `styles.css` and `fonts.css`: layout, theme, and fonts.
- `script.js`: leaderboard data, filters, and gallery interactions.
- `resource-links.js`: review-safe resource links.
- `assets/`: figures, scene previews, downloadable figure PDFs, result CSV, and BibTeX.

Identity-revealing resource links are disabled for anonymous review.
The internal leaderboard remains available. The Demo section contains
the approved 60-second video; its AR overlays are illustrative annotations,
not a recording of live model predictions.

GitHub Pages serves the root directory of the `main` branch. `.nojekyll`
keeps the site as plain static files.

## Attribution

Paper content and original figures belong to their respective authors.
The Sensors and Action Space illustrations were generated for this project page.
Bundled font licenses are included in `assets/fonts/`.
