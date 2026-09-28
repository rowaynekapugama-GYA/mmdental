# M&M Dental Care – Marsden Park landing page

Static site, no build step. Deploy the folder root on Vercel/Netlify/GitHub Pages.

- `index.html` – landing page (all images inlined)
- `thank-you.html` – post-booking thank-you page (noindex); use as the conversion/redirect URL
- GTM hooks: `.js-call` (phone links) and `.js-book-online` (book buttons)
- Booking form: Centaur portal iframe loads inside a modal (opened by any Book button); src is set on first open
