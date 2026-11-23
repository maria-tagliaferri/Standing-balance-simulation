# Project page

Website for "Learning Ankle Exoskeleton Control for Reactive Standing Balance Through Neuromusculoskeletal Simulation".

## Layout

- `index.html` — the whole page (styles and scripts are inline)
- `static/videos/` — the four comparison videos
- `static/images/` — paper figures (add these; see below)
- `.nojekyll` — tells GitHub Pages to serve the files as-is

## Figures

The five paper figures are in `static/images/` (`fig1_framework.png` to `fig5_recovery_strategy.png`). To update one, replace the file under the same name.

## Still to fill in (search for `TODO` in `index.html`)

- Code link in the header
- BibTeX venue once the paper is published

## Publishing on GitHub Pages

1. Create a new public repository on GitHub and upload the contents of this folder to it (so `index.html` is at the top level).
2. In the repository, go to Settings → Pages, set Source to "Deploy from a branch", pick the `main` branch and `/ (root)`, and save.
3. The site appears at `https://<username>.github.io/<repository>/` after a minute or two.
