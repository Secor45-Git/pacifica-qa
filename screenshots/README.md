# Visual QA — face-and-about-visual-qa-v6

Playwright full-page screenshots for the Matt-round build on
`Secor45-Git/pacifica` branch `feat/face-and-about-sections` (commit `96bdcc7`).

Captured against the production build (`next start`) with Playwright 1.60.0
(chromium), full-page, at two viewport widths.

| Page type | Route | 1440px | 390px |
|---|---|---|---|
| About | `/about` | `about-1440.png` | `about-390.png` |
| Surgery Center | `/about/surgery-center` | `surgery-center-1440.png` | `surgery-center-390.png` |
| Blog listing | `/blog` | `blog-1440.png` | `blog-390.png` |
| Blog post | `/blog/sun-skin-and-summer-what-southern-california-patients-need-to-know-after-surgery` | `blog-post-1440.png` | `blog-post-390.png` |

Notes:
- `/about` title updated to "Plastic Surgery & Med Spa | Camarillo & Studio City".
- `/about/surgery-center` shows the QUAD A logo integrated into the intro section.
- `/blog` lists all 181 ported WordPress posts.
- `/blog/[slug]` shows the rendered body + "Written By" Dr. Kolder block.
