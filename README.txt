PakInfoHub V44 - Netlify-ready / GitHub-ready package

V44 adds an offline/online network status indicator for better PWA usability. Existing V27-V43 features are preserved.

Files:
- index.html: production website
- manifest.webmanifest: PWA metadata
- sw.js: service worker with V44 cache version

Deployment:
- GitHub: upload/commit these files to the PakInfoHub repository.
- Netlify Drop: upload this folder or its ZIP when production deploys are available.

V44 improvement:
- Shows a clear offline notice when the device loses internet connectivity.
- Shows a brief confirmation when connectivity returns.
- Offline notice is hidden during printing.
