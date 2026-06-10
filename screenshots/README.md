# Visual QA — matt-round2-qa-v1

Matt review round 2 on `Secor45-Git/pacifica` branch `feat/face-and-about-sections`
(commits `eaa60fb`, `dc756d8`, `6f2eb8a`, `5af2ae0`). Playwright (chromium),
deviceScaleFactor 2, captured at 1440 and 390.

| Item | Screenshot(s) | What to look for |
|---|---|---|
| 1 — Gold links on dark | `facelift-goldlinks-{1440,390}` | "fully-accredited ambulatory surgery center" link + phone number are gold on the dark section. |
| 2 — Bigger nurse photos | `aesthetic-nurses-{1440,390}` | Provider portraits enlarged (280px mobile / 360px desktop, 4:5). |
| 3 — Bigger financing logos | `financing-{1440,390}` | CareCredit / Alphaeon / Cherry logos much larger, undistorted. |
| 5 — Blog index | `blog-top-{1440,390}`, `blog-lower-{1440,390}` | No "Pacifica Journal" heading; light, legible cards with full-brightness images (incl. lower cards). |
| 6 — Blog post | `blogpost-{1440,390}` | No "Blog · Category" line above title; image sits tighter under title + date. |
| 7 — Facelift video lightbox | `facelift-lightbox-{1440,390}` | Full-viewport overlay, centered video, close X at top-right corner, no page overlap. Portaled to body; iframe centered (x=720/y=450 @1440, x=195 @390), X 20px from corner. |
