# Visual QA v4 — feat/face-and-about-sections @ db92161

Complete current capture. Independent of v3 (5836fa6), one consistent naming
convention (`__1440` / `__390`), no older shots mixed in.

- **Source build:** `git rev-parse HEAD` = `db92161` (branch tip of feat/face-and-about-sections)
- **Mode:** local **production** build — `next build` then `next start` (NOT `next dev`)
- **Tool:** Playwright (Chromium), full-page PNGs at viewport 1440 (desktop) and 390 (mobile); interaction states are viewport captures. CSS transitions/animations frozen so open states are fully settled.

## Pages (full-page, 1440 + 390)

| File base | Matt item(s) evidenced |
|---|---|
| `about-aesthetic-nurses` | 7 — rectangular 4:5 portraits at ~2× |
| `about-financing` | 8 — sized-up pre-qualify buttons |
| `about-financing-cherry-payment-plans` | 9 — no hero/intro, enlarged Cherry widget |
| `facelift` (rhytidectomy-facelift, lightbox CLOSED) | 12 (closed); **6** FAQ left-align; **5** sage bullets on light + dark sections; **4** gold links on dark section |
| `about-surgery-center` | **5** sage bullets light + dark; QUAD A text sections (item 10 context) |

## Interaction states

| File | Viewport | Matt item |
|---|---|---|
| `facelift-video-lightbox-open__1440` | 1440 | 12 — in-page video lightbox OPEN |
| `facelift-video-lightbox-open__390` | 390 | 12 — in-page video lightbox OPEN |
| `nav-megamenu-open__1440` | 1440 | 3 — Plastic Surgery grouped mega-menu OPEN (Face/Breast/Body, db92161) |
| `nav-mobile-drawer-expanded__390` | 390 | 3 — Plastic Surgery drawer section expanded |
| `nav-ourpractice-open__1440` | 1440 | 3 — Our Practice desktop dropdown OPEN |
| `nav-ourpractice-drawer-expanded__390` | 390 | 3 — Our Practice drawer section expanded |

**16 PNGs total.** Item-requirement coverage: FAQ (item 6) → `facelift`; bullets on light **and** dark (item 5) → `facelift` + `about-surgery-center`; links on dark (item 4) → `facelift`.
