# UFE Academic Planner – website files

Upload **all files in this folder together** (keep them in the same folder):

| File | What it does |
|---|---|
| `index.html` | The whole app (design, code, logo) |
| `manifest.webmanifest` | App name, colours and icons for "Add to Home Screen" |
| `sw.js` | Lets the app open offline and show notifications |
| `icon-192.png`, `icon-512.png`, `maskable-512.png`, `apple-touch-icon.png` | Home-screen icons |

## Publish for free with GitHub Pages

1. Make a free account at github.com.
2. Click **New repository**, name it e.g. `ufe-planner`, choose **Public**, click **Create repository**.
3. Click **uploading an existing file**, drag in every file from this folder, then click **Commit changes**.
4. Open **Settings → Pages**. Under *Build and deployment*, choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
5. After 1–2 minutes your app is live at `https://YOUR-USERNAME.github.io/ufe-planner/`.

## Install it like an app

- **Android (Chrome):** open the link → menu ⋮ → **Add to Home screen** / **Install app**.
- **iPhone (Safari):** open the link → Share button → **Add to Home Screen**.
- **Computer (Chrome/Edge):** click the install icon at the right of the address bar.

## Updating the app

Replace `index.html` in the repository with the new version. Also change the first line of `sw.js`
(`ufe-planner-v1` → `ufe-planner-v2`) so phones pick up the update.

## Good to know

- Each person's tasks are saved on their own device/browser. Use **Settings → Data → Copy backup / Restore** to move them.
- Reminders, sound and notifications work while the app is open (also in a background tab).
  Notifications when the app is fully closed need a push server, which is a possible next step.
- On iPhone, notifications only work after the app is added to the Home Screen (iOS 16.4 or newer).
