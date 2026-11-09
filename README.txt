SMART PDF SCANNER — MOBILE SETUP (FREE)

WHAT IS INCLUDED
- Camera capture (live camera on supported HTTPS browsers; fallback to Android image capture)
- Import images and PDF files
- Local document library using IndexedDB
- Favourites, search, sort, rename, download, delete
- Images to PDF
- Merge PDFs
- Split PDFs into one-page PDFs
- PDF editor: rotate/delete pages and add a text watermark, saving an edited copy\n- PDF object-stream re-save (not guaranteed to reduce every PDF)
- Signature pad
- OCR (English)
- QR code reading from an image and QR code generation from text/URLs
- ID photo maker: import a portrait and create 4x6 inch sheets in 35x45 mm, 2x2 inch or 25x35 mm sizes
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

NEW FEATURES IN THIS VERSION
- QR code generator: enter text or a URL, generate a QR code, and save it in your local library.
- PDF editor: choose a PDF, rotate a selected page, delete a page, and optionally apply a text watermark to every page. The edited PDF is saved as a new copy; the original is preserved.
- ID photo maker: import a photo, choose 35x45 mm passport, 2x2 inch visa, or 25x35 mm, choose the number of copies, and create a 4x6 inch print sheet.
- QR scanner continues to read QR codes from selected images.

NOTES
- ID photo sheet is a layout helper, not an official photo-compliance checker. Check the destination authority's current photo rules and use a properly cropped, compliant portrait.
- The PDF editor provides basic page operations and watermarking; it is not a full desktop-style text/object editor for changing existing PDF text.
- For camera and install features, deploy on HTTPS (GitHub Pages works).
