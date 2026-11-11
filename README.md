# stevaoaa.github.io

[![Deploy](https://github.com/stevaoaa/stevaoaa.github.io/actions/workflows/pages.yml/badge.svg)](https://github.com/stevaoaa/stevaoaa.github.io/actions/workflows/pages.yml)
[![Site](https://img.shields.io/badge/site-stevaoaa.github.io-blue)](https://stevaoaa.github.io)

Personal website and blog of **Stevão Andrade**, a Senior Software Engineer and software testing specialist with a Ph.D. in Computer Science (USP).

🌐 **https://stevaoaa.github.io** · [About](https://stevaoaa.github.io/about/) · [Experience](https://stevaoaa.github.io/experience/) · [Publications](https://stevaoaa.github.io/publications/) · [CV (PDF)](https://stevaoaa.github.io/cv/cv-stevao.pdf)

## Stack

- [Jekyll](https://jekyllrb.com/) 4.4
- [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) theme
- GitHub Pages, deployed by [GitHub Actions](.github/workflows/pages.yml) on every push to `master`
- Dependabot for monthly gem and action updates

## Structure

```
├── _config.yml          # Site settings, author profile, links
├── _data/navigation.yml # Top navigation menu
├── _pages/              # About, Experience, Publications, archives, 404
├── _posts/              # Blog posts (YYYY-MM-DD-title.md)
├── _includes/           # Theme overrides (footer, favicons)
├── assets/images/       # Avatar and favicons
└── cv/cv-stevao.pdf     # CV (generated on Overleaf)
```

## Running locally

Requires Ruby 3.x and Bundler.

```sh
bundle install
bundle exec jekyll serve --livereload
# open http://localhost:4000
```

Or, without installing Ruby:

```sh
docker run --rm -it -p 4000:4000 -v "$PWD":/site -w /site ruby:3.4 \
  sh -c 'bundle install && bundle exec jekyll serve --host 0.0.0.0'
```

## Writing a post

Create `_posts/YYYY-MM-DD-my-title.md`:

```markdown
---
title: "My title"
categories:
  - blog
tags:
  - testing
---

Content in Markdown.
```

## Updating the CV

The CV's LaTeX source lives on **Overleaf**, which is the source of truth. This repo only stores the compiled PDF. To update it:

1. Download the PDF from Overleaf.
2. Replace `cv/cv-stevao.pdf` with it.
3. Commit and push. The site redeploys automatically.

## License

Content (text, CV, images) © Stevão Andrade. Theme by [Michael Rose](https://github.com/mmistakes/minimal-mistakes), MIT license.
