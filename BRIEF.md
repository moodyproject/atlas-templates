# Caravan Uyghur Cuisine - Premium Restaurant Website

Build a single-page restaurant website that looks like a $15k agency build. This is a sales demo piece.

## Design Requirements
- DARK theme (deep blacks/charcoals with warm gold/amber accents)
- Full-screen hero section with parallax scrolling
- GSAP ScrollTrigger animations throughout (text reveals, fade-ups, image zooms, parallax layers)
- Smooth scrolling (use Lenis or CSS scroll-behavior)
- Large cinematic typography (mix of serif headlines + clean sans-serif body)
- Sections should pin and animate content in
- Horizontal scroll gallery for food photos
- Mobile responsive with touch-friendly animations

## Sections (in order)
1. **Hero** - Full viewport, restaurant name "CARAVAN" in massive type, tagline "A Taste of Kashgar in New York", subtle parallax background. Include a "Reserve a Table" CTA button.
2. **Story** - Split layout: text left, image right. Abdul Ahad Bakri's story of bringing Uyghur cuisine to NYC. Text reveals on scroll. "One of the first Uyghur restaurants in the bustling food scene of NYC."
3. **Menu Highlights** - 3-4 signature dishes with descriptions that animate in. Use cards or a staggered grid:
   - Big Plate Chicken (with hand-pulled noodles)
   - Lamb Kebabs (grilled to perfection, aromatic spices)
   - Uyghur Naan (sour, malty, dense and porous)
   - Polo (savoury rice dish with salad, Uyghur-style)
4. **Gallery** - Horizontal scroll or masonry grid with food/restaurant photos. Use placeholder images from unsplash (uyghur food, kebabs, noodles, restaurant interiors). Use specific unsplash URLs that work.
5. **Press** - "As featured in Eater NY" with a quote or badge. Simple, elegant.
6. **Location & Hours** - 60 Beaver St, Financial District, NYC. Include an embedded map or stylized address block. Hours can be placeholder.
7. **Footer** - Minimal. Phone, email, social links, "© 2026 Caravan Uyghur Cuisine"

## Tech Stack
- Pure HTML + CSS + JS (single index.html file is fine, or separate files)
- GSAP 3 + ScrollTrigger plugin (load from CDN)
- Lenis smooth scroll (CDN)
- Google Fonts: use something premium like "Playfair Display" for headlines + "Inter" for body
- All images from Unsplash (use direct URLs like https://images.unsplash.com/photo-XXXXX?w=1200)

## Vibe References
- Think: Nobu website meets awwwards restaurant winner
- Dark, moody, cinematic
- Every scroll should feel intentional
- White space is your friend
- Gold/amber accent color on dark background

## CRITICAL
- Must actually work when opened in a browser (no broken images, no missing CDN links)
- Test that GSAP animations fire correctly
- Mobile must look good (test at 375px width)
- Use real Unsplash image URLs that resolve (not placeholder.com)
- The site should make someone say "holy shit" when they scroll through it
