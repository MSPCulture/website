# mspculture.com

Static site for MSP Culture. Plain HTML/CSS, no build step. Hosted on Cloudflare Pages; every push to `main` deploys, every branch gets a preview URL.

## Structure
- `index.html`: the whole site (styles inline at the top)
- `assets/`: logo (from the MSP Culture design system), headshot, social preview image
- `_headers`: security headers (Cloudflare Pages)

## Editing
Ask Claude: "Add the <kit> to the toolkits section of mspculture.com." Changes go on a branch, you review the preview link, then merge.

## Placeholders to replace
- `GUMROAD_ONBOARDING_URL`: Gumroad link for the onboarding kit (or the free "get notified" listing)
- `BOOKING_URL`: Calendly / Microsoft Bookings link
- `CONTACT_EMAIL`: business email address
- `LINKEDIN_URL`: MSP Culture LinkedIn page
