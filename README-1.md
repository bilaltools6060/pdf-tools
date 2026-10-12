# Free PDF Tools — updated website files

## Files in this folder
- `index.html` — responsive homepage and browser-based PDF tools.
- `privacy.html` — privacy policy page.
- `README.md` — publishing notes.

## Tools included
1. Merge PDF
2. Split / Extract Pages
3. JPG to PDF (supports JPEG, PNG and images the browser can decode)
4. Rotate PDF
5. Delete PDF Pages
6. Add Page Numbers
7. Watermark PDF
8. PDF to JPG (exports rendered pages in a ZIP file)

The PDF features use `pdf-lib`, and PDF-to-JPG uses PDF.js and JSZip. The libraries are loaded from cdnjs, so visitors need an internet connection for the libraries to load. Files are processed in the browser; the website code does not intentionally upload selected documents to a file-processing server. Very large files can exceed the available memory on some phones.

## Before publishing
1. Open `privacy.html` and replace `apna-email@example.com` with your real contact email. The same placeholder appears in the homepage contact link.
2. Test every tool on a few sample files, including on a phone.
3. Upload/replace `index.html`, `privacy.html`, and `README.md` in your existing GitHub repository (`bilaltools6060/pdf-tools`) on the `main` branch. Keep the existing repository name and Pages settings.
4. Wait for GitHub Pages to rebuild, then refresh the website. If the old version remains, try a hard refresh or a private/incognito tab.
5. The ad boxes are placeholders only. Do not paste ad code until your advertising account/site setup is ready and the provider has given you the correct code. Approval and income are not guaranteed.

## Notes
- No backend or server-side file storage is required for these tools.
- Third-party libraries are loaded from a CDN; the privacy policy explains this.
- This is a static website, so a custom domain is optional, not required for GitHub Pages.
