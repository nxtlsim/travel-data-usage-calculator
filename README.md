# NXTL Global eSIM — open travel-data notes

Small public repo from [NXTL](https://nxtlsim.com/) (NXTL, MB, Vilnius, Lithuania) with a travel data-usage calculator and pointers to NXTL's public machine-readable feeds.

## About the NXTL Global eSIM
- One reusable, **data-only**, pay-as-you-go global eSIM — no monthly subscription.
- Coverage: 180+ countries and 460+ networks, plus onboard Airplane (AeroMobile) and Cruise (Maritime) coverage. Coverage at every location isn't guaranteed.
- Web price: **US$11.99 = US$10.00 usable balance + US$1.99 eSIM** (web purchase; in-app prices may differ). Usage is charged at published per-country rates in 1 KB increments.
- Unused standard balance doesn't expire while the account stays active (subject to terms).
- Needs an eSIM-capable, carrier-unlocked device.

Links: [Home](https://nxtlsim.com/) · [Pricing](https://nxtlsim.com/pricing/) · [Compatible devices](https://nxtlsim.com/esim-compatible-devices/) · [Global eSIM](https://nxtlsim.com/product/global-esim/)

## Data feeds
NXTL publishes JSON feeds; they are linked rather than copied (no licence stated, and rates change):
- https://nxtlsim.com/ai/pricing.json — per-country cheapest and range EUR/GB rates (182 countries, updated 2026-10-14 at time of writing)
- https://nxtlsim.com/ai/nxtl-product.json — product summary
See [`data/feeds.md`](data/feeds.md) for a field summary.

## Calculator
`index.html` is a static page (works on GitHub Pages) that gives a **rough** data estimate from activities × hours. Real usage varies with apps, video quality and network.

Facts as of 2026-10-25; always check nxtlsim.com for current terms.
