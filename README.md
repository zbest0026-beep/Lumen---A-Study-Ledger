# Lumen — A Study Ledger

This is the installable Progressive Web App (PWA) version of your original Lumen study tracker.

## What changed
- Kept the original interface and core features.
- Added an app manifest, app icons, and a service worker.
- Added basic offline caching for the app shell and resources after they have loaded once.
- Removed pre-filled demo subjects, study logs, and tasks so a fresh install starts empty.
- Fixed local-date handling so dates are not shifted by UTC conversion.
- Fixed the timer save/reset flow so it does not recursively prompt itself.

## Important data note
Your subjects, tasks, and study logs are saved in this browser on this device using local storage. They are not automatically synced to another phone or computer, and clearing browser/site data can erase them. This version does not have accounts or cloud backup.

## How to put it online for free
1. Create a free account on GitHub if you do not already have one.
2. Create a new repository (for example, `lumen-study-ledger`).
3. Upload the contents of this folder to the repository's main/root folder. `index.html` should be at the top level.
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**, select **main** and **/(root)**, then save.
6. Wait for GitHub Pages to publish the site. It will show you the website address.

## How to install on Android
1. Open the published website in Chrome.
2. Open Chrome's three-dot menu.
3. Tap **Install app** or **Add to Home screen** (the wording can vary).
4. Confirm. Lumen will appear with its own icon.

## Before sharing it publicly
This version is suitable for trying personally. Before inviting lots of students to use it, it should get a proper privacy notice, data export/backup, accessibility testing, and (if cross-device sync is wanted) a secure account/database system.
