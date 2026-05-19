# CyberLens

Interactive cybersecurity education prototype — a visual, museum-style tour of passwords, hashing, encryption, phishing, public WiFi, digital footprints, and social engineering.

Built as a static site (HTML, CSS, JavaScript) for [GitHub Pages](https://pages.github.com/).

## Run locally

```bash
python -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000).

## Deploy on GitHub Pages

1. Create a repository named `cyberlens` (or your preferred name).
2. Push this folder to the `main` branch.
3. In the repo **Settings → Pages**, set **Source** to **Deploy from branch**, branch `main`, folder `/ (root)`.
4. Your site will be at `https://<username>.github.io/cyberlens/` (or your custom domain).

## Structure

- `index.html` — main museum lobby and inline exhibits
- `exhibit.html?topic=...` — deeper dives (`passwords`, `hashing`, `encryption`, `phishing`, `wifi`, `footprint`, `scenarios`)
- `base.css` — shared layout and typography
- `cyberlens.css` / `cyberlens.js` — CyberLens styling and interactions
- `cyberlens-exhibit.js` — dynamic exhibit detail pages
