SAREE CUTTING PLANNER - PWA PACKAGE
===================================

UPLOAD (Netlify Drop - easiest)
1. Unzip this file. You get a folder "saree-planner".
2. Open https://app.netlify.com/drop in a browser.
3. Drag the whole "saree-planner" folder onto the page.
4. You get a link like https://something.netlify.app - share it with the team.
   Create a free Netlify account to keep the site and rename the link.

INSTALL ON PHONES
- Android (Chrome): open the link > menu (3 dots) > "Install app" / "Add to Home screen".
- iPhone (Safari): open the link > Share > "Add to Home Screen".
- Open it once while online; after that it works offline.

UPDATING THE APP LATER
1. Replace index.html with the new version.
2. In sw.js change  const VERSION = "v1";  to "v2" (then "v3", ...).
3. Upload the folder again (Netlify: your site > Deploys > drag the folder).
Phones get the update the next time they open the app online.

FILES
index.html            the calculator
manifest.webmanifest  app name, colours, icons
sw.js                 offline support
icon-*.png            app icons

Must be hosted on HTTPS. Netlify, Cloudflare Pages and GitHub Pages all are.
