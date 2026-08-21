# 9TechAgency Website

Marketing site for 9TechAgency. Plain static HTML/CSS/JS — no build step, no framework.

## Files

| Path | What it is |
|---|---|
| `index.html` | The whole site (single page) |
| `styles.css` | All styling, dark theme using the brand tokens |
| `script.js` | Scroll reveal + small interactions |
| `assets/` | Logos (SVG), favicons (PNG), animated logo (`logo-sting.mp4`) |
| `vercel.json` | Clean URLs + cache headers for assets |

## How it deploys

This repo is connected to the Vercel project **9-tech-agency-website**
(team: 9TechAgency Team).

Any push to the `main` branch automatically builds and deploys to production at
<https://9-tech-agency-website.vercel.app>.

There is no build command — Vercel serves the files at the repo root as-is.

## Making a change

1. Edit the file (usually `index.html` for copy, `styles.css` for looks).
2. Commit and push to `main`.
3. Vercel deploys automatically in about 30 seconds.

## Things that still need doing

- Attach the custom domain `9techagency.com` in Vercel:
  Project Settings → Domains → Add, then add the DNS records Vercel gives you
  at the domain registrar.
- Pricing/CTA for the "Web & Custom Apps" and "Ongoing Care & Growth" cards
  (only "Business Websites" has a price and a Stripe deposit button today).
- Phone number, if one should be public.
- Testimonials / case studies — none on the site, none invented.
