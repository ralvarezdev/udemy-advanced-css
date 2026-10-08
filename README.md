# udemy-advanced-css

Practice exercises and projects from Jonas Schmedtmann's advanced CSS and Sass course on Udemy.

**Note:** This repository is archived and read-only.

## Contents

- **`01-natours`** — "Natours" landing page: `index.html` styled with Sass in the 7-in-1 architecture (`sass/abstracts`, `base`, `components`, `layout`, `pages`, assembled by `sass/main.scss`), with images, a background video and the Linea icon font under `css/`.
- **`02-scss`** — small Sass playground: `index.html` and `style.scss`.

## Running

Each project has a `package.json` using [Parcel](https://parceljs.org/). Parcel is not listed as a dependency and versions are not pinned, so install it yourself.

```bash
cd 01-natours   # or 02-scss
npm install parcel sass
npm start       # parcel index.html
npm run build   # parcel build index.html --dist-dir ./dist
```

## License

GNU General Public License v3.0. See [LICENSE](LICENSE).
