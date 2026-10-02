ALGEBRA 1 SESSIONS - offline app

Everything runs on the phone. No account, no internet needed after setup.
Progress is stored on the device; use Progress > Backup to save a copy.

BEST: install to the home screen (iPhone or Android, works offline)
  1. Put this whole folder on any static web host. Easiest options:
       - Netlify Drop: drag the folder onto app.netlify.com/drop
       - GitHub Pages: push the folder to a repo, enable Pages
       - Or any web server you already have (IIS, nginx, etc.)
  2. Open the link once on the phone (Safari on iPhone, Chrome on Android).
  3. iPhone: Share > Add to Home Screen.  Android: menu > Install app.
  4. It now opens like an app and works with no connection.

QUICK: just the file
  - Android / desktop: copy index.html to the device and open it in Chrome
    or a browser. Works offline, saves progress in that browser.
  - iPhone: opening an HTML file from the Files app only shows a preview
    and won't save progress. Use the home-screen route above instead.

UPDATING
  If you edit index.html on a host, also change VERSION in sw.js
  (e.g. alg1-v2) so installed copies pick up the new version.
