# guziordo.github.io

Source for [guziordo.github.io](https://guziordo.github.io), the personal academic website of Doug Guzior.

Built with Jekyll from the [AcademicPages](https://github.com/academicpages/academicpages.github.io) template, a fork of the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) © 2016 Michael Rose, released under the MIT License (see [LICENSE](LICENSE)). Pushes to `master` are built and deployed by [.github/workflows/jekyll.yml](.github/workflows/jekyll.yml).

## Layout

- `_pages/` – top-level pages (About, CV, Publications, Talks, Teaching, Contact)
- `_publications/`, `_talks/`, `_teaching/`, `_reference/` – collection entries
- `files/` – downloadable PDFs (CV, papers)
- `markdown_generator/` – scripts that turn TSV/BibTeX into collection Markdown

## Local preview

```sh
bundle install
bundle exec jekyll serve --config _config.yml,_config.dev.yml
```
