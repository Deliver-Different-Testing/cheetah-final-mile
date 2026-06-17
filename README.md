# Cheetah Final Mile — Recipient Portal

Demo recipient portal for **Cheetah Final Mile**, a prospective DFRNT tenant.

## Use case

Cheetah operates a final-mile delivery facility at **13219 Arrington Road, Grandview, MO 64030**. Packages are received into the warehouse and scanned in. When a parcel is scanned, the recipient is alerted by SMS + email with a link to this portal. The portal lets the recipient confirm their details and pick a delivery window — same flow shape as the DFRNT baggage portal, recast for warehouse-origin last-mile.

## Pages

- **index.html** — landing page with links to both flows
- **receiver-mobile.html** — mobile recipient confirmation (details, address, delivery window, authority to leave)
- **tracking.html** — live tracking page (timeline, driver, ETA)

## Brand

- Logo: `assets/cheetah-logo.jpg`
- Dark: `#1a1a2e`
- Accent: `#ffb800` (yellow, from the logo's motion line)
- Secondary highlights: `#e63946` (red) and `#2a52be` (blue) from the logo

## Stack

Static HTML / CSS / JS. Deploys to GitHub Pages.

## Origin

Cloned from the DFRNT baggage portal and recast for the Cheetah Final Mile use case. All airline / airport / passenger language has been stripped in favour of warehouse / parcel / recipient language.
