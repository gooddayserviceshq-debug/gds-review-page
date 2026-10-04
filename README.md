# GDPW Review Page

Public hosting repo for the Good Day Pressure Washing (GDPW) review landing page, served by GitHub Pages.

- `index.html` — one-tap Google review page (source of truth: `reviews/review.html` in the private ops repo)
- `qr/` — QR codes pointing at the review link, hosted at stable URLs for print materials

Deploys automatically on every push to `main` via `.github/workflows/deploy-pages.yml`.
