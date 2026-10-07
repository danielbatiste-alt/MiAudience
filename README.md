# Milieu: MiAudience page mock

A front-end mock of the new MiAudience page (replacing [mili.eu/portraits](https://mili.eu/portraits/)),
built to sit seamlessly inside the live mili.eu site.

**This is a mock-up.** Copy is from the "Mi Audience_Webpage-2" doc and may still change.

## What's in it

- `index.html`: the page. Plain HTML, CSS and JS with no build step and no dependencies beyond the Archivo font from Google Fonts.
- `img/`: hero, USP 1 and USP 2 images (WebP, 4:3) and the Milieu logo.

## Design

All styles come from the live page's own CSS (`nav.css`, `pages.css` footer, `pv-portraits.css`):
Archivo, `#1A1A1A` hero, `#F1F1F1` / white alternating sections, `#0067C2` pill buttons and closing CTA, white footer.

## Page structure

1. Hero: "MiAudience (formerly Portraits)", "Audience intelligence, built for your market", stats Our own panel / Six Southeast Asian markets
2. Who is it for? Two cards: media and creative agencies, brands (light)
3. USP 1, Specialist modules (white, image)
4. USP 2, Follow-up surveys (light, image)
5. The Milieu Edge, 3 cards: media habits, six markets, ready 24/7 (white section, light grey cards)
6. FAQ, 5 questions (light)
7. Closing CTA (blue): "See what your audience watches, believes and buys. Market by market", with an Explore MiReports link
8. Footer

The client logo strip is removed for launch until client permissions are confirmed (its styles are kept in the file).

## Still to do before launch

- FAQ "Can I survey the people I find?": number of credits (marked `[Number]`)
- "Explore MiReports" link in the closing CTA is a placeholder (`href="#"`): add the URL once the first report is confirmed, or remove it
- Nav, footer and URL still say Portraits / `/portraits/`; these will be updated separately
