# Advanced Mechanical — unofficial Hamilton pitch sample

A mobile-first one-page website **proposal** for **Advanced Mechanical**, an HVAC shop listed at 148 Adis Ave, Hamilton, ON L9C 6V3.

**This is not the company’s official website.** It is an unofficial sample prepared as a pitch so the owner can see what a simple site could look like. It is not affiliated with Advanced Mechanical until they say otherwise.

There is no public email on the listings used for this page. There is **no contact form**, no online booking, and no online payment. The only call to action is **call Milad at 905-745-7457**.

Live URL (after Pages is on): [https://kunyi523.github.io/advanced-mechanical/](https://kunyi523.github.io/advanced-mechanical/)

The shop’s own domain, `advancedmechanical.ca`, was parked at the registrar (WHC.ca) at research time. This page does not treat that domain as a live marketing site.

## How to open

The site is `index.html` with inlined CSS/JS, plus photos in `images/`. Open the file in a browser, or visit the Pages URL on a phone.

Optional local server, from this folder:

```bash
python3 -m http.server 8080
```

Then visit http://localhost:8080

## GitHub Pages

Static files live at the **repository root**. Enable branch-based Pages (same pattern as the Nail To Nail sample):

1. **Settings → Pages**
2. Build and deployment → Source: **Deploy from a branch**
3. Branch: **main**, folder: **/** (root)
4. Save

GitHub will serve the site at `https://kunyi523.github.io/advanced-mechanical/`.

Do not add a GitHub Actions workflow for Pages. Use branch-based Pages from `main`.

## Design

Visual language follows Rico’s open ClickHouse `DESIGN.md` from the brand library at [design.ricoui.com/brands](https://design.ricoui.com/brands) (source files: [ricocc/brands-design-md](https://github.com/ricocc/brands-design-md) → `brands/clickhouse`). Black canvas, electric yellow CTAs, Inter + JetBrains Mono, 8–12px radii, 1200px max width — a workshop / high-vis trades look, not a luxury barbershop palette.

## Photos

No Unsplash/Pexels HVAC models.

| File | What it is |
| --- | --- |
| `images/van-listing.jpg` | Public listing photo of the Advanced Mechanical van (OnHamilton / goguild directory). Lettering matches the shop name, 905-745-7457, and the service list. |
| `images/adis-ave-streetview.jpg` | Google Street View still of 148 Adis Ave (pano `vtu_CCbsAaWUoiv7i7HbCQ`, heading ~350°). House number 148 is on the garage. |
| `images/adis-ave-aerial.jpg` | Aerial of 148 Adis Ave and the immediate block (Esri World Imagery tiles, stitched). |
| `images/adis-ave-neighbourhood.jpg` | Wider aerial of the same west-mountain streets. |

Street View Static API without a key returned 403. The still above was fetched from Google’s Street View thumbnail endpoint using a panorama id from Maps. The page also embeds Google Maps for 148 Adis Ave and a Street View iframe for that same pano.

The luxury fireplace interior on that same goguild listing was not used — it reads as stock, not this shop.

## What’s on the page

- Shop name, 148 Adis Ave, click-to-call (`tel:9057457457` — **905-745-7457**)
- Thumb-sized **Call** and **Directions** buttons (56px tap targets)
- Hours from public listings: Mon–Fri 7am–7pm, Sat–Sun 7am–5pm
- Services from the public list / van lettering only (furnace, AC, heat pump, tankless/hot water, ductwork, gas piping, humidifiers, fireplaces, maintenance). Directories claim 24-hour emergency — the page says that without inventing a licence
- Three short published review quotes (first name only): Maxwell, Meaghan, S.
- About 4.9 from 42 Google reviews via Birdeye
- Google Map embed, Street View iframe, and Get directions for 148 Adis Ave
- A small footer: unofficial sample for Advanced Mechanical · Hamilton

A small script only labels today’s hours in the America/Toronto timezone.

## Facts used (public sources only)

- Address: 148 Adis Ave, Hamilton, ON L9C 6V3
- Phone: 905-745-7457. One directory also prints 905-745-6644; that number is **not** treated as confirmed and is not on the page
- Owner/tech: Milad Sideq (TrustedPros / allbiz). Reviews also name Zamir
- Year listed established: 2012 (TrustedPros)
- Hours: Birdeye (and matching directory listings)
- Rating: about 4.9 from 42 Google reviews, aggregated on Birdeye
- 24-hour emergency: claimed on TrustedPros — not independently verified here
- TSSA #000259698 appears on the van in the listing photo. This page does not invent further licences, insurance, or certifications
- `advancedmechanical.ca` parked at WHC.ca at research time

## What this page does not do

- Invent email, a contact form, prices, warranties, or extra certifications
- Pretend stock photos are this crew’s jobs
- Copy barbershop story or copy from the Gus & Son / Nail To Nail samples
- Treat the parked `advancedmechanical.ca` domain as a live site
- Take bookings or payments
