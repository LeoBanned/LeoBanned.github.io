# Crocodile Gena Studio — website

A standalone, responsive landing page. No build step, npm dependencies or API keys.

## Open locally

Open `index.html` directly, or run `npm run dev` and visit http://127.0.0.1:4173.
Node.js is only needed for the optional local server.

## Deploy

Upload `index.html`, `style.css`, `script.js` and the entire `assets` folder to any static host. The project uses relative asset paths and works in a subdirectory. `serve.cjs` is a local preview server, not a production backend.

## Edit

- Page structure and Russian copy: `index.html`.
- English translations and the seven module descriptions: `script.js`.
- Colors: the `:root`, `[data-theme=jade]` and `[data-theme=ivory]` declarations in `style.css`.
- Download/repository/community links: `index.html`.
- Product screenshots: `assets/` (actual English application UI, version 5.6.4).

The header palette button cycles through Ember, Jade and Ivory. The gallery contains all seven modules, the home screen and settings. Screenshots are captured from the actual UI with demonstration IPC data; no Steam or system operations run during capture.

Website palettes do not change the desktop application's settings. Language and palette are remembered in the visitor's browser. Download links open the project's latest GitHub release; no unverified release version is hard-coded into the download button.

Fonts are served locally. Golos Text and Manrope are distributed under the SIL Open Font License; their license notices are in `assets/`. Product artwork and screenshots come from the Crocodile Gena Studio project.

No analytics, tracking cookies, contact forms or remote font requests. Outbound GitHub and Telegram links require internet access.

