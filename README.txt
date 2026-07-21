PWA package.

IMPORTANT FOR IPHONE:
Safari can install to Home Screen, but service workers/PWA require the app to be served over HTTPS.
Opening index.html directly from Files will not register the service worker.

Upload these files to any HTTPS hosting (GitHub Pages, Cloudflare Pages, Netlify, etc.), open once in Safari, then Share -> Add to Home Screen.
After the first load, it works offline.
