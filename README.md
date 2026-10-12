# Night Floor release site

Static support, privacy, and terms pages for GitHub Pages. Plain HTML and
one small stylesheet. No frameworks, no JavaScript, no cookies, no
analytics, no external assets.

## Files

- `index.html`: support page in casual player language (floor, free
  points, ads, packs, co-op, storage, contact)
- `privacy.html`: privacy policy matching the in-app policy and the real
  ad SDK behavior
- `terms.html`: terms of use matching the in-app terms, with the accurate
  App Store age note
- `styles.css`: the only stylesheet, system fonts only

All numbers on the pages come from the shipped code and docs: 100 free
points per UTC day, free top-ups stop at a 200 balance, rewarded ads pay 25
points at most three per UTC day, four consumable packs of 100, 300, 1,000,
or 3,000 points with prices from the live App Store, a local SwiftData
ledger with no iCloud sync, Google Mobile Ads with non-personalized and
teen treatment, and Apple's 18+ rating rule for frequent simulated gambling
with the in-app 13 minimum preserved.

## Support email

Every page links its contact address as a `mailto:` link to
woundedmc1@gmail.com, one per page (index, privacy, terms). The site is
published at https://wxundup.github.io/night-floor-support/.

## Publishing

Only this folder's contents are published in `wxundup/night-floor-support`,
with GitHub Pages serving the main branch root. The app repository remains
private. Copy changes from this folder into the separate website repository
to update the published pages. Links between pages are relative.
