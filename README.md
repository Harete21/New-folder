Siya's Chillers — Project Changelog

This README lists changes made for Part 3 (interactive features, forms, SEO and submission).

## Changelog (Part 3 updates)

- 2026-10-15: Added core client-side JavaScript and interactive features
  - Added `js/main.js` — handles: dynamic footer year, mobile nav toggle, booking form submission simulation, contact form mailto compilation, gallery lightbox, menu search & sort, and Leaflet map initialization.

- 2026-10-15: Styling updates
  - Updated `css/style.css` to include styles for the lightbox, accordion, menu controls, map container, and simple transitions.

- 2026-10-15: Contact & enquiry pages
  - Updated `contact.html`: replaced embedded Google iframe with an interactive Leaflet map container, added a general message form (`#contact-form`) with mailto fallback, and included Leaflet assets.
  - Added `enquiry.html`: a purpose-built enquiry form for services, products, volunteering and sponsorship with client-side estimate response.

- 2026-10-15: Gallery improvements
  - `gallery.html` now connects to the lightbox UI; clicking images opens a fullscreen viewer (lightbox).

- 2026-10-15: Menu search and sort
  - `menu.html` gained client-side `menu-search` and `menu-sort` controls. Items are filtered live and can be sorted by price.

- 2026-10-15: SEO & technical files
  - Added `robots.txt` and `sitemap.xml` (update `sitemap.xml` host URLs to match your live site).

## Notes & Next Steps

- Testing: Open `index.html`, `menu.html`, `gallery.html` and `contact.html` locally in a browser to interact with features.
- The Leaflet map uses OpenStreetMap tiles; it requires network access. Adjust coordinates in `js/main.js` if needed.
- Replace the placeholder URLs in `sitemap.xml` with your GitHub Pages or hosted site URLs before publishing.

