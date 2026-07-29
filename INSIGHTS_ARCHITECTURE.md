# Insights publishing architecture

This document describes the next three substantive pages for the professional
website of Alladdin Yousif Makawi, MD. These are not generic SEO pages or an
image dump. Each page should be an original, evidence-based professional
resource built around one coherent subject, one authentic lead image, and
relevant published work.

## Site structure

The current homepage remains the professional profile at:

- `https://alladdinmakawi.com/`

Add an Insights navigation item and a crawlable hub at:

- `https://alladdinmakawi.com/insights/`

The hub should introduce the purpose of the section, list the three pages
below, show each page's lead image and publication date, and link back to the
professional profile, publications, Google Scholar, and ORCID.

The first three page URLs should be:

1. `https://alladdinmakawi.com/insights/hypertension-screening-and-prevention/`
2. `https://alladdinmakawi.com/insights/equitable-clinical-trial-participation/`
3. `https://alladdinmakawi.com/insights/resident-ecg-burst-learning/`

Use stable, descriptive URLs and do not change them after launch.

## Page 1: Hypertension screening and prevention

Purpose: explain a practical, evidence-based approach to improving hypertension
recognition and prevention in routine care.

Suggested content:

- Why undiagnosed or undertreated hypertension remains important
- Practical opportunities for screening and follow-up
- Implementation barriers in real clinical settings
- How health equity affects detection and durable risk reduction
- A short "what clinicians and trainees can do" section
- Links to relevant peer-reviewed sources and any directly related work by
  Alladdin Yousif Makawi, MD

Lead image: an authentic clinical-research, teaching, or environmental portrait
that fits the subject. Do not use an unrelated stock photograph.

## Page 2: Equitable clinical-trial participation

Purpose: describe why inclusive cardiovascular research participation matters
and how workflow, communication, and digital support can make enrollment more
feasible.

Suggested content:

- Why representation affects the usefulness of clinical evidence
- Common participation and workflow barriers
- Practical design principles for equitable enrollment
- Lessons from implementation science and the TIDE-IM context
- A short section for resident investigators
- Links to relevant peer-reviewed sources and directly related publications

Lead image: an authentic research-team, conference, poster, or Morehouse
Clinical Research Center image with permission from everyone clearly
identifiable.

## Page 3: Resident ECG burst learning

Purpose: translate the published ECG curriculum work into a useful educational
resource for residents and educators without reproducing the published article.

Suggested content:

- The educational problem the curriculum addressed
- What "burst learning" means in this setting
- How concise repetition can support ECG confidence
- Practical considerations for implementing a similar curriculum
- Limits of the local quality-improvement experience
- A prominent link to the peer-reviewed publication

Lead image: an authentic teaching, podium, journal-club, or resident-education
photograph with permission from everyone clearly identifiable.

## Required page anatomy

Every insight page should include:

1. A unique title and plain-language summary
2. The exact author name `Alladdin Yousif Makawi, MD`
3. A visible publication date and, when applicable, updated date
4. One distinct lead image with a descriptive filename, accurate alt text, and
   visible caption
5. Approximately 800–1,200 words of original, useful content
6. Citations and direct links to primary research or authoritative guidance
7. A short author box linking to the homepage, Google Scholar, and ORCID
8. Contextual links to the other two insight pages
9. A brief disclosure that the page is educational and not individual medical
   advice

## Metadata and structured data

Each page should have its own:

- `<title>` and meta description
- Canonical URL
- `<meta name="robots" content="index, follow, max-image-preview:large">`
- Open Graph title, description, URL, and representative image
- `BlogPosting` JSON-LD with `headline`, `description`, `datePublished`,
  `dateModified`, `author`, `mainEntityOfPage`, `image`, and `about`
- `primaryImageOfPage` that points to the same lead-image `ImageObject`
- Breadcrumbs linking Home → Insights → Article

The `author` node should reference the same Person identity used on the
homepage: `https://alladdinmakawi.com/#alladdin-makawi`.

## Image and indexing workflow

For every approved image:

- Strip unnecessary EXIF and location metadata before publishing
- Use a descriptive filename based on the actual event or subject
- Publish the image beside text that genuinely explains its context
- Use the same absolute image URL in the page markup, Open Graph metadata,
  structured data, and sitemap
- Add the article URL and its lead image URL to `sitemap.xml`
- Link the article from the homepage and Insights hub so it is not orphaned

After a page is live over stable HTTPS, submit the updated sitemap in Google
Search Console and request indexing of the new page once. Do not create thin
pages, duplicate articles across domains, stuff names into captions, or publish
all three pages in one burst.

## Recommended release cadence

- Week 1: publish the Insights hub and the hypertension page
- Weeks 3–4: publish the equitable clinical-trial participation page
- Weeks 6–8: publish the resident ECG burst-learning page

This cadence gives each page time to be crawled, linked from established
professional profiles, and supported by one or two authentic public updates.
