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
ready to publish; it has not been published yet.

## Publishing

The app repository is private and must stay private. Do not publish it.
Publish only this folder's contents, for example as a new public repo with
`index.html` at its root, then enable GitHub Pages from the main branch.
All links between pages are relative, so the folder works at any URL root.
