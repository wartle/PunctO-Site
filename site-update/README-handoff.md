# Puncto site — enhanced index page

Drop-in replacement for `index.html` in `wartle/PunctO-Site`.

## What to commit

- `index.html` — replaces the repo's index.html
- `assets/badge-app-store.svg`, `assets/badge-google-play.svg` — new
- `assets/app-logo.png`, `assets/puncto-icon-light.png` — new (used by the embedded app screens)
- `assets/wordmark.png`, `assets/icon.png` — unchanged, already in the repo

`styles.css`, `privacy.html`, `terms.html`, `support.html`, `robots.txt`, `sitemap.xml` and `og.png` are untouched. The new index carries its own styles inline and no longer needs `styles.css` — the legal and support pages still do, so leave the file in place.

## Still to wire

1. The two store badges and the hero/footer CTAs link to `#get`. Swap in the real App Store and Google Play URLs.
2. `privacy.html`, `terms.html` and `support.html` still use the previous header/hero styling. Bring them onto this shell if you want the set to match.
3. Update `sitemap.xml` with the final domain.
