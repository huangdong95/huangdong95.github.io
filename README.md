# donghuang.github.io

Personal academic site, built with Jekyll and served by GitHub Pages.

## Editing

- **Bio / name / links** – `_config.yml` (the `author:` block) and the bio paragraph in `index.html`.
- **Papers** – add an entry to `_data/papers.yml`. Put PDFs in `assets/papers/`.
- **Headshot** – replace `assets/img/headshot.jpg`.
- **CV** – put it at `assets/cv.pdf`.
- **Styling** – `assets/css/style.css`.
- **New pages** – create e.g. `teaching.md` with `layout: default` front matter and link it from `_layouts/default.html`.

## Local preview

```powershell
bundle install          # first time only
bundle exec jekyll serve
```

Open http://localhost:4000. Edits rebuild automatically (restart after changing `_config.yml`).

## Deploy

Push to `main`. GitHub Pages builds and publishes automatically
(Settings → Pages → Deploy from branch `main`, folder `/`).
