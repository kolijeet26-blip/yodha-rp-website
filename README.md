# YODHA RP Website Starter

Responsive static website for a FiveM GTA roleplay community.

## Files
- `index.html` — website sections and whitelist form
- `style.css` — black/red responsive design
- `script.js` — menu, Connect button, server status, whitelist email draft
- `assets/` — place your logo and local images here

## Quick start
1. Extract the ZIP.
2. Open `index.html` in a browser to preview.
3. Open `script.js` and edit the `CONFIG` values:
   - `SERVER_ADDRESS`: your public FiveM address, e.g. `123.45.67.89:30120`
   - `DISCORD_INVITE`: your real Discord invite URL
   - `CONNECT_URL`: optional `fivem://connect/IP:PORT`
   - `APPLICATION_EMAIL`: the email that receives whitelist applications
4. Replace sample staff names, rules and store cards in `index.html`.
5. Upload all files to GitHub Pages, Netlify, or your web host.

## Publish free with GitHub Pages
1. Sign in at https://github.com/ and create a public repository, e.g. `yodha-rp-website`.
2. Upload `index.html`, `style.css`, `script.js`, and the `assets` folder.
3. Open repository **Settings → Pages**.
4. Under build/deployment, select **Deploy from a branch**, choose `main` and `/ (root)`, then Save.
5. Wait for the Pages URL to appear in Settings → Pages.

## Important setup notes
- Live server status calls the Cfx.re server-list endpoint from the browser. Some environments may block this request; if so, use a small backend/proxy and keep any private credentials on the server.
- The whitelist form is a starter that opens the visitor's email application. It does not store submissions online. For real online submissions, connect a form provider such as Formspree or build a backend.
- Store prices and packages are placeholders. Configure a real Tebex store and follow current FiveM/Rockstar monetization policies.
- The background photos are remote Unsplash URLs; replace them with images you have permission to use if you prefer local hosting.
