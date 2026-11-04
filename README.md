# Gihan Perera — Portfolio Website (Final GitHub Release)

A complete, ready-to-deploy static portfolio website, including the existing development projects, the Print & Outdoor Advertising collection, and all five Corporate Print & Publications projects.

## Install / publish via GitHub

1. Extract this ZIP on your computer.
2. Open your **existing portfolio repository** on GitHub and choose **Add file → Upload files**.
3. Upload the files inside the extracted folder, retaining `index.html`, `vercel.json`, `.gitignore`, `README.md` and the `assets` folder at the **repository root**. Replace existing files with the same names.
4. Commit changes to the branch connected to your Vercel deployment.
5. In Vercel, verify the new deployment is ready; hard-refresh the website (`Ctrl + Shift + R`).

**Important:** Do not upload the ZIP file itself to GitHub as a website source, and do not place `index.html` inside a subfolder. Vercel should use the root folder as the project's root directory.

## Included

- `index.html`: the complete self-contained portfolio website, including the five embedded corporate mockup images, CSS and JavaScript.
- `assets/print-corporate/`: optional separate WebP versions of the same concept images, included for source management and a JavaScript-free fallback for opening images.
- `vercel.json`: static site deployment configuration.
- `.gitignore`: repository ignore rules.

## Gallery improvements

- All 8 print and corporate projects have their descriptions and tags.
- Corporate gallery maximum width prevents excessive enlargement of the supplied mockups.
- Consistent two-column cards on desktop and one-column cards on small screens, aligned card text and pill tags.
- Embedded images prevent missing-file problems on deployment.
- Accessible image preview modal opens without requesting the separate image files.

**Image quality note:** The mockups are illustrative images generated as concepts. The layout now avoids unnecessarily upscaling their original raster detail; replacing them with higher-resolution original artwork is the way to improve text-level sharpness further.
