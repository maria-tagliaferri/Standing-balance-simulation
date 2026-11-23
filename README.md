# Project page

Website for "Learning Ankle Exoskeleton Control for Reactive Standing Balance Through Neuromusculoskeletal Simulation".

## Layout

- `index.html` — the whole page (styles and scripts are inline)
- `static/videos/` — the four comparison videos
- `static/images/` — paper figures (add these; see below)
- `.nojekyll` — tells GitHub Pages to serve the files as-is

## Adding the figures

Save the figures with these names and they appear automatically (until then the page shows a placeholder):

- `static/images/fig1_framework.png`
- `static/images/fig3_sim2real.png`
- `static/images/fig4_balance_outcomes.png`
- `static/images/fig5_recovery_strategy.png`

## Still to fill in (search for `TODO` in `index.html`)

- Paper, arXiv and Code links in the header
- BibTeX venue and year

## Publishing on GitHub Pages

1. Create a new public repository on GitHub and upload the contents of this folder to it (so `index.html` is at the top level).
2. In the repository, go to Settings → Pages, set Source to "Deploy from a branch", pick the `main` branch and `/ (root)`, and save.
3. The site appears at `https://<username>.github.io/<repository>/` after a minute or two.
