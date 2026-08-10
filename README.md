# Salary Calculator

NHS / non-NHS take-home pay calculator. Standalone static PWA (app shell +
service worker), no build step and no dependencies — deploy as-is.

Split out from the `portfolio` (mapleintel.uk) repo on 2026-08-10, where it
previously lived at `public/salary/` and was served at `mapleintel.uk/salary/`.
There is no separate source beyond this built app — it was already a
preserved, finished static utility. The `assets/maple-leaf.png` reference
was rewritten from `../assets/maple-leaf.png` to `assets/maple-leaf.png` to
match its new location at the repo root.

## Deploy

Point a Cloudflare Pages project at this repo root (no build command, no
output directory override needed). Attach whatever domain/subdomain you
want it reachable at (e.g. `salary.mapleintel.uk`).
