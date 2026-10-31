# Hearth website

The public product website for Hearth, a homeowner app in development.

**Website:** https://joshginz.github.io/Hearth-Website/

## Publish

GitHub Pages publishes the `docs/` folder on the `main` branch. Updates committed to that folder deploy automatically. The `.nojekyll` file keeps this a plain static website; no build tools or dependencies are required.

## Local preview

Run `python -m http.server 4178 --directory docs` from this repository, then open http://localhost:4178/.

## Content

- Product introduction, About, Help & FAQs, and a website privacy notice.
- A custom 404 page with an absolute base URL so links work for nested missing paths.
- Responsive layouts, semantic headings, keyboard focus, and reduced-motion support.
- All illustrations and styles are local. No tracking scripts, contact forms, account sign-in, or payments.

This website announces a product in development. Final app privacy/terms, operational support/deletion contacts, and store download links are separate launch work. Do not publish internal legal drafts or claim verified company registration without confirming the facts.

## Custom domain

The initial site uses the GitHub Pages address above. A custom domain is not configured. Before connecting one, confirm ownership, save the existing DNS records, and preserve mail records. Then update canonical URLs, the sitemap, robots.txt, and the 404 page's base URL to match.

GitHub's [Pages publishing documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site) describes the branch and folder settings.
