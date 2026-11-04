# JD Burch’s personal website

Jekyll site based on Indigo, hosted on GitHub Pages at https://jdburch.com.

## Local development

With Ruby and Bundler installed:

```sh
bundle install
bundle exec jekyll serve
```

Open http://localhost:4000. Build without the server using `bundle exec jekyll build`.

## Editing

- Homepage: `index.html`; About: `about.md`; Projects: `projects.html`.
- Fundraising hub: `st-jude.html`; annual figures and stories: `_data/campaigns.yml`.
- Historical total on the homepage and hub covers **2022–2025 only**. Update both when adding a confirmed annual result. The 2026 campaign links out for its latest total.
- Writing: `_posts/`. Existing article URLs are retained.
- Résumé: replace `assets/Resume.pdf` with a current PDF.
- Shared navigation, header, footer: `_includes/`; visual refinements: `assets/site.css`.
- The original dark Indigo palette, Helvetica typography, portrait, and 810px column are preserved.

No analytics or third-party fundraising scripts are required to browse the site. Donations happen on the linked Tiltify campaign.
