# Bayes — pilot onboarding page

Minimalist bilingual (EN/FR) landing page to onboard pilot partners interested in Bayesian modelling.

- `index.html` — the whole page (no build step). Language toggles EN/FR, auto-detects browser language, or force with `?lang=fr`.
- Set `CONTACT_EMAIL` near the top of the `<script>` in `index.html` to receive form responses (mailto, no backend).

## Hidden from search engines
- `<meta name="robots" content="noindex, nofollow, noarchive, nosnippet…">` (+ googlebot/bingbot)
- `robots.txt` disallows all crawlers
- No sitemap, no outbound links

Note: `robots.txt` blocks well-behaved crawlers from fetching the page, which also means they never see the `noindex` tag — a URL linked from elsewhere could still appear as a bare link. For strict privacy, share the URL only directly. To publish: Settings → Pages → deploy from `main` / root.
