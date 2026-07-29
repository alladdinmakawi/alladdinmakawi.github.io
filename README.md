# Alladdin Makawi, MD — professional website

This folder contains the maintained static, GitHub Pages-compatible professional
website for Alladdin Yousif Makawi, MD. GitHub Pages is live at
`https://alladdinmakawi.github.io/`. The custom domain is not yet registered or
connected.

## Review locally

From this folder, run:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000` in a browser. Stop the local preview with
`Control-C`.

## Files used by the static site

- `index.html` — page content, metadata, and Person structured data
- `insights/index.html` — crawlable Insights hub
- `insights/hypertension-screening-and-prevention/index.html` — first
  evidence-based article
- `presentations/index.html` — staged research-presentation page with four
  contextual professional images
- `leadership-and-teaching/index.html` — staged leadership and teaching page
  with the 2025 Morehouse GME commencement and Complex Clinical Cases images
- `styles.css` — responsive layout and visual styling
- `public/alladdin-makawi-headshot.jpg` — professional portrait
- `public/alladdin-makawi-acc26-poster.jpg` — ACC.26 research photograph
- `public/favicon.svg` — browser icon
- `CNAME` — intended custom domain: `alladdinmakawi.com`
- `robots.txt` and `sitemap.xml` — search-engine discovery files
- `INSIGHTS_ARCHITECTURE.md` — reviewed plan for the first three substantive
  research and education pages; it is documentation, not a public page

The canonical URL, Open Graph URLs, sitemap, and structured-data URLs are
prepared for `https://alladdinmakawi.com/`. Until that domain is registered and
configured, the public GitHub Pages site remains accessible but its preferred
canonical URL does not resolve.

## Production launch

1. Upload the reviewed source state to the public `alladdinmakawi.github.io`
   repository, preserving the `public` and `insights` folders.
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

Nothing in this folder performs deployment automatically.
