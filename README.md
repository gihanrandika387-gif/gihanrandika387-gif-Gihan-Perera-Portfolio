# Gihan Shevon Perera — Portfolio

Static one-file portfolio, ready for GitHub and Vercel. All images and styles are embedded in `index.html`.

## Publish

1. Create a public GitHub repository.
2. Upload `index.html`, `README.md`, and `vercel.json` directly to its root.
3. Import the repository at https://vercel.com/new. Select **Other** framework; no build command.
4. Open the **production domain** from Vercel → Settings → Domains.

### Fix included

The page script is placed at the end of the document, after the elements it uses. Page content is visible by default, so it cannot disappear if an animation fails to run. The portrait and project logos remain embedded in the HTML.

Check your project descriptions and contact details before sharing with clients.
