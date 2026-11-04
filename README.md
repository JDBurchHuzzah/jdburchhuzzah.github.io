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
- Campaign naming: **JD Burch for St. Jude** is the campaign name for every year. **Marching for St. Jude** is the theme of the 2025 and 2026 campaigns only; `_data/campaigns.yml` keeps the campaign title and theme separate.
- Fundraising hub: `st-jude.html`; annual figures and stories: `_data/campaigns.yml`.
- The completed 2026 campaign raised **$3,100.12** against a $3,000 goal, verified on Tiltify. The lifetime total for **2022–2026 is $10,191.77**. Keep homepage, About, Projects, hub, and campaign data in sync when adding results.
- Writing: `_posts/`. Existing article URLs are retained.
- Résumé page and PDF are removed for now.
- Shared navigation, header, footer: `_includes/`; visual refinements: `assets/site.css`.
- The original dark Indigo palette, Helvetica typography, portrait, and 810px column are preserved.

No analytics or third-party fundraising scripts are required to browse the site. Donations happen on the linked Tiltify campaign.
