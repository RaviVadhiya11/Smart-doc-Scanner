SMART PDF SCANNER — MOBILE SETUP (FREE)

WHAT IS INCLUDED
- Camera capture (live camera on supported HTTPS browsers; fallback to Android image capture)
- Import images and PDF files
- Local document library using IndexedDB
- Favourites, search, sort, rename, download, delete
- Images to PDF
- Merge PDFs
- Split PDFs into one-page PDFs
- PDF object-stream re-save (not guaranteed to reduce every PDF)
- Signature pad
- OCR (English)
- QR code reading from an image
- ID-card capture/import workflow
- Dark mode
- PWA install and basic offline app shell

IMPORTANT LIMITATIONS
- Files stay in this browser's local IndexedDB. Clearing browser site data can delete them. Export/download important files for backup.
- Camera access generally requires HTTPS or localhost. GitHub Pages is HTTPS.
- PDF/OCR/QR libraries are loaded from public CDNs, so those tools need an internet connection the first time (and may need it again if browser cache is cleared).
- "Compress PDF" re-saves with object streams. It is not a full image-downsampling compressor.
- This is a PWA/web app, not a native Android APK. PWABuilder can package a hosted PWA, but signing and Play Store publishing have separate requirements.
- ID Card tool is a convenient capture/import shortcut; it does not automatically detect ID edges or extract identity data.
- No cloud sync, account login, server upload, or paid API is included.

HOW TO RUN ON YOUR PHONE
1. Extract this ZIP.
2. Create a free GitHub account at https://github.com
3. Create a new PUBLIC repository named smart-pdf-scanner.
4. Upload the files from this folder (index.html, style.css, app.js, manifest.json, sw.js).
5. In repository Settings > Pages, choose Deploy from a branch, select main and /(root), then Save.
6. Wait for GitHub Pages to publish. Open the Pages URL in Chrome on Android.
7. Use Chrome menu > Add to Home screen (or Install app if offered).
8. Allow camera access when scanning. Import can be used if live camera is unavailable.

LOCAL TEST
You can open index.html in a desktop browser, but camera/PWA features require HTTPS or localhost. On Android, use the hosted GitHub Pages URL.

PRIVACY
The app itself does not send your documents to a custom server. External JavaScript libraries are fetched from CDNs. Your documents are saved in browser storage on your device.
