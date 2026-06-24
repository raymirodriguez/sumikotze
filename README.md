# Sumi Kotze — One-Page Site (Foundation)

Static, single-file foundation. No build step. Deploy by dragging this folder into
Netlify, or connect a repo.

## Structure
- index.html ............ the whole site (HTML + CSS + JS inline)
- assets/logo-dark.svg ... signature logo, charcoal (for light backgrounds)
- assets/logo-light.svg .. signature logo, beige (for dark backgrounds)
- assets/favicon.svg ..... SK monogram favicon

## Brand tokens (defined as CSS variables at the top of index.html)
- Warm beige  #EFE7DC   - Soft blush  #EBD4CC
- Dusty blush #C9A097   - Charcoal    #2A2A2E
- Fonts: Cormorant Garamond (display/serif) + Jost (utility/sans)

## Placeholders to replace next
1. Hero portrait — swap the `.hero-photo` gradient panel for a real image.
2. About copy — confirm Sumi's bio voice and details.
3. Offerings — real programs, pricing, links.
4. Testimonials — transcribe the screenshots into the three cards.
5. Journal — currently anchors to the testimonials block; wire to real posts.

## Contact form
The form is Netlify-ready (`data-netlify="true"` + honeypot). Submissions appear in
the Netlify dashboard once deployed. No backend needed.
