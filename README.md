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
- `app-ads.txt`: AdMob authorized-seller declaration, Google DIRECT line
  only

All numbers on the pages come from the shipped code and docs: 100 free
points per UTC day, free top-ups stop at a 200 balance, rewarded ads pay 25
points at most three per UTC day, four consumable packs of 100, 300, 1,000,
or 3,000 points with prices from the live App Store, a local SwiftData
ledger with no iCloud sync, Google Mobile Ads with non-personalized and
under-age treatment, and Apple's 18+ rating rule for frequent simulated gambling
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

## app-ads.txt and root hosting

The AdMob crawler looks for the file at the root of the developer website,
not inside a project path: for a store listing pointing at
https://wxundup.github.io/night-floor-support/ it checks
https://wxundup.github.io/app-ads.txt (source:
https://support.google.com/admob/answer/9363762#step3).

Therefore the file must live in the separate root user-site repository
`wxundup/wxundup.github.io` (at https://wxundup.github.io/app-ads.txt),
not in `night-floor-support`. Its content is this single line:

```
google.com, pub-6688441843186564, DIRECT, f08c47fec0942fa0
```

The file is published in that root repo and its live content was verified
against the snippet shown by the AdMob account. This folder holds the
canonical copy for future updates. The App Store listing's Marketing URL
must use the same host so the crawler can tie the app to the file. Public
listing, crawl verification, and Google review remain pending. The individual
payment profile is complete; Google account approval is pending.
