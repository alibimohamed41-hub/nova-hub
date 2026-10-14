# NovaHub

NovaHub is a responsive, single-page collection of useful browser tools, built with plain HTML, CSS and JavaScript. No build tools or dependencies are required.

## Included tools
- Word Counter (words, characters, sentences, estimated reading time)
- Case Converter (uppercase, lowercase, title case, sentence case)
- Quick Calculator (arithmetic and percentage)
- Unit Converter (length, weight, temperature)
- Password Generator (choose length and character sets)
- QR Code Helper (prepare and copy text/URL payload)

Search, category filters, mobile navigation, modal dialogs, and copy buttons are interactive.

## Run locally
Open `index.html` in any modern browser.

## Publish with GitHub Pages
1. Create a new repository on GitHub, for example `novahub`.
2. Upload `index.html` to the repository's root folder.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then click **Save**.
6. Wait for GitHub Pages to publish the site. The public URL will appear on the Pages settings page.

## Notes
- This is a static website and works on GitHub Pages.
- Tool calculations and text processing run in your browser.
- The QR Code Helper prepares/copies a payload; it does not generate a scannable QR image.
- There is no backend, login, or server-side storage.
