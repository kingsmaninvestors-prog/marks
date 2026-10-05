# Marks App – Installation Guide

A browser can only install an app from a web address (https), not from a file opened on your device. So there are two parts: put the app online once, then install it on each device.

## Part A – Put the app online (one time, free)

You need the 6 files in this folder together: index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png, icon-maskable-512.png.

**Option 1 – Netlify Drop (easiest)**
1. Go to app.netlify.com/drop.
2. Drag this whole folder onto the page.
3. Netlify gives you a link starting with https://. (It may ask you to sign up to keep the site permanently.)

**Option 2 – GitHub Pages**
1. Create a free GitHub account and a new public repository.
2. Upload the 6 files to the repository.
3. In the repository go to Settings -> Pages, publish from the main branch (root folder).
4. After a minute your link appears: https://YOUR-NAME.github.io/REPOSITORY-NAME/

Open the link once while you have internet.

## Part B – Install on each device

- **Android (Chrome):** open the link, tap the green "Install app" button in the page (or Chrome menu -> Install app).
- **Windows / Mac (Chrome or Edge):** open the link, click "Install app" in the page (or the install icon at the right of the address bar).
- **iPhone / iPad (Safari):** open the link, tap Share -> Add to Home Screen.

Open the app from its icon. After the first load it works fully offline.

## Important

- Marks are saved on the device where you type them. Each device has its own data.
- Use "Backup Data" regularly, and "Restore Data" to move data to another device.
- Keep the same link. A different link is a different app with empty storage.
- To update the app later, upload the new files to the same place; the app picks them up next time it is opened online.
