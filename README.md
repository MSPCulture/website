# mspculture.com

Static site for MSP Culture. Plain HTML/CSS, no build step. Hosted on Cloudflare Workers (static assets); every push to `main` deploys, every branch gets a preview URL.

## Structure
- `public/index.html`: the home page
- `public/speaking.html`: talks, past events and press kit
- `public/reading.html`: the leadership reading plan (12-month plan + executive top 5)
- `public/assets/site.css`: shared styles for every page
- `public/assets/`: logo (from the MSP Culture design system), headshot, social preview image
- `public/_headers`: security headers
- `wrangler.jsonc`: Cloudflare config (serves `public/` as static assets)
- `src/index.js`: redirects www.mspculture.com to mspculture.com (301), then serves the site

## Editing
Ask Claude: "Add the <kit> to the toolkits section of mspculture.com." Changes go on a branch, you review the preview link, then merge.

## Pending
- Onboarding kit card shows "Coming soon" until the Gumroad link exists
- Booking link not added yet
