# Crystal News Network

Crystal News Network (CNN), the national news channel for the Republic of Amplon.

Live at https://spollenjack.github.io/Crystal-News-Network/

## How it works

- Single-page site in `index.html`, hosted on GitHub Pages
- Stories are stored in Supabase (`articles` table)
- The newest 25 stories keep their images; older ones are archived and their images removed
- Browser tab and iPhone home screen icons are embedded in `index.html`
- Full past editions are kept as ZIP files in the Archive Google Drive folder

## Files

| File | What it is |
| --- | --- |
| `index.html` | The whole site |
| `manifest.json` | Home screen / app install settings |
| `icon-192.png`, `icon-512.png` | Android home screen icons (used by `manifest.json`) and the link preview image |
| `sitemap.xml` | Sitemap for Google Search Console |
| `google8519a84a3a3e45cc.html` | Google Search Console verification, don't delete |
