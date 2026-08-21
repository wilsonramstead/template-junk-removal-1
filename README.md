# Junk Removal Website Template

A junk removal and hauling website template by **Wilson Innovations** — a single-page marketing site for junk haulers, cleanout crews and debris removal businesses.

- **Build:** self-contained `index.html` — inline CSS + minimal JS, works from `file://` and with JS disabled. Local photos live in `assets/`.
- **Status:** ships with a `noindex` robots meta (remove it when a client site goes live).
- **Fictional placeholder brand:** "Loadout Junk Removal" serving the Tampa Bay Area. Swap the business name, phone, service area, reviews, and photos for the real client before launch.

## Sections

- Sticky header with brand mark and a click-to-call button
- Full-bleed photo hero with slow Ken Burns zoom, slate overlay, text-a-photo and call CTAs, and rating chips
- Hazard-stripe accent bands between sections
- Trust strip (star rating, same-day service, service area, family owned)
- "Text a photo, get a quote" hook with a three-step how-it-works list
- Services grid (furniture & appliance removal, garage & property cleanouts, same-day hauling, clean finish)
- "Why us" checklist band (family owned, always on time, quick to respond, accommodating)
- Six-card review grid on dark slate, with the last card as a highlight panel
- "Our work" four-photo gallery with a placeholder-imagery note
- Big call-to-action band with the phone number set large, then the footer

## Design

- **Palette:** near-black slate (`#20262F`) + raised slate panels + bold hauler orange (`#FF5A1F` / deep `#E1430F`) on white and soft off-white (`#F6F5F2`) / warm tint (`#FCEDE5`) bands.
- **Fonts:** Patua One (slab display) + Mulish (body).
- **Motifs:** diagonal hazard-stripe dividers, box-truck logo mark, sheen sweep across primary buttons, orange glow shadows.
- IntersectionObserver fade-ins with staggered delays respect reduced motion. MovingCompany JSON-LD with `areaServed` (no street address). AA contrast, focus states, lazy-loaded below-fold images. SMS-first CTAs throughout.

## Customizing for a client

1. Replace brand name, phone (`tel:` / `sms:` links), and service area.
2. Rewrite the placeholder reviews with the client's real testimonials.
3. Swap the photos in `assets/` (hero, service, work-gallery and OG preview) for the crew's own job pictures.
4. Update the JSON-LD business data and Open Graph / social tags.
5. Remove the `noindex` robots meta + comment when going live.

Website by Wilson Innovations — https://wilsoninnovations.net
