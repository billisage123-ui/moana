# Moana Beach Bar

Single-page website for Moana Beach Bar — Φανάρι, Παραλία Αρωγής, Αρωγή 691 00, Greece.
Live at https://moanaseaside.com

## Structure
- `index.html` — the site
- `media/` — hero video (mp4 + webm), poster image, mobile hero image, title graphic
- `CNAME` — custom domain for GitHub Pages
- `robots.txt` / `sitemap.xml` — search engine crawler files

## Hosting on GitHub Pages
1. Upload every file in this folder to the repo root, keeping `media/` as a subfolder.
2. Settings > Pages > Source: `main` branch, root folder.
3. Custom domain is handled by the included `CNAME` file.
4. DNS at your registrar: four A records (@ -> 185.199.108-111.153) and one CNAME (www -> <username>.github.io).
5. Once DNS resolves, enable "Enforce HTTPS" in Settings > Pages.

## After going live
- Submit the site to Google Search Console and add the sitemap URL there.
