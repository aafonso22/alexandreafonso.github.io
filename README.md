# alexandreafonso.github.io

Personal academic website of Alexandre Afonso, built with Hugo, PaperMod and Pascal Michaillat's hugo-website template (MIT licence).

- Edit content in `content/` (papers in `content/papers/pNN/index.md`), settings in `config.yml`.
- Preview locally: `hugo server`, then open http://localhost:1313/alexandreafonso.github.io/
- Publishing: pushing to `master` triggers the GitHub Action in `.github/workflows/hugo.yml`, which builds and deploys to GitHub Pages (enable Pages > Source: GitHub Actions in the repository settings).
