# Aircraft Weight & Navigation Calculator

## Publish on GitHub Pages
1. Create a GitHub repository.
2. Extract this ZIP and upload **all files** to the repository's top level (the same level as `index.html`).
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
5. Wait for GitHub Pages to publish, then open the Pages URL on your phone.

## Install on iPhone
1. Open the published HTTPS URL in **Safari**.
2. Tap **Share** → **Add to Home Screen** → **Add**.

## Install on Android
1. Open the published HTTPS URL in **Chrome**.
2. Tap **⋮** → **Install app** (or **Add to Home screen**).

## Offline notes
Open the site once while online and allow it to finish loading before testing offline. The calculator page and app icons are cached. Leaflet's map library, satellite imagery, and map tiles are loaded from external services and are cached only as they are successfully visited; the entire map of Egypt is **not** bundled for offline use. The map therefore needs internet for areas/tiles that have not previously been viewed. Browser storage can also be cleared by the device.

The app uses a service worker, which requires HTTPS. GitHub Pages provides HTTPS automatically.
