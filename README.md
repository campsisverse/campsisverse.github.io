# campsisverse.github.io

[Go to Campsis website](https://campsisverse.github.io).

The site sources live in `Rmd/`. On every push to `main`, the GitHub Actions workflow
`.github/workflows/deploy.yml` renders the site with `rmarkdown::render_site("Rmd")`
and deploys it to GitHub Pages. Rendered HTML is not committed.

To preview locally, run `rmarkdown::render_site("Rmd")`; the output goes to `Rmd/_site/` (git-ignored).
