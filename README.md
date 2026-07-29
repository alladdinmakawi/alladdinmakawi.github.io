# Alladdin Makawi, MD — professional website

This folder contains a static, GitHub Pages-compatible professional website for
Alladdin Yousif Makawi, MD. It is a local review draft and has not been
published or connected to a GitHub repository.

## Review locally

From this folder, run:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000` in a browser. Stop the local preview with
`Control-C`.

## Files used by the static site

- `index.html` — page content, metadata, and Person structured data
- `styles.css` — responsive layout and visual styling
- `public/alladdin-makawi-headshot.jpg` — professional portrait
- `public/alladdin-makawi-acc26-poster.jpg` — ACC.26 research photograph
- `public/favicon.svg` — browser icon
- `CNAME` — intended custom domain: `alladdinmakawi.com`
- `robots.txt` and `sitemap.xml` — search-engine discovery files
- `INSIGHTS_ARCHITECTURE.md` — reviewed plan for the first three substantive
  research and education pages; it is documentation, not a public page

The canonical URL, Open Graph URLs, sitemap, and structured-data URLs are
prepared for `https://alladdinmakawi.com/`. That address will not become active
unless the site is later published and the domain is configured.

## Publish later, only after approval

1. Create the public `alladdinmakawi.github.io` repository and upload only the
   static files listed above, preserving the `public` folder.
2. Enable GitHub Pages from the `main` branch and repository root.
3. Add and verify `alladdinmakawi.com` in the owning GitHub account before
   changing public DNS; retain GitHub's verification TXT record.
4. Point the apex domain to GitHub Pages and point `www` directly to
   `alladdinmakawi.github.io`. Remove conflicting records.
5. Wait for the domain check and TLS certificate, then enable **Enforce HTTPS**.
6. Confirm that the apex HTTPS URL, redirects, CSS, images, `robots.txt`, and
   `sitemap.xml` all work before submitting the site to search engines.
7. Verify the domain in Google Search Console, submit the sitemap, request
   homepage indexing once, and then import the verified property into Bing
   Webmaster Tools.
8. Add the live custom-domain URL to controlled professional profiles only
   after HTTPS is stable.
9. Recheck every title, biography statement, publication, profile link, and
   photograph before publication.

Nothing in this folder performs deployment or publishes content automatically.
