# The Daily Jobs — PWA

Deployment-ready Progressive Web App based on the supplied Video Studio HTML.

## Included
- Original Video Studio UI and rendering functionality
- Web App Manifest
- Service Worker for offline app-shell caching
- Installable PWA metadata
- 192px and 512px app icons
- Offline-first same-origin asset caching
- External CDN/font resources cached after first successful load

## Deployment
Upload the contents of this folder to any HTTPS static hosting provider.
The site must be served over HTTPS (or localhost during development) for service-worker/PWA installation.

## Important
The video renderer uses the browser's MediaRecorder and canvas APIs. Actual MP4/WebM support depends on the user's browser, as in the original app.
