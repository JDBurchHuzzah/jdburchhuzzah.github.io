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
- Shared navigation, header, footer: `_includes/`; visual refinements: `assets/site.css`.
- The dark Indigo foundation, Helvetica typography, and 810px column are preserved; the blue accents complement the updated headshot.

No analytics or third-party fundraising scripts are required to browse the site. Donations happen on the linked Tiltify campaign.

## Build scope

This branch contains only the current site: the homepage, About, Projects, Blog, fundraising hub, 404 page, and the five published articles. Legacy pages, unlinked downloads, unused images, optional theme features, and unused styling files have been removed. The remaining favicon, Apple touch icon, post images, and headshot are used by this build. Jekyll generates the RSS feed.

Keep generated `_site/`, installed dependencies, and local preview archives out of Git. The preview ZIP is a separate local deliverable.
