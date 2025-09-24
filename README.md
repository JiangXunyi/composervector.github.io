# Composer Vector – GitHub Pages Demo

A minimal, clean template to host your **NeurIPS AI4Music** demo with audio samples, results, and BibTeX.

## Quick Start (GitHub Pages)

1. Create a repo (public is easiest).  
2. Upload the files in this folder to the repo root (or to `docs/`).
3. On GitHub: **Settings → Pages → Build and deployment**  
   - *Source*: `Deploy from a branch`  
   - *Branch*: `main` (root) **or** `main /docs` if you put files in `docs/`  
4. Wait ~1–2 minutes, then visit the URL shown under **Pages**.

> Tip: If you want this to live under a project site like `username.github.io/project`, put it in a repo named `project` and enable Pages for that repo.

## Replace Placeholders

- Put your audio in `assets/samples/` (WAV/MP3/OGG supported by the browser).  
- Update links in the header badges (`paper.pdf`, `code`).  
- Swap `assets/img/teaser.png` and `assets/img/method.png` with real figures.

## Suggested Sections
- Abstract (1 paragraph)
- Method (1 figure)
- Audio grid: Original / Steered / Mix
- Results: objective + subjective metrics
- BibTeX

## Notes
- Static HTML/CSS/JS only; no build system required.
- If files under folders starting with `_` don’t load, add a `.nojekyll` file.

© 2025 Composer Vector
