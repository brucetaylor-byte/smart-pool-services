# Smart Pool Services app (demo PWA)

A clickable demo of the technician and manager app. Nothing here connects to a server or Google Calendar.

## Put it online with GitHub Pages
1. On github.com, create a new repository (public is simplest), e.g. `pool-app`.
2. Upload every file in this folder to the repository root (Add file > Upload files). `index.html` must be at the top level.
3. Go to Settings > Pages. Under "Build and deployment", set Source to "Deploy from a branch", branch `main`, folder `/ (root)`, then Save.
4. After a minute or two the site is at `https://YOUR-USERNAME.github.io/pool-app/`. Send that link to Dan.

## Install on a phone
- iPhone: open the link in Safari, tap Share, then "Add to Home Screen".
- Android: open in Chrome, tap the menu, then "Install app" or "Add to Home screen".

## Things to know
- Demo data is stored in the browser on each device, so two phones don't share jobs. The demo always shows the current week, with sample jobs on today, and the sample data resets each new day. "Reset demo data" is at the bottom of the manager's Week screen.
- Sign-in is a demo picker (Sam as technician, Alex as manager). There are no real accounts.
- Customers and phone numbers are made up.
- After changing files, edit the version in `sw.js` (`sps-v1` to `sps-v2`) so phones pick up the update.
