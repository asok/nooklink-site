# Nooklink website

Static, dependency-free site for GitHub Pages. `index.html` describes the phone
camera, phone and desktop monitors, and local-network setup. `privacy.html`
covers the mobile and desktop apps and is the permanent privacy-policy page for
App Store Connect and Google Play Console. Both pages support English, Polish,
Simplified Chinese, Hindi, Spanish, Arabic, Portuguese, and French. The language
switcher remembers the choice in browser local storage.

## Publish

The manually triggered **Website** workflow at `.github/workflows/pages.yml`
publishes `website/`. Run it from **Actions → Website → Run workflow** after
merging the version that should go live. In **Settings → Pages**, set **Build and
deployment → Source** to **GitHub Actions**. The expected URLs for this
repository are:

- Home: `https://asok.github.io/nooklink/`
- Privacy policy: `https://asok.github.io/nooklink/privacy.html`

Verify the live URL before entering it in App Store Connect or Play Console.
The store release build and its privacy declarations should match the published
policy. Store policies also require the privacy policy to be accessible from
within the app.
