# Kettle & Crumb GitHub Pages package

Upload `index.html`, `styles.css`, `app.js`, and the entire `assets` folder to the root of your GitHub repository. In GitHub, open **Settings > Pages**, choose **Deploy from a branch**, select the `main` branch and `/ (root)`, then save.

Do not preview this project through OneDrive or SharePoint and use that preview as the final website test. Those previews can restrict JavaScript. Test either by opening `index.html` from the extracted folder or through GitHub Pages.

## Included diagnostics
- HTML/CSS/JavaScript files use relative paths suitable for GitHub Pages.
- All 12 images are stored in `assets` with lowercase, space-free filenames.
- Main navigation, basket, checkout, filters and bespoke-order controls are implemented in `app.js`.
- Bespoke orders fall back gracefully if browser storage is unavailable.
