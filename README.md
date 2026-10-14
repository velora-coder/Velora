# Velora

A mobile-first, client-side image compression, resizing and conversion website.

## Run locally
Open `index.html` in a modern browser. For best testing, you can also use VS Code Live Server.

## Publish on GitHub Pages
1. Create a new GitHub repository named `velora` (or use your desired repository).
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then save.
6. Wait until GitHub Pages finishes deploying, then open the published URL.

No build step, backend, API key, or external JavaScript library is required. Image processing takes place in the browser. This starter supports output as JPG, PNG, and WebP; animated GIFs are not kept animated when processed through canvas.
