PAISA — money tracker (standalone app)
======================================

FILES (keep all five together in one folder)
  index.html      the whole app
  manifest.json   makes it installable
  sw.js           lets it work offline
  icon-192.png    home screen icon
  icon-512.png    splash / store icon

PUT IT ONLINE (free, ~2 minutes)
  Option A — Netlify Drop
    1. Go to app.netlify.com/drop
    2. Drag this whole folder onto the page
    3. You get a link like https://paisa-xyz.netlify.app — share that

  Option B — GitHub Pages
    1. Create a public repo, upload all five files to the root
    2. Settings > Pages > Source: main branch, / (root)
    3. Your link: https://<username>.github.io/<repo>/

  Note: it must be served over https:// for offline mode to work.
  Opening index.html directly from your phone's files still works,
  but without install or offline caching.

INSTALL ON A PHONE
  Android (Chrome): open the link > menu (⋮) > "Install app" / "Add to Home screen"
  iPhone (Safari):  open the link > Share > "Add to Home Screen"
  It then opens fullscreen with its own icon, like a normal app.

HOW DATA WORKS
  Everything is stored in the browser on each person's own phone.
  Nothing is uploaded, nothing is shared between friends —
  you cannot see their entries and they cannot see yours.
  The username is a label, not a password.
  Clearing browser data / site data deletes the entries,
  so use "Copy this month's summary" now and then as a backup.
