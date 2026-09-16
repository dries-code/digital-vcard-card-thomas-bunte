# TUJP Connect Card — Thomas Bunte

Built to match Daan Grasveld's live card (https://tujp-connectcard-daangrasveld.netlify.app/) exactly — same design, copy, stats, product photo and EU funding badge. Only the contact block, title, and `.vcf` differ.

- `index.html` — the landing page
- `thomas-bunte.vcf` — the downloadable contact card for the CTA button
- `jungle-blocks.jpg`, `eu-co-funded.png`, `tujp-logotype.svg`, `tujp-logomark.svg` — shared assets, self-contained in this folder (same files as Daan's card)

## Current status

- ✅ HubSpot form is live (same portal/form as Dries's and Daan's cards)
- ✅ Vimeo video is embedded
- ✅ Jungle Blocks® photo (the crane/balcony installation shot), TUJP logos, and the "Co-funded by the European Union" badge are in place
- ⏳ **Thomas's photo** — add `thomas-photo.jpg` to this folder, then in `index.html` replace
  `<div class="avatar">TB</div>` with `<img src="thomas-photo.jpg" alt="Thomas Bunte">` inside `.avatar`
  (see the TODO comment right above it). Match the square-crop, ~560×560px framing used for Daan.

## Note on contact details

Thomas is listed as **Sales Germany, Austria & South Tyrol**, with his own email
(`t.bunte@ebben.nl`) rather than a `@theurbanjungleproject.com` address — same situation as Hans.
Let me know if he should get a TUJP address instead, and whether `ORG: The Urban Jungle Project`
is right or if it should say Ebben.

## Heads up: Dries's and Hans's cards still use the older template

Daan's card (used as the base for this one) has since diverged from what's live for Dries and
Hans — different impact stats, a different Jungle Blocks® photo, and this new EU-only funding
badge instead of the OPZuid regional one. If you want all cards visually consistent, Dries's and
Hans's folders need the same update — ask and I'll bring them in line.

See the repo root `README.md` for how this folder is deployed and how to add another colleague.
