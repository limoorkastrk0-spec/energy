# Coin Strike — GitHub Pages

Complete English static website. No npm, backend or build step.

Upload all contents of this folder (including `.nojekyll`) to the root of the existing `energy` repository. Enable Pages from main / root. Replace old files with these files; the public base URL stays https://limoorkastrk0-spec.github.io/energy/.

## Pages

- index.html — Coin Strike homepage
- how-to-play.html — controls and ten paylines
- free-spins.html — three-coin trigger, scatter payouts and retriggers
- symbols-and-paytable.html — eleven symbols and exact line multipliers
- rewards.html — the reward economy of this package
- faq.html — local progress and purchase support
- privacy.html — local wallet, existing Google Play and Firebase integrations
- hold-and-win.html — immediate HTML redirect to the new free-spin guide, excluded from sitemap
- 404.html — missing-page fallback, excluded from sitemap

Google Play package: com.fallowmint.harvesttrolley. Support: limoor.kastrk0@gmail.com. The logo is supplied artwork. Screenshots are captured from the rebranded app on a physical Xiaomi; example bonus/winning states are labelled illustrative.

Canonical URLs, social metadata, structured data and sitemap use the existing /energy/ address. The supplied Google verification tag is retained in index.html. After deployment, submit https://limoorkastrk0-spec.github.io/energy/sitemap.xml in Search Console and request recrawling of changed pages. Update any bookmarks from hold-and-win.html to free-spins.html. GitHub Pages cannot provide a custom per-path HTTP 301 here, so the old bonus address uses a zero-delay HTML redirect and destination canonical.

The site has no analytics, cookies, external fonts or browser storage. JavaScript only enhances the screenshot dialog. All guide content and links work without it. No robots.txt is needed at /energy/: crawlers look at the domain root.

Local preview: python3 -m http.server 8776 --bind 127.0.0.1 --directory site_app (from the parent directory).

Validation and screenshots are in ../qa/coin-strike/. Static checker: python3 qa/coin-strike/check_site.py. The site's rules describe this rebranded package, whose bet levels, coin packs and rewards remain compatible with its previous release; they are not a copy of a different Coin Strike application's economy.

This folder is prepared locally. Deployment, Search Console ownership verification, indexing and Google Play publication are external steps. No ranking promises or artificial reviews are included.
