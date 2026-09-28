# davinhill.me

Personal website, built with [Jekyll](https://jekyllrb.com) on GitHub Pages and based on the [Jekyll Now](https://github.com/barryclark/jekyll-now) theme.

- `index.md`: bio and research interests
- `_data/publications.yml`: publication list (add new papers here)
- `_config.yml`: name, description, avatar, resume link, and header icon links
- `files/posters/`: posters, linked as `/files/posters/...` (the resume stays on Google Drive)
- `images/paper_thumbnails/`: publication thumbnails (resize to 420px wide, e.g. `sips --resampleWidth 420 thumb.png`)

## Local development

```bash
bundle install
bundle exec jekyll serve
```

Then open http://127.0.0.1:4000. Pushing to `master` redeploys the site.
