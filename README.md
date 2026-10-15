# Cavern Gauge — mobile (HSVC LPG caverns TK-3301 / TK-3401)

Mobile version of Cavern Volume Gauge 4.1: same conversion tables (C3 Rev.1, C4 Rev.2) and the same calculation
(M = G × VCF × (D15 − 0.0011), as the PMS). Screens: Stock · Level A → B · Pump plan · Table lookup · Density.
Languages EN / VI / KO, dark / light theme, works offline after the first visit, can be added to the home screen.

## Deploy on GitHub Pages
1. Create a repository (e.g. `cavern-gauge`) and upload ALL files of this folder to the repository root:
   `index.html, manifest.webmanifest, sw.js, icon.svg, icon-180.png, icon-192.png, icon-512.png`.
2. Settings → Pages → Source: "Deploy from a branch" → branch `main`, folder `/ (root)` → Save.
3. After ~1 minute open `https://<user>.github.io/cavern-gauge/`.
4. On the phone: Safari → Share → "Add to Home Screen" (iPhone) or Chrome → ⋮ → "Install app" (Android).

## Updating
After changing `index.html`, change `VERSION` in `sw.js` (e.g. `cvgm-2026-10-20a`) so phones load the new version.

Note: the repository is public on a free GitHub plan — the page contains cavern tables and alarm set points.
