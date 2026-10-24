# mspculture.com

Static site for MSP Culture. Plain HTML/CSS, no build step. Hosted on Cloudflare Workers (static assets); every push to `main` deploys, every branch gets a preview URL.

## Structure
- `public/index.html`: the whole site (styles inline at the top)
- `public/assets/`: logo (from the MSP Culture design system), headshot, social preview image
- `public/_headers`: security headers
- `wrangler.jsonc`: Cloudflare config (serves `public/` as static assets)

## Editing
Ask Claude: "Add the <kit> to the toolkits section of mspculture.com." Changes go on a branch, you review the preview link, then merge.

## Pending
- Onboarding kit card shows "Coming soon" until the Gumroad link exists
- Booking link and LinkedIn link not added yet
