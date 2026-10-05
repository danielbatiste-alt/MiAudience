# Milieu: MiAudience page mock

A front-end mock of the new MiAudience page (replacing [mili.eu/portraits](https://mili.eu/portraits/)),
built to sit seamlessly inside the live mili.eu site.

**This is a mock-up.** Copy is from the "Mi Audience_Webpage" doc and may still change.

## What's in it

- `index.html`: the page. Plain HTML, CSS and JS with no build step and no dependencies beyond the Archivo font from Google Fonts.
- `img/`: the three current Portraits images (hero, USP 1, USP 2) and the Milieu logo.

## Design

All styles come from the live page's own CSS (`nav.css`, `pages.css` footer, `pv-portraits.css`):
Archivo, `#1A1A1A` hero, `#F1F1F1` / white alternating sections, `#0067C2` pill buttons and closing CTA, white footer.

## Page structure

1. Hero: "Real-time audience profiling on demand", stats 2M+ / 2,000+ / 4,000+
2. Logo strip
3. USP 1, Plug-and-play insight (light, current image)
4. USP 2, Always current (white, current image)
5. USP 3, Follow-up surveys (light, **image placeholder**) *new*
6. The Milieu Edge, 3 cards (white section, light grey cards)
7. FAQ, 5 questions (light)
8. Closing CTA (blue)
9. Footer

## Still to do before launch

- USP 3 image (4:3, same style as the other feature images)
- FAQ "What is MiAudience?": number of data points (marked `[number]`)
- FAQ "How often is the data refreshed?": refresh cadence answer
- Nav, footer and URL still say Portraits / `/portraits/`; these will be updated separately
