# Shuxian Zou's academic website

Personal website built with Jekyll and hosted on GitHub Pages at [littletreezou.github.io](https://littletreezou.github.io).

## Update content

- `_pages/about.md`: homepage, research experience, teaching, and awards.
- `_pages/cv.md`: full CV page.
- `_includes/publication-list.md`: shared publication list used by the homepage, CV, and publications page.
- `files/Shuxian_Zou_CV.pdf`: downloadable CV.
- `_config.yml`: profile details, contact links, and site settings.
- `_data/navigation.yml`: navigation links.
- `images/ShuxianZou.png`: current profile photo and site icon.

The site keeps its theme layouts, styles, scripts, fonts, and personal photos. Template demo content and the old publication/talk generators have been removed.

## Preview locally

With Ruby and Bundler installed, run:

```sh
bundle install
bundle exec jekyll serve --config _config.yml,_config.dev.yml
```

Open `http://localhost:4000`. To check a production build:

```sh
bundle exec jekyll build
```

Build output, local dependencies, and caches are ignored by Git. Push changes to `master` to publish through GitHub Pages.

## Theme credits

Based on [AcademicPages](https://github.com/academicpages/academicpages.github.io), derived from [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes) by Michael Rose. The original theme license is retained in [LICENSE](LICENSE).
