# guibrandao.github.io

Guilherme Brandão's academic homepage. Plain HTML/CSS, served by GitHub Pages at <https://guibrandao.github.io>.

## Structure

| Path | What |
|---|---|
| `index.html` | English page |
| `pt/index.html` | Portuguese page (paths use `../`) |
| `assets/css/style.css` | Shared styles (light/dark via `prefers-color-scheme`) |
| `assets/img/` | `photo.jpg` (400×400) and `unb-logo.svg` |
| `assets/cv/` | `cv-en.pdf`, `cv-pt.pdf` |
| `favicon.svg` | Tab icon |
| `.nojekyll` | Serve files as-is (no Jekyll build) |

Search for `TODO` to find placeholders. When you add a publication, add the same `<li>` to **both** pages.

## Preview locally

```sh
python3 -m http.server 8000
# open http://localhost:8000/ and http://localhost:8000/pt/
```

## Deploy

Push to `main`. In the repo's **Settings → Pages**, set Source to *Deploy from a branch*, branch `main`, folder `/ (root)`.
