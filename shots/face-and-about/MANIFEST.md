# Visual QA v3 — feat/face-and-about-sections @ db92161

Captured with Playwright (Chromium) against a local production build (`next build && next start`).
Full-page PNGs at viewport **1440** (desktop) and **390** (mobile), plus interaction states.

| Shot | Viewports | Matt item(s) evidenced |
|---|---|---|
| `about-aesthetic-nurses` | 1440, 390 | 7 — rectangular 4:5 portraits at ~2× |
| `about-financing` | 1440, 390 | 8 — sized-up pre-qualify buttons |
| `about-financing-cherry-payment-plans` | 1440, 390 | 9 — no hero/intro, enlarged Cherry widget |
| `facelift` (rhytidectomy-facelift, closed) | 1440, 390 | 12 (closed), 6 (FAQ left-align), 5 (sage bullets on light + dark sections), 4 (gold links on dark) |
| `about-surgery-center` | 1440, 390 | 5 (sage bullets light + dark), QUAD A text sections (item 10 context) |
| `facelift-video-lightbox-open` | 1440, 390 | 12 — in-page video lightbox OPEN |
| `nav-megamenu-open` | 1440 | 3 — desktop grouped mega-menu OPEN (Face/Breast/Body) |
| `nav-mobile-drawer-expanded` | 390 | 3 — mobile drawer, Plastic Surgery section expanded |

14 PNGs total. Lightbox/mega-menu/drawer captured via `[data-video-trigger]`, `[data-megamenu]`,
and the hamburger `[aria-label="Open menu"]` controls already present in the components.
