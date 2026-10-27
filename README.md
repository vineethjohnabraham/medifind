# MediFind: online demo

Static build of the MediFind find-a-doctor app for GitHub Pages.

This version runs entirely in the visitor's browser. There is no server:
- The sample doctors, bookings and accounts are saved only in each visitor's own browser.
- "More clinics nearby" is looked up live from OpenStreetMap, straight from the browser.

Use the full Node.js version for real use.

## Publish on GitHub Pages
1. Create a new repository on GitHub (for example `medifind`).
2. Upload **everything in this folder** to the repository root, including the hidden `.nojekyll` file.
3. In the repository, open **Settings → Pages**, set **Source** to *Deploy from a branch*,
   pick branch `main` and folder `/ (root)`, then **Save**.
4. After a minute the site is live at `https://<your-username>.github.io/<repository-name>/`.

Demo sign-in: one-click demo accounts on the sign-in page (password `demo1234`).
