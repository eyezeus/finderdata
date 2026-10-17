# My Data Finder

A static browser-based Excel/CSV search page. It searches records locally in the user's browser and does not upload the selected file to a server.

## Run locally
Open `index.html` in a modern browser. Internet is needed to load the SheetJS library from jsDelivr for Excel parsing.

## Publish with GitHub Pages
1. Open **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/(root)`, then Save.
3. Wait for GitHub Pages to publish the site. The URL will be `https://eyezeus.github.io/finderdata/`.

## Privacy
Do not commit real personal records, Excel files, PAN numbers, phone numbers, or email lists to a public repository. This page processes the file selected by the user locally in their browser. The page itself is public when hosted on GitHub Pages; only use it with data you are authorized to access.
