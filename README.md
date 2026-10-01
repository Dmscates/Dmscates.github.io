# Daniel Scates Website Builder

## Preview locally

```bash
quarto preview
```

## Render the site

```bash
quarto render
```

Quarto writes the finished HTML to `docs/`. Open `docs/index.html` to inspect the rendered starter.

## Publish with GitHub Pages

The simplest route is **Settings → Pages → Deploy from a branch → `main` → `/docs`**. Commit the rendered `docs/` folder whenever you update the site.

For automatic rendering, choose **GitHub Actions** as the Pages source instead; `.github/workflows/publish.yml` renders and deploys the site on every push to `main`.

