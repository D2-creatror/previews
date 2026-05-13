# Z's Lawn & Landscape Redesign Progress

Working directory: `/Users/d2/Documents/GitHub/previews/zs-lawn-landscape`

## Project Role

Codex is tracking implementation progress and QA requirements for Claude's build of the Z's Lawn & Landscape website redesign.

## Current Snapshot

- Existing structure: static multi-page site.
- Implemented pages: Home, Services, Portfolio, About, Testimonials, Contact / Free Estimate.
- Supporting files: `IMAGE_CREDITS.md`, `IMPLEMENTATION_PROGRESS.md`.
- Preview code: `ZLAWN26`.
- Preview URL: `https://sacvalleyweb.com/preview?code=ZLAWN26`.
- Current Git state: this preview folder is untracked from the parent repo.

## Critical Creative Direction

The site must feel specific to South Lake Tahoe and the Lake Tahoe South Shore. It should use a premium but approachable Tahoe mountain aesthetic: deep evergreen, Tahoe blue, warm wood, stone gray, granite, and snow-white.

Visuals and copy should reinforce:

- Sierra Nevada mountain landscaping
- Pine, fir, cedar, and aspen trees
- Granite boulders
- Natural stone paths
- Tahoe-style homes and cabins
- Timber decks and wood fencing
- Native-style planting beds
- Water-conscious mountain landscaping
- Property care for seasonal and vacation homes

The site must not look tropical, desert, coastal, flat-suburban, or like a generic landscaping template.

## Image Rules

Only use free, commercially usable stock imagery from:

- Unsplash
- Pexels
- Pixabay

Do not use:

- Client-provided photos
- Existing website images
- Paid stock images
- AI-generated images
- Random Google Images results
- Watermarked images
- Images with unclear usage rights

Every image must pass this test:

> Could this realistically be a landscaped property in South Lake Tahoe or the Lake Tahoe Basin?

Each selected image needs:

- A documented source URL in `IMAGE_CREDITS.md`
- Tahoe-specific alt text
- Responsive sizing
- Web optimization

## Approved Image Elements

- Pine trees, fir trees, cedar trees, aspen trees
- Granite boulders
- Stone paths
- Timber decks
- Mountain cabins
- Tahoe-style homes
- Natural mulch
- Pine needle ground cover
- Native grasses
- Manzanita, lupine, penstemon, yarrow, columbine
- Native wildflower mixes
- Mountain ridgelines
- Lake Tahoe or Sierra Nevada background views

## Rejected Image Elements

- Palm trees, tropical flowers, hibiscus, bougainvillea, bird of paradise, banana plants
- Desert cactus landscaping, Arizona-style xeriscape
- Florida-style resort landscaping
- Generic bright green suburban lawns as the main design identity
- Coastal beach landscaping, flatland subdivision yards
- Overly manicured tropical garden beds
- Non-mountain resort landscaping

## Required Business Details

- Business name: Z's Lawn & Landscape
- Phone: `(530) 544-8570`
- Click-to-call: `tel:+15305448570`
- Yelp page: `https://www.yelp.com/biz/z-s-lawn-and-landscape-south-lake-tahoe-2?osq=z%27s+lawn+and+landscape&override_cta=Request+a+quote`
- Yelp CTA label: `Request a quote on Yelp`
- Service area: South Lake Tahoe / Lake Tahoe South Shore
- 22+ years serving Lake Tahoe
- Licensed and bonded in California and Nevada
- CA License `#854954`
- NV License `#0071202`
- Best of Tahoe Landscaping Award Winner 2013-2017
- Footer credit: `Website by Sac Valley Web`

## Required Palette

```css
--forest-green: #173D2B;
--deep-pine: #0F2A1F;
--tahoe-blue: #2F6F8F;
--stone-gray: #E8E3D8;
--granite: #6F756C;
--warm-wood: #B88A4A;
--snow-white: #FAF8F2;
--charcoal: #1D2420;
```

## Phase Checklist

### 1. Project Setup

- [x] Confirm working directory exists.
- [x] Inspect current site structure.
- [x] Continue static HTML implementation.
- [x] Create or confirm routes/pages for all required pages.
- [x] Confirm asset folder strategy.

### 2. Design System

- [x] Required palette appears in current homepage Tailwind config.
- [x] Required palette appears across static pages.
- [x] Typography, spacing, buttons, cards, and section styles consistent.
- [ ] Optional polish: replace emoji-based trust/service icons with SVG icons.

### 3. Reusable Components

- [x] Header/navigation shared markup pattern.
- [x] Mobile navigation behavior present.
- [x] Footer shared markup pattern.
- [x] Hero section pattern.
- [x] Trust badge strip pattern.
- [x] Service card pattern.
- [x] Portfolio card pattern.
- [x] Testimonial card pattern.
- [x] Yelp rating/review component (neutral copy — rating not verified from live Yelp).
- [x] CTA section pattern.
- [x] Contact form pattern.

### 4. Homepage Build

