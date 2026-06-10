# Visual QA — our-practice-linkable-qa-v1

Nav fix making the "Our Practice" landing (`/about`) reachable, on
`Secor45-Git/pacifica` branch `feat/face-and-about-sections` (commit `ca8320c`).

Captured with Playwright (chromium), `deviceScaleFactor: 2`.

| Screenshot | Viewport | Scenario |
|---|---|---|
| `our-practice-dropdown-1440.png` | 1440 | Desktop nav with the "Our Practice" dropdown open (hover). Trigger click navigates to `/about` via `useRouter().push` — same mechanism as the Plastic Surgery mega trigger. |
| `about-landing-1440.png` | 1440 | `/about` landing (full page: hero + intro + cards). |
| `about-landing-390.png` | 390 | `/about` landing, mobile. |
| `mobile-drawer-our-practice-390.png` | 390 | Mobile drawer with "Our Practice" expanded — "Our Practice" (`/about`) is the first accordion item. |
