# Gihan Shevon Perera — Portfolio | FINAL IMAGE FIX

## What was fixed

The corporate showcase images previously used relative URLs such as
`assets/print-corporate/calendar-mockup.webp`. Those images could appear
blank after deployment if the `assets` folder was not uploaded to the
exact correct directory. The final `index.html` now embeds **all five**
corporate mockups directly in the HTML. Every image is visible even if
the `index.html` file is deployed alone, without an `assets` directory.

Clicking any of the five images opens a full-size viewer. Works without
image server requests. The website retains all original project work,
updated corporate descriptions, desktop and mobile styles.

## Upload to your existing GitHub repository

1. Unzip this package on your computer.
2. Open the extracted folder and upload its **contents** to your GitHub
   repository root, not the ZIP and not a nested parent folder.
3. Confirm you can see `index.html` at the top level of your repository.
4. Commit the files. Vercel can redeploy this static site from GitHub;
   for GitHub Pages, set Pages source to Deploy from a branch (main / root).
5. Hard-refresh your website (Ctrl+Shift+R, or test in an incognito tab)
   if your browser still shows an earlier cached deployment.

The `assets/print-corporate/` folder contains editable copies of the mockups,
but **it is not required for viewing the images**.

## Updating the images later

Replace one or more `.webp` images in `assets/print-corporate/` with your
real design work, keeping the same filenames. Run `python tools/refresh_images.py`
once to refresh the image data embedded in `index.html`, then commit the
changed `index.html`. Python 3 is sufficient; no extra packages needed.

## Contents

- `index.html` — entire website, styles, scripts and embedded design images.
- `assets/print-corporate/` — editable WebP images (source copies).
- `tools/refresh_images.py` — optional image replacement helper.
- `vercel.json` — deployment configuration.
- `README.md` — this guide.

Note: Corporate designs are illustrative concept mockups, not documented
completed client commissions. Replace them with actual portfolio examples
as appropriate.
