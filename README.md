# Connecticut Ave Dental Studio

Marketing website for Connecticut Ave Dental Studio, a dental practice in Washington DC.

**Live:** [asquitt.github.io](https://asquitt.github.io)

## Tech Stack

| Component | Technology |
|-----------|-----------|
| Static Site Generator | Jekyll |
| Hosting | GitHub Pages |
| Fonts | Inter, Playfair Display (Google Fonts) |
| Icons | Font Awesome 6 |
| Maps | Google Maps Embed API |
| SEO | Schema.org JSON-LD, jekyll-seo-tag |

## Pages

- **Homepage** (`index.html`) — Hero, services overview, testimonials, contact with embedded map
- **Teeth Whitening** (`teeth-whitening.html`) — Professional whitening services
- **Orthodontics** (`orthodontics.html`) — Braces and alignment treatments
- **Dental Implants** (`dental-implants.html`) — Implant restoration procedures
- **Blog** (`blog.html`) — Jekyll-powered blog with 3 published posts

## Local Development

```bash
# Serve locally with live reload
jekyll serve --livereload

# Or just open the HTML files directly
open index.html
```

No build step required. Push to `main` to auto-deploy via GitHub Pages.

## SEO Features

- Google Site Verification meta tag
- Schema.org JSON-LD (Dentist entity with address, hours, coordinates)
- robots.txt with AI crawler policy (allows GPTBot, Claude-Web, PerplexityBot)
- Sitemap.xml
- Responsive meta descriptions per page

## Design

- **Color palette:** Navy primary (`#1a365d`), teal secondary (`#0d9488`), gold accents
- **Typography:** Playfair Display (headings), Inter (body)
- **Responsive:** CSS Grid layouts with mobile hamburger menu
- **Performance:** Async font loading, LCP hero image preloading

## Project Structure

```
asquitt.github.io/
├── _config.yml              # Jekyll config
├── _layouts/post.html       # Blog post template
├── _posts/                  # Blog posts (Markdown)
├── index.html               # Homepage
├── teeth-whitening.html     # Service page
├── orthodontics.html        # Service page
├── dental-implants.html     # Service page
├── blog.html                # Blog listing
├── robots.txt               # Crawler rules
└── sitemap.xml              # URL sitemap
```
