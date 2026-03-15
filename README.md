# Site Structure

This repository is a Jekyll site for `https://kettlecornwitha-QU.github.io`.

## Layout

- `index.markdown`, `about.markdown`, `404.html`: top-level site entry pages
- `articles/`: long-form article source pages
- `projects/`: "about this project" pages for linked apps
- `papers/`: downloadable PDF versions of the articles
- `assets/`: styles, JavaScript, fonts, and images
- `_layouts/`, `_sass/`, `_posts/`: standard Jekyll site structure

## Notes

- Article and project pages use explicit `permalink` values so their public URLs stay unchanged even though the source files are now organized into folders.
- `_site/` and other Jekyll build artifacts should stay untracked.
