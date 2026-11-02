# Feed Me & Love Me — Official site

This branch contains the static homepage and privacy policy for the Android game, developed by Zemvuu.

## Publish the website (recommended setup)

1. Create a **PUBLIC** repository named **feedmeloveme.github.io** under the GitHub account **Feedmeloveme**. Keep the game source repository PRIVATE.
2. Copy index.html, privacy.html, styles.css, favicon.svg and .nojekyll from this branch into the ROOT of that new repository's main branch.
3. Open Settings → Pages → Build and deployment → Deploy from a branch → main / (root) → Save.
4. Check https://feedmeloveme.github.io/ and https://feedmeloveme.github.io/privacy.html publicly. Only use the privacy policy URL in Google Play when it actually opens without GitHub sign-in.

## Future app-ads.txt

For AdMob, add a plain UTF-8 file named app-ads.txt to the root of the separate public site. Verify https://feedmeloveme.github.io/app-ads.txt . A typical Google seller entry looks like:

    google.com, pub-YOUR_VERIFIED_ADMOB_PUBLISHER_ID, DIRECT, f08c47fec0942fa0

Do not publish a guessed seller ID or use test ad unit IDs. Keep this file deferred until the Feed Me & Love Me AdMob setup is ready.

## Important

- Site contact email feedmeloveme@proton.me is PUBLIC on the website. Replace it if you prefer a separate support address.
- The privacy policy reflects the v0.3.1 closed-test build and should be reviewed when enabling production advertisements or real purchases.
- Do not make the PRIVATE Android source repo public to host this site.
