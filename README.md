# Hearth website

The public product website for Hearth, a homeowner app in development.

**Website:** https://hearthhomehealth.com/

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

The website targets `hearthhomehealth.com`, the domain registered through Squarespace Domains. `docs/CNAME` declares that domain for GitHub Pages. Canonical URLs, the sitemap, robots.txt, and the 404 page's base URL use `https://hearthhomehealth.com/`.

The domain connection requires GitHub Pages settings, Squarespace DNS records, and an issued HTTPS certificate. These source changes do not establish that DNS propagation or HTTPS verification has completed. Preserve existing mail and authentication records when updating website DNS.

GitHub's [Pages publishing documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site) describes the branch and folder settings.
