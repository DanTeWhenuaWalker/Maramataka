# Te Maramataka

A kaupapa Māori leadership guide aligned to the rhythm of te marama. A discipline for governing, building and pausing in the right season.

## What is here

| File | Purpose |
| --- | --- |
| `index.html` | The website. A single self-contained page with no server, database, or build step. |
| `maramataka.ics` | A static calendar covering July 2026 to October 2028, for people who prefer to subscribe rather than download. |
| `CNAME` | Points GitHub Pages at the custom domain `temaramataka.nz`. |

## Hosting

The site is static. It runs on GitHub Pages, Netlify, Cloudflare Pages, or any web server, with no configuration.

For GitHub Pages: push these files to the repository root, then open **Settings → Pages** and set the source to **Deploy from a branch**, branch `main`, folder `/ (root)`. The site appears at `https://<username>.github.io/<repository>/` within a minute or two, and at `https://temaramataka.nz` once DNS is pointed at GitHub and **Enforce HTTPS** is ticked.

Links inside the calendar entries are fixed to `https://temaramataka.nz/`, so they remain correct regardless of where the site is served from.

## Notes

- All dates are computed in the browser from astronomical new moon times for Pacific/Auckland. Nothing is sent anywhere.
- The new moon table in `index.html` runs to October 2028. Extending it is a matter of adding dates to the `NEW_MOONS` array.
- Calendar events are marked `TRANSP:TRANSPARENT`, so they never block availability.
- Where a lunar month holds twenty-nine nights, Ōmutu rests and Mutuwhenua closes the month.

## He kupu whakamārama

The names are only one part of the maramataka. The real practice comes from observing the tohu in your own environment. Iwi and hapū hold their own maramataka, shaped by their whenua, moana, and mātauranga, and those regional forms take precedence in their own rohe. This calendar is offered as a guide, not a prescription.
