# STATUS — BTI Junk Removal site

## What this is
Free one-page phone website Cody is giving the BTI Junk Removal owner (Tucson) as a bonus for one day's work. Not paid. One-time gift, no ongoing maintenance.

## Decisions made
- One page, phone-first, static. No GHL, no backend. Leads = prefilled text message to his phone (520-486-6490) with a photo.
- Style matches his flyer: black, lime brush banners, chrome logo, sunset art. Images = ChatGPT illustrated set (bti-images flyer style). Photoreal set rejected ("too professional").
- Trailer = 5x8 (Cody's assumption, sides ~4 ft). Pricing set by Claude, Cody closes him on it:
  few items $95, 1/4 $150, 1/2 $250, 3/4 $350, full $425; single items $50-$95; extras: stairs +$25/flight, same-day +$40, tires +$15.
- Added services: cleanouts (from $250), moving help ($95/hr, 2 hr min), assembly ($60/item), yard ($150), move-out clean ($175), donation drop-off (+$40).
- Rejected: furniture repair (needs skill), ranges on prices (invite haggling).
- Deploy: private GitHub repo -> Cloudflare Workers (Cody's standard).

## Cody's words (verbatim)
- "make a funnel, make fucking sales, and make it so this will work for this guy. Add any proof you can"
- "He just gets a text message"
- "I don't know how big the trailers are. Let's just say it's 5 by 8."

## Status
| Item | Status |
|---|---|
| Page built (public/index.html) | Done, v2 flyer style |
| Images optimized (public/img) | Done |
| GitHub repo | Pending |
| Cloudflare dev site | Pending |
| Owner confirms services + prices | Pending (Cody) |
| Google Business Profile / reviews | Not started |

## Open questions
- Does he take all the added services (moving, assembly, cleaning, yard)?
- Real trailer size / side height.
- Payment methods, licensed/insured? (not claimed on site)
- His domain name.

## Next action
Push repo to GitHub, Cody imports it in Cloudflare Workers for the dev URL.
