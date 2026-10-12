# Sweet Crumbs Bakery — multi-page website demo

A responsive frontend-only bakery demo built with semantic HTML, CSS and vanilla JavaScript. Open `index.html` in a browser or serve this directory with any static web server.

## Pages
- `index.html` — home, category cards, featured bakes, story, testimonials, gallery and demo newsletter.
- `shop.html` — searchable 18-item catalogue with category, price and sorting filters.
- `product.html` — reusable product details (`?id=...`) with quantity, size, related items and WhatsApp enquiry.
- `about.html` — bakery story, mission and values.
- `contact.html` — demo contact details and validated frontend-only form.
- `cart.html` — localStorage cart, quantity updates/removal, totals and WhatsApp order text.

## Configuration before presenting or publishing
- Replace `BAKERY_WHATSAPP_NUMBER` in `js/main.js` with the client's international-format digits-only number. It is intentionally a placeholder (`923000000000`), not a real bakery number.
- Replace all sample prices, product/catalog data, address, phone, opening hours, social handles, testimonials and email in `js/products.js`, `js/main.js` and the page markup.
- The contact and newsletter forms are frontend demos; no messages or email addresses are transmitted or stored.
- Product imagery and fonts are remote Unsplash/Google Fonts resources and require an internet connection.

## Publish / deploy
This is a static website and can be published on GitHub Pages, Netlify, Cloudflare Pages, or any ordinary web host. Upload the contents of this folder as the site root. No build step or backend is required. Test the published URL on mobile and desktop, and replace demo details before sharing with a bakery client.