# christcaremarketingsolutions.github.io

Root GitHub Pages site for the ChristcareMarketingSolutions account.

- `.well-known/assetlinks.json`: Android App Links verification for the Bible Buddies app
  (`com.christcare.biblebuddies`), so links to
  https://christcaremarketingsolutions.github.io/Bible-Buddies/ open in the app.
  When the app is published on Google Play, add the Play App Signing SHA-256 fingerprint
  (Play Console → Setup → App signing) to `sha256_cert_fingerprints`.
- `.nojekyll`: needed so GitHub Pages serves the `.well-known` folder.
- `index.html`: forwards visitors to Bible Buddies.
