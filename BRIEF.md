# Mrs. DoubtHire — Design Brief

## Brand Synopsis
**Mrs. DoubtHire** is a concept brand: a drag-queen luxury taxi / party-transport service in Palm Springs, CA. The name is a playful parody pun (we deliberately use **zero** Robin Williams / Mrs. Doubtfire character likeness — the joke lives entirely in the wordplay, keeping us clear of trademark/likeness issues). The positioning: "Palm Springs' Fabulous Drag Taxi" — the driver *is* the entertainment. Target use cases lean into what's already huge in Palm Springs: bachelorette parties, bar crawls (Arenas District), drag bingo nights, and showgirl photo cruises.

The visual world is unapologetically glam: mid-century Palm Springs neon, hot pink + black + gold, lashes & lips iconography, checkerboard taxi motifs, and desert-sunset palettes. Fun, camp, premium.

This was built in **IMAGE FORGE MODE** (branding proof of concept) and extended into a **BLAST** landing page to assemble everything into a live one-pager.

## Brand System (locked)
- **Primary mark**: Lips & Lashes Badge (`logo-2`) — gold ring, glossy pink lips under gold lashes. Scales to app icon, car decal, merch, favicon.
- **Wordmark**: Mid-Century Script (`logo-4`) — coral cursive "Mrs. DoubtHire".
- **Ad / hero aesthetic**: Neon Marquee (`logo-1`) — Palm Springs motel-sign neon treatment.
- **Accent motif**: hot-pink/black checkerboard stripe (from `logo-3`).
- **Campaign line**: **"HIRE THE MRS."** / *Palm Springs' Fabulous Drag Taxi*

## Design Decisions (landing page)
- **Mood**: Camp luxury, desert nightlife, main-character energy.
- **Fonts**: Bebas Neue (display) + Sacramento (script accents) + Poppins (body). Google Fonts.
- **Colors**: Ink `#0B0A0C` · Hot pink `#FF2E93` / `#FF5FB0` · Gold `#E7B24C` · Teal `#25D8C8` · Cream `#FAF1E4`.
- **Layout**: Full-bleed cinematic hero, alternating timeline for "the night," glass package cards, neon CTA.
- **Signature moves**: Neon text-glow on headlines, scrolling pink marquee, hot-pink/black checker dividers.
- **Animation**: IntersectionObserver scroll-reveals, CSS marquee, sticky nav background-on-scroll, image hover-zoom. All content visible by default (iOS-safe).

## Asset Inventory (15 keepers — see IMAGE_LOG.md)
- **Logos (4)**: neon marquee, lips-lashes badge ⭐, checkered taxi, mid-century script ⭐
- **Fleet (3)**: pink Sprinter van, coral '59 convertible, neon nightlife SUV (one palette each, unified branding)
- **Scenes (4)**: golden-hour pickup → convertible cruise → club arrival → van after-party
- **Collateral (4)**: Instagram poster, packages card, business card mockup, bachelorette merch flat-lay

All images generated via the tier pipeline (Grok Tier 1 for photoreal scenes; Gemini Nano Banana Pro for all text-bearing logos/collateral/vehicles; one NB2 escalation on scene 4). **Total spend ~$1.68** of a $5 campaign cap.

## Share Preview
- **OG image source**: `hero-a-goldenhour-clean.jpg` (dedicated editorial desert hero) cropped to 1200×630.
- **OG title**: "Mrs. DoubtHire — Palm Springs' Fabulous Drag Taxi"
- **OG description**: "Bachelorettes, bar crawls, drag bingo & showgirl cruises — chauffeured in heels through Palm Springs."
- **Favicon source**: lips-lashes badge (`logo-2`), scaled to 512×512.
- **Theme color**: `#0B0A0C`

## ⚠️ Placeholders to confirm before any real use
This is a **concept** — the following are invented and must be replaced with real data:
- **Pricing**: $399 / $299 / $89 / $149 are illustrative only.
- **Phone**: (760) 555-DRAG is a placeholder.
- **Handle / domain**: @mrsdoubthire / mrsdoubthire.com are placeholders (check availability).
- **Service area**: Palm Springs · Cathedral City · Rancho Mirage · Palm Desert — assumed.
- Legal note: confirm trademark availability of "Mrs. DoubtHire"; the parody framing avoids the film likeness but the name should be cleared.

## Suggested Next Mockups
- Booking flow (date/package picker → quote)
- Per-package detail pages
- "Meet the Queens" roster page (driver profiles)
- Gift-card / merch shop
- Animated reel from the 4 night-phase scenes for IG/TikTok

## Production Notes
To build this for real: a simple booking/lead-capture (Calendly or a custom form → SMS), real photography of the actual fleet/queens to replace concept imagery, and a CMS-light stack (Astro or Next.js) if it grows past one page. The vanilla HTML here is the interim GitHub Pages representation.
