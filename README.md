# Wild Roots Field Guide

A sample field guide (brochure-style, multi-page static site) built for a course project showcasing
plant knowledge for a plant identification app. Built with plain HTML/CSS/JS so it can be hosted for
free on GitHub Pages with no build step.

## Structure

```
index.html          Home / cover page with links to all 4 species
species-1.html       Species entry template (repeat structure for 2–4)
species-2.html
species-3.html
species-4.html
family-tree.html     "Family tree" infographic relating the 4 species
references.html      Running references list, organized by species
css/style.css        Shared stylesheet
js/main.js           Mobile nav toggle + active-link highlighting
images/               Add photos/diagrams here
```

Each species page follows the required entry format:

- Common name & scientific name, biome & region
- **A.** Identifying features (leaf shape/arrangement, bark, flowers/fruits/cones)
- **B.** Habitat & range (current + historical/native)
- **C.** Four aspects of biology & ecology: photosynthetic pathway, resource acquisition
  strategy, reproductive strategy, and species interactions
- Per-species reference list (mirrors the master list in `references.html`)

## Editing

All content is plain HTML — open any `species-N.html` file and replace the bracketed placeholder
text (e.g., `[Common Name]`, `[Genus species]`) with real content. Add photos/diagrams to `images/`
and swap the `.hero-image` / `.diagram-placeholder` blocks for `<img>` tags.

## Running locally

No build step required. Either:

- Open `index.html` directly in a browser, or
- Serve the folder locally, e.g. `npx serve .` or `python -m http.server`, then visit the printed URL.

## Deploying to GitHub Pages

1. Push this repo to GitHub.
2. In the repo settings, go to **Pages** → set source to the `main` branch, root folder.
3. Your site will be published at `https://<username>.github.io/<repo-name>/`.
