# Project: Yotsuba Clovers Official Website

This is the single authoritative project specification for the Yotsuba Clovers official website.

## Background

Yotsuba Clovers is an eBay business specializing in Japanese Printed & Recorded Heritage collectibles.

Main categories include:

- Weekly Shonen Jump
- Vintage Manga
- Anime Magazines
- Japanese Music Magazines
- Catalogs
- Art Books
- Books
- Exhibition Catalogs
- Music CDs
- SHM-CD
- SACD
- Blu-ray
- DVD
- LaserDisc

The website is hosted on GitHub Pages.

Future integrations:

- Pinterest API
- Instagram
- Shopify
- Custom Domain

Pinterest API Trial status: Pending

Previous Pinterest review issues:

- eBay URL was used instead of an owned website.
- Privacy Policy returned 404.

These issues have now been resolved.

## Brand

Brand: Yotsuba Clovers

Tagline: Japanese Printed & Recorded Heritage

Platform: Powered by BRIdGE

## Logo

Use `assets/logo.png` as the official four-leaf clover brand logo.

Apply it to:

- Header
- Footer
- About page
- Favicon

Theme colors:

- Deep Green
- Antique Gold
- Ivory
- Dark Gray

## Design Goal

Create a premium collector-oriented website.

Target audience:

- Western collectors
- Vintage magazine collectors
- Japanese print culture enthusiasts
- Japanese recorded media collectors
- Music, film, anime, manga, and physical edition collectors

The atmosphere should be:

- Elegant
- Trustworthy
- Museum-quality
- Japanese
- Collector-focused

## Current Website Architecture

The website uses static HTML and CSS for GitHub Pages compatibility.

Core files:

- `index.html`
- `about.html`
- `collector-resources.html`
- `why-collect-japanese-printed-culture.html`
- `contact.html`
- `privacy.html`
- `style.css`
- `robots.txt`
- `sitemap.xml`

Core assets:

- `assets/logo.png`
- `assets/hero-printed-culture.png`

Historical Version 2 baseline files:

- `index.html`
- `about.html`
- `contact.html`
- `privacy.html`
- `collector-resources.html`
- `style.css`
- `robots.txt`
- `sitemap.xml`

## Content Requirements

Home:

- Hero section
- Japanese Printed & Recorded Heritage
- Brand introduction
- Brand story
- Featured Collections
- Featured Discoveries
- Collector Trust
- Collector Journal placeholder
- Shopify Online Store placeholder
- Instagram placeholder

Featured Collections:

- Books & Magazines
- Music
- Movies
- Art & Exhibition Catalogs
- Manga & Anime
- Collector Resources

About:

- Our Mission
- Collector Philosophy
- Authenticity
- Worldwide Shipping
- Powered by BRIdGE

Collector Resources:

- What is an Obi Strip?
- Understanding First Press CDs
- What is SHM-CD?
- Japanese Blu-ray Editions
- LaserDisc Collecting
- Magazine Grading
- Catalog Collecting
- Art Book Collecting

Educational cornerstone page:

- Why Collect Japanese Printed & Recorded Heritage?
- Japanese magazine culture
- Manga history
- Music magazines
- Catalogs
- Art books
- Why collectors value original Japanese editions
- Edo-period publishing history
- Terakoya and shijuku
- Kashihon rental bookshops
- Ukiyo-e
- Newspapers and early magazines
- Japanese music media
- Optical media
- Physical collector editions

Contact:

- Working FormSubmit contact form delivering to `yotsubaclovers.japan@gmail.com`
- Name, email, subject, inquiry type, and message fields
- Success page for submitted contact messages
- Spam protection through FormSubmit and a hidden honeypot field
- Supported inquiry types:
  - Business Inquiries
  - Collector Questions
  - Partnerships
  - Press
  - Rare Item Requests
- Pinterest placeholder
- Instagram placeholder
- GitHub placeholder
- Shopify Online Store placeholder

SEO scope includes:

- Japanese Printed Heritage
- Japanese Recorded Media
- Japanese Publishing History
- Japanese Music Media
- Japanese Collector Editions
- Japanese Blu-ray
- Japanese CDs
- Japanese Magazines

Privacy:

- Readable, accessible privacy policy layout
- Must remain available to avoid marketplace and API review issues

## SEO Requirements

Implement and maintain:

- Page titles
- Meta descriptions
- Open Graph metadata
- Twitter Cards
- Canonical URLs
- Schema.org JSON-LD
- Sitemap coverage

## Responsive Requirements

Support:

- Desktop
- Tablet
- Mobile

## Technical Requirements

- GitHub Pages compatible
- HTML + CSS + minimal JavaScript
- Semantic HTML
- Clean, maintainable CSS
- No frameworks unless explicitly approved
- Preserve the premium museum-quality visual identity unless explicitly instructed otherwise

## Documentation Requirements

Before making project changes, read:

- `PROJECT_BRIEF.md`
- `VERSION3_REQUEST.md`
- `CHANGELOG.md`

When completing a feature, update `CHANGELOG.md` without removing previous history.

After every completed feature:

1. Update `CHANGELOG.md`.
2. Commit with a meaningful message.
3. Push to GitHub.
4. Verify GitHub Pages deployment.
5. Report the deployment URL and latest commit hash.

`PROJECT_BRIEF.md` is the only authoritative project brief. Older duplicate brief files must not remain active in the project after their unique information has been merged here.

This documentation set is the authoritative source of truth for Version 4, Version 5, and later updates.
