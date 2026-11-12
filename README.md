# martyniak.page

Personal landing page for [www.martyniak.page](https://www.martyniak.page) — a minimal page with links to GitHub and [octopusreferralcode.com](https://octopusreferralcode.com), over an animated server-rack background drawn in canvas (no images, no dependencies).

## Hosting (GitHub Pages)

1. Settings → Pages → Deploy from branch → `main` / root.
2. The `CNAME` file sets the custom domain to `www.martyniak.page`.
3. DNS (Squarespace):
   - `www` → CNAME → `mimikm.github.io`
   - apex `@` → A records `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
4. Once the certificate is issued, tick **Enforce HTTPS**.
