---
layout: plain
sitemap: false
---

# CHANGELOG
{:.no_toc}

* this list will be replaced by the toc
{:toc .large-only}

## v0.0.1
Mar 09 2026
{:.heading.post-date}

### Site Foundation
- Initial Hydejack PRO setup with gem-based theme (`jekyll-theme-hydejack ~> 9.1`)
- Custom domain configured at kyleobrien.me
- Dark mode enabled (dynamic OS preference + icon toggle)
- KaTeX math rendering via `kramdown-math-katex`
- LSI-powered related posts via `classifier-reborn`

### Content
- Migrated archived posts from Ghost
- Published posts: Dreaming in Code, Waking Software Engineering, AI Ethics, Time Management, Software Development Life Cycle, I'm Trans, 黒春光琳海
- About page and Constellations (external links) page
- Category page for Code; tag pages for 9 tags

### Infrastructure
- GitHub Actions deploy pipeline (`.github/workflows/jekyll.yml`)
- CI with html-proofer on PRs (`.github/workflows/ci.yml`)
- Dependabot for GitHub Actions and Bundler
- Cloudflare email protection integration via `_includes/my-body.html`

### Cleanup
- Removed Hydejack starter kit boilerplate (`docs/`, unused includes)
- Replaced starter kit README with project-specific documentation
