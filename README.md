# AI Horizons Society — starter site (draft)

One static page: `index.html`, no build step. Status: **LIVE at https://aihorizonssociety.org since 2026-11-15** (complete content, indexable).

## Facts used (all verified)
- Delaware nonprofit, active / good standing (Bizee, 2026-11-15)
- Meets once a month

Everything else is a yellow dashed placeholder awaiting Blake: mission, audience,
meeting when/where/who, what happens at meetings, contact email or sign-up link,
optional "Founded by Blake Ruwali" credit. No donate button (501(c)(3) status unknown).

## Hosting plan (nothing done yet — each step needs Blake's OK in chat)
1. **Now, free:** new public repo `blakeruwali/ai-horizons-society`, GitHub Pages from `main`
   → `https://blakeruwali.github.io/ai-horizons-society/`. Same setup as blakeruwali.com.
2. **Later, custom domain:** Blake picks/buys one, add a `CNAME` file + DNS records
   (4 GitHub A records or a CNAME to `blakeruwali.github.io`), enable HTTPS in Pages settings.
3. Before going live: remove the draft banner and `noindex`, fill or delete every placeholder.
4. Then link the `card nolink` AI Horizons Society card in blakeruwali.com `i18n/template.html` to the URL.

## Screenshots
`screenshots/desktop.png` (1440 wide), `screenshots/mobile.jpg` (375 wide, top of page).

## Logo (approved by Blake 2026-11-15)
Concept A "Sunrise": sun on the horizon, three rays ending in nodes. Colors: ink #14213d, sun #c2541b, paper #f7f4ee.
`logos/sunrise-lockup-{light,dark}.svg` (full logo), `logos/sunrise-mark-{light,dark}.svg` (mark only), `logos/favicon.svg` (tab icon, adapts to dark mode).
Lockup text uses live fonts (Fraunces/Inter); outline it before print or Canva use. `logos/concepts.html` keeps the 4 explored directions.

## Live setup (2026-11-15)
- Hosting: GitHub Pages from `main` of blakeruwali/ai-horizons-society, HTTPS enforced. `_config.yml` keeps README, screenshots and logo working files unpublished.
- Domain: aihorizonssociety.org at Cloudflare Registrar (renews $11.20/yr). DNS: 4 GitHub A records + `www` CNAME, all DNS-only (not proxied).
- Email: Cloudflare Email Routing, hello@aihorizonssociety.org forwards to blakeruwali@hometsair.com; catch-all off. Receive-only; to reply as hello@, add a Gmail "Send mail as" alias.
- SEO: robots.txt, sitemap.xml, canonical, Open Graph image (og-image.png), schema.org NGO JSON-LD.
- Content source: Blake's answers 2026-11-15 (mission, audience, meeting format, contact, founder credit). Nothing invented: no programs, outcomes, testimonials or donations.
