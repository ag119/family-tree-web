# Family Tree — invite landing site

Static pages served via GitHub Pages at
`https://ag119.github.io/family-tree-web/`.

- `/i/?c=<code>` — invite landing. Opens the app if installed, otherwise sends
  the visitor to Google Play with the invite code attached as the install
  referrer.
- `/` — general "get the app" page.
- `/privacy.html` — privacy policy.
- `/.well-known/assetlinks.json` — Android App Links (takes effect once served
  from a domain root).

Enable hosting: **Settings → Pages → Deploy from a branch → `main` / `/root`**.
