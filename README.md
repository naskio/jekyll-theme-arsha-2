# jekyll-theme-arsha-2

## Install (locally)

```shell
bundle install
```

## Run (locally)

```shell
bundle exec jekyll serve --config _config.yml,_config.development.yml
```

## Upgrading

- `assets/js` => `assets/js`
- `assets/img/*` => `assets/img/*`
- `assets/vendor/*` => `assets/vendor/*`
- `assets/css/style.css` => `_sass/styles.scss`, `_sass/colors.scss`, `assets/css/sass.scss`
- `index.html` => `index.html`, `_includes/`
- `portfolio-details.html` => `_layouts/post.html`
- `inner-page.html` => `_layouts/page.html`
