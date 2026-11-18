# Anastasios Temenos — academic website

Professional website built with Academic Pages, Jekyll and GitHub Pages.

- Homepage: `_pages/home.html`
- Biography and interests: `_pages/about.md`
- Experience, education, teaching and awards: `_pages/cv.md`
- Contact and portrait settings: `_data/profile.yml`
- Funded projects: `_portfolio/*.md`
- Navigation: `_data/navigation.yml`
- Visual styling: `assets/css/profile.css`

See [the content and setup guide](docs/CONTENT_GUIDE.md) for the project schema,
logo and portrait replacement, conservative source-review decisions, exact local
setup commands and validation instructions.

```bash
bundle install
bundle exec jekyll build --strict_front_matter
bundle exec jekyll serve --host 127.0.0.1
```

Node-only source checks:

```bash
node scripts/check-content.cjs
node scripts/check-content.cjs --links
```

The private `TasosTemenos_website_content/` staging directory is ignored by Git and
excluded from Jekyll. Copy only curated public text and approved images into site
folders. Publications remain in their original collection; do not import BibTeX
without an explicit request. Research activity content is deferred.

Based on [Academic Pages](https://academicpages.github.io/) and
[Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/), under the
[MIT license](LICENSE).

Unused template examples, talk-map tooling, old CV-conversion tools, sample comments
and authors, theme preview screenshots and duplicate project logos have been removed.
The Jekyll theme, Docker preview configuration and publication tools are retained.
