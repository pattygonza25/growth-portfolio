# Bdoors.us — B2B Digital Growth Architecture

> European interior doors · South Florida · B2B (Architects, Designers, Contractors, Developers, Hospitality)

## Overview

End-to-end digital growth system for a European interior door supplier operating in the South Florida B2B market. The project covered full website restructure, SEO architecture, segmented lead capture, and CRM integration — built to support Google Ads campaigns targeting 5 distinct professional segments.

**Stack:** WordPress · Elementor · Contact Form 7 · HubSpot CRM · Rank Math · Cloudflare Turnstile · Google Search Console

---

## Problem

The existing website had no growth infrastructure in place:

- Inconsistent visual identity — no design system, no brand coherence
- Vague content with no clear B2B value proposition
- Poorly structured URLs with no SEO architecture
- No differentiated product pages per collection
- No blog or content strategy to build organic authority
- Generic contact form with no lead segmentation — sales had no visibility into who was contacting them or why
- No CRM integration — leads managed manually with no pipeline structure

---

## Solution

### 1. Website Redesign & Visual System
Rebuilt the site on WordPress + Elementor with a consistent design system: Raleway 300/400, brand palette (`#8B0000` red, `#222222` titles, `#F0EBE3` sand), and standardized section structure across all pages.

### 2. SEO Architecture
- Restructured all URLs following SEO best practices
- Title tags, meta descriptions, and canonical URLs configured via Rank Math Advanced on all 19 pages
- XML sitemap generated and submitted to Google Search Console
- 301 redirects configured for legacy URLs
- Internal linking strategy across product pages and blog

### 3. Product Pages (3)
One page per collection, each with targeted local keywords:

| Collection | URL | Stock |
|------------|-----|-------|
| Lacquered Interior Doors | `/lacquered-interior-doors/` | In stock · Miami |
| Wood Veneer Doors | `/wood-veneer-doors-miami/` | Made to order |
| Laminated Doors | `/laminated-doors-miami/` | Made to order |

### 4. SEO Content — Industry Guides (7 articles)
Technical blog targeting long-tail B2B keywords. Each article structured with H1/H2 hierarchy, internal links to product pages, and local Miami/South Florida keyword targeting.

| Article | Target Keyword |
|---------|---------------|
| What Is a Frameless Interior Door? | frameless interior doors Miami |
| How to Read a Door Schedule | door schedule south florida |
| 7 Mistakes When Buying Interior Doors | modern interior doors Miami |
| Professional Door Installation South Florida | interior door installation south florida |
| Wood Veneer vs Lacquered — Which Is Right? | wood veneer vs lacquered doors Miami |
| How to Specify Doors for a Hotel Renovation | hotel interior doors south florida |
| Interior Door Trends Miami 2026 | luxury interior doors Miami 2026 |

### 5. Segmented Lead Capture — 5 Landing Pages
One landing page per target segment, each with:
- Elementor Canvas template (no header/footer) — optimized for Google Ads
- Contact Form 7 with a **hidden segment field** that auto-tags the lead on submission
- HTML confirmation email to the lead with catalogue CTA
- Internal notification to sales with segment included

| Segment | URL | Hidden Field Value |
|---------|-----|--------------------|
| Architects | `/interior-doors-architects/` | `Architect` |
| Interior Designers | `/interior-doors-interior-designers/` | `Interior Designer` |
| Contractors | `/interior-doors-contractors/` | `Contractor` |
| Real Estate Developers | `/interior-doors-real-estate-developers/` | `Real Estate Developer` |
| Hospitality | `/hotel-interior-doors/` | `Hospitality` |

### 6. HubSpot CRM Integration
- HubSpot plugin connected to WordPress
- Custom `Segment` property created in HubSpot Contacts
- All form submissions sync automatically to HubSpot
- Sales pipeline structured: New → Contacted → Proposal → Close
- `Discuss Your Project` page includes dropdown "I am a..." for organic traffic self-identification

### 7. Anti-spam & Security
- Cloudflare Turnstile configured on all CF7 forms (replaces reCAPTCHA)
- "Enable on all CF7 Forms" — no manual shortcode required

---

## Key Design Decisions

**Hidden segment field vs. dropdown on landing pages** — Shorter form = higher conversion. The segment is captured automatically based on which landing page the lead arrived from. The dropdown is reserved for the general contact page where the traffic source is unknown.

**URLs without "miami" in landing pages** — Avoided geo-locking the pages to a single city, keeping them viable for broader South Florida targeting in Google Ads.

**CF7 over HubSpot native forms** — HubSpot free plan does not allow custom field mapping for non-HubSpot forms, and native HubSpot forms include branding that conflicts with the premium B2B positioning. CF7 with HubSpot plugin provides cleaner UX and full design control.

**7 blog articles before Google Ads launch** — Built topical authority in Google's eyes before paid traffic arrives, so organic and paid reinforce each other.

---

## Status

| Area | Status |
|------|--------|
| Website redesign | ✅ Live |
| Product pages (3) | ✅ Live |
| Industry Guides (7) | ✅ Live |
| Landing pages (5) | ✅ Live |
| HubSpot CRM | ✅ Connected |
| Google Search Console | ✅ Sitemap submitted |
| Google Business Profile | 🔄 Verification in progress |
| Google Ads (5 campaigns) | ⏳ Launching after GBP verification |

---

## Results — Month 1 (Feb 27 – Mar 26, 2026)

> All results achieved organically — Google Ads campaigns not yet launched.

### Technical Performance (Google Lighthouse)

| Metric | Mobile | Desktop |
|--------|--------|---------|
| Performance | 59 | 85 |
| Best Practices | 100 | 100 |
| SEO | 100 | 100 |
| Accessibility | 88 | 79 |

*Mobile performance impacted by uncompressed images (882 pending ShortPixel compression). Desktop score already strong.*

### Traffic & Engagement (Google Analytics)

| Metric | Value |
|--------|-------|
| Active users | 78 |
| New users | 78 (100% new audience) |
| Avg. engagement time | 22s |
| Total events | 579 |

**Top pages by engagement:**

| Page | Views | Bounce Rate |
|------|-------|-------------|
| Homepage | 57 | 53.8% |
| Discuss Your Project | 27 | 33.3% ✅ |
| Interior Doors for Interior Designers | 11 | 25.0% ✅ |
| Lacquered Interior Doors | 11 | 25.0% ✅ |
| Projects | 10 | 50.0% |
| Laminated Interior Doors | 9 | 25.0% ✅ |
| Wood Veneer Interior Doors | 8 | 37.5% ✅ |

**Traffic sources — 0 paid media active:**

| Source | Users |
|--------|-------|
| Direct | 42 |
| Google organic | 11 |
| Yahoo organic | 9 |
| Instagram / social | 6 |
| Facebook referral | 5 |
| Instagram referral | 2 |

### Key observations
- Google organic traffic appearing within weeks of launch — before any paid campaigns
- "Discuss Your Project" conversion page at 33.3% bounce rate — strong signal of qualified intent
- All product pages under 40% bounce rate — content resonating with B2B audience
- Instagram generating referral traffic immediately after bio optimization
- 0 paid media spend during this entire period

### Next milestone
Google Ads launch (5 segmented campaigns) pending Google Business Profile verification. Results to be updated post-launch.

---

## Live Site

[bdoors.us](https://bdoors.us)
