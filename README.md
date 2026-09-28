# M&M Dental Care – Marsden Park landing page

Static site, no build step. Deploy the folder root on Vercel/Netlify/GitHub Pages.

- `index.html` – landing page (all images inlined)
- `thank-you.html` – post-booking thank-you page (noindex); use as the conversion/redirect URL
- GTM hooks: `.js-call` (phone links) and `.js-book-online` (book buttons)
- Booking form: Centaur portal iframe embedded in the `#book` section under the banner; every Book button scrolls to it
