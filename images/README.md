# Images — what to drop in here

Placeholder images are in place so the local preview renders. Replace each
with the real file, **keeping the exact filename** (the HTML, Open Graph
tags, and JSON-LD schema all reference these names).

| File | Used on | Specs |
|---|---|---|
| `omar-bahhur.jpg` | Home hero, OG/Twitter image, JSON-LD schema | Main portrait. ~1200px long edge, WebP or quality-80 JPG, aim < 150 KB. Square-ish crop works best (displayed 200×200 on home). |
| `omar-bahhur-about.jpg` | About page | Casual/contextual shot. ~1200px wide (16:9 looks best), < 200 KB. |
| `project-1.png` / `project-2.png` / `project-3.png` | Project cards | Screenshots, 1200×675 (16:9), < 150 KB each. |

Compression tips: export as WebP where possible (rename references in HTML
from .jpg/.png to .webp if you do), or run JPGs through Squoosh/ImageOptim
at quality ~80. Every photo of you should keep "Omar Bahhur" in the alt
text — already set in the HTML.
