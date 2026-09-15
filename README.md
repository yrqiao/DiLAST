# DiLAST

Project page for **DiLAST**.

Based on the [nerfies](https://github.com/nerfies/nerfies.github.io) project page template
(CC BY-SA 4.0).

## Deploying with GitHub Pages

Settings → Pages → Source: `Deploy from a branch` → Branch: `main` / `root`.
The page will then be served at `https://<user>.github.io/<repo>/`.

## What to edit

Everything you need to change in `index.html` is marked with a `TODO` comment:

- `<head>`: title, description, keywords, favicon
- Hero: paper title, venue, authors + their links, affiliations
- Link buttons: paper, arXiv, code, dataset (delete the ones you do not need)
- Teaser, Abstract, Motivation, Pipeline, Results, More Results sections
- BibTeX block

Drop your own assets into `static/images/` and `static/videos/`, then replace the
`placeholder.png` / `placeholder.mp4` references. Delete the placeholders when you are done.

Tip: keep the videos small (e.g. `ffmpeg -i in.mp4 -vf scale=640:-2 -crf 28 out.mp4`);
GitHub Pages has to serve them on every page load.
