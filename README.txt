Sheet Weight Calculator

Files:
- index.html: calculator app
- manifest.json: PWA metadata
- sw.js: offline cache after first load

Important:
This package is a lightweight Progressive Web App (PWA), not an Android APK.
To install it like an app, upload these files to an HTTPS website, open that URL in Chrome on Android, then use Chrome menu > Install app (or Add to Home screen).
After first successful load, the service worker caches the app for offline use.
The calculator uses approximate density factors:
MS 0.7293, SS304 0.7432, SS316 0.7432, SS430 0.7154 kg per ft² per mm.
