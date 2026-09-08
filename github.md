repo: leahlay/sophie-portfolio
branch: main

site: https://sophiebydesign.com  (sophiestone.vercel.app 308-redirects here)

## Last sync
date: 2026-09-08T16:49:35Z

### Updated in this project
- Switched all URLs to the sophiebydesign.com custom domain; added rel="canonical" to all 7 pages
- Restored assets/jumpweg.jpg from the repo after a WebP naming collision; it is now assets/jumpwag.webp
- Fixed og:url on all 7 pages; added og:image, og:image:alt, twitter:card
- Renamed JumpWeg.dc.html → JumpWag.dc.html; vercel.json now routes /jumpwag with 301s from /jumpweg and /belavi
- About: counters carry real values (5 / 2 / 3) in markup; product-design figure 1.5 → 2 years; added Marketing Bunnies (2019–2021)
- All animation gated on prefers-reduced-motion; images converted to WebP (18.7 MB → 2.1 MB)

## Sync history
date: 2026-09-08T00:00:00Z
- Replaced assets/sophie-cv.pdf with the latest CV
- Resume links on all 7 pages point at assets/sophie-cv.pdf

date: 2026-08-25T12:56:02Z
commit: 3e19dc22ff2f
- Connected the Vercel project to the GitHub repo for auto-deploys
- Added vercel.json (root rewrite + clean URLs for each case study)
- Confirmed assets/ uploaded correctly (48 files); loose root-level image duplicates can be deleted

## Screen map
| Page | Files |
| --- | --- |
| Home / Portfolio | Portfolio.dc.html |
| About | About.dc.html |
| Bellavi | Bellavi.dc.html |
| Fanatix | Fanatix.dc.html |
| Fertitude | Fertitude.dc.html |
| JumpWag | JumpWag.dc.html |
| Sweatville | Sweatville.dc.html |
| Shared | support.js, image-slot.js, assets/, vercel.json, robots.txt, sitemap.xml |

## Upload notes
- Delete JumpWeg.dc.html from the repo (renamed to JumpWag.dc.html)
- Delete the 48 superseded .png/.jpg files in assets/ — replaced by .webp of the same name
- assets/jumpweg.jpg and assets/jumpweg.png are both gone; the card image is now assets/jumpwag.webp
- Keep assets/og-card.png as PNG (WebP is unreliable for link-preview scrapers)
- gemini_generated_image_*.jpg at the repo root is unused and can go