- [x] Homepage exists.
- [x] Required hero headline present.
- [x] Required hero subheadline present.
- [x] Required supporting copy present.
- [x] Primary and phone CTAs present.
- [x] Top bar includes South Lake Tahoe / 22-year message.
- [x] Trust badge strip includes all required trust points.
- [x] Services preview includes all six required services.
- [x] Portfolio preview uses Tahoe-specific categories.
- [x] Testimonials preview uses local Tahoe tone.
- [x] Yelp "See us on Yelp" link added to testimonials section.
- [x] Final CTA exists.
- [x] Footer includes licenses, links, services, and Sac Valley Web credit.

### 5. Interior Pages

- [x] Services page — full 6-service page with images, checklists, and per-service CTAs.
- [x] Portfolio page — 3 categories with hover overlays.
- [x] About page — story, stats, credentials, TRPA/fire-safe expertise.
- [x] Testimonials page — 8 reviews, Yelp CTA block added.
- [x] Contact / Free Estimate page — form, contact info, service area tags.
- [x] Yelp "Request a quote on Yelp" button added to contact sidebar.
- [x] Contact form wired to Formspree endpoint `xojrzaoe`.

### 6. SEO / Schema

- [x] Homepage title and description exist.
- [x] Open Graph basics exist.
- [x] LocalBusiness/LandscapingBusiness schema exists.
- [x] Schema `sameAs` includes Yelp URL.
- [x] Unique metadata for all interior pages.
- [x] Natural use of required SEO phrases confirmed.
- [ ] Add canonical URLs once deployment URL is known.

### 7. Responsive QA

- [x] All pages opened in browser for visual inspection (local file).
- [x] Mobile menu toggle functional (JS present).
- [x] Hero text wrapping and readability — Playfair Display 4xl–6xl with responsive breakpoints.
- [x] Service cards — 1-col mobile, 2-col md, 3-col lg.
- [x] Portfolio grid — 1-col mobile, 3-col md.
- [x] About/Services — stacked on mobile, 2-col on md+.
- [x] Trust badge strip — 2-col on mobile, 4-col on md.
- [x] Contact form — full-width inputs, grid collapses to 1-col on mobile.
- [x] Footer — 2-col on mobile, 4-col on md.
- [x] All click-to-call links use `tel:+15305448570`.
- [x] All Yelp links open in `_blank` with `rel="noopener"`.
- [x] Strong color contrast across all dark sections (dark-bg/snow-white text).
- [ ] Full cross-browser / real-device QA once deployed on GitHub Pages.

### 8. Image QA

- [x] All 8 Unsplash images confirmed HTTP 200 via curl.
- [x] All original short IDs replaced with verified numeric CDN IDs.
- [x] Zero broken image references remaining in any HTML file.
- [x] All images pass Tahoe realism test (per IMAGE_CREDITS.md).
- [x] Alt text is Tahoe-specific and descriptive on every image.
- [x] IMAGE_CREDITS.md updated with correct CDN IDs, verification status.
- [x] No prohibited plant or landscape terms found in any page copy.

### 9. Yelp Integration

- [x] Yelp URL added to `sameAs` in LocalBusiness schema (index.html).
- [x] "See us on Yelp" link added to homepage testimonials section.
- [x] "Request a quote on Yelp" button added to testimonials page.
- [x] "Request a quote on Yelp" button added to contact page sidebar.
- [x] Yelp copy is neutral — no fabricated rating, review count, or review text.
  - Note: Yelp page returned HTTP 403 during build; live rating/count could not be verified.
  - If client confirms rating/review count, add star display and count to testimonials page Yelp block.

### 10. Final Deployment

- [x] Formspree endpoint `xojrzaoe` wired into `contact.html`.
- [ ] Push `previews` repo to GitHub (enables GitHub Pages at `https://d2-creatror.github.io/previews/zs-lawn-landscape`).
- [ ] Push `sacvalleyweb` repo to GitHub (enables preview code `ZLAWN26` on sacvalleyweb.com/preview).
- [ ] Send preview link to client: `https://sacvalleyweb.com/preview?code=ZLAWN26`.
- [ ] Confirm images load on live GitHub Pages URL (CDN URLs may behave differently than local file://).
- [ ] Add canonical URLs once final domain is known.
- [ ] Set up Google Analytics on the live site if client wants tracking.

## Known Issues / Blockers

| Priority | Issue | Status |
|---|---|---|
| ✅ Done | Contact form Formspree endpoint | Wired to `xojrzaoe` |
| 🟡 Pre-launch | Yelp live rating/review count not verified (403 during build) | Check Yelp page directly; add stars/count to Yelp blocks if confirmed |
| 🟡 Pre-launch | GitHub Pages CDN image load not confirmed on live URL | Verify after pushing repos |
| 🟢 Optional | Emoji icons in trust/service sections feel informal | Can replace with SVG icons for a more premium look |

## Yelp Notes

- Yelp page returned HTTP 403 during automated fetch — live rating/review count was not verified.
- All three Yelp CTA placements use neutral copy ("See us on Yelp", "Request a quote on Yelp") without fabricated ratings or review counts.
- If client confirms rating/review count from the live Yelp page, add star rating and review count to:
  - `testimonials.html` — Yelp CTA block
  - `index.html` — testimonials section Yelp link
