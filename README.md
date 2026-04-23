# schoolsportportal.com.au

Source for the School Sport Portal directory site. Part of the 4-domain SportPortal platform.

## Structure

- `index.html` — public homepage (shows demo pages only, real hierarchy hidden)
- `demo-*.html` — 4 public demo pages (school, district, division, region)
- `williamstownps.html` — Williamstown Primary School (real, unlisted)
- `williamstowndistrict.html` — Williamstown District (real, unlisted; restored Apr 23)
- `hobsonsbaydivision.html`, `wyndhamdivision.html`, `wmr.html` — real division/region pages
- `{altona,laverton,pointcook,hopperscrossing,derrimut,tarneit,truganina,werribee,wyndhamvale}district.html` — real district stubs
- `vercel.json` — clean-URL routing config

## Deploy

Connected to Vercel project `schoolsportportal`. Push to `main` triggers auto-deploy.

## Related properties

- `sportportal.com.au` — flagship, marketing, payment
- `sportcarnival.com.au` — carnival management tool
- `carnivaltiming.com` — on-the-day timing tool
