Personal academic page of Qixiang Chen, served at https://q1xiangchen.github.io.

Forked (then detached) from [Stuart Geiger](https://github.com/staeiou)'s site, which is based on the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/), © 2016 Michael Rose, released under the MIT License.

- forked, edited & maintained: 08/12/2023
- released: 10/12/2023
- updated: 25/06/2025
- redesigned as a single page: 09/10/2026

## Layout

- `_pages/about.md` — the whole home page: bio, education, publications, projects (and the page's own styles and image-zoom script).
- `_config.yml` — site title, sidebar author info and links.
- `_data/navigation.yml` — top navigation bar entries (anchors into the home page).
- `images/works/` — work previews; `images/works/full/` — full-size versions opened on click.
- `files/` — PDFs linked from the page.

## Run locally

Needs Ruby 3.x (GitHub Pages' gems do not support Ruby 4 yet), e.g. `brew install ruby@3.4`.

```bash
export PATH="/opt/homebrew/opt/ruby@3.4/bin:$PATH"
bundle config set --local path vendor/bundle
bundle install
bundle exec jekyll serve --livereload --config _config.yml,_config.dev.yml
```

Then open http://localhost:4000.
