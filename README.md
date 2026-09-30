# M39029 Contact ID

Free quick reference for identifying M39029 crimp contacts by color band, with DMC crimp and insertion/removal tooling. Runs entirely in the browser, installs to a phone home screen, and works offline once installed.

Not approved maintenance data. Not affiliated with Daniels Manufacturing Corporation. Provided as-is.

## Publish on GitHub Pages (free, no coding)

1. Make a free account at github.com.
2. Click **New repository**. Name it something like `m39029-contact-id`, set it to **Public**, and create it.
3. On the repo page, click **Add file > Upload files**. Drag in everything from this folder, including the hidden `.nojekyll` file (on a Mac press Cmd+Shift+. to show it). Click **Commit changes**.
4. Go to **Settings > Pages**. Under Source pick **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
5. After a minute or two the site is live at `https://<your-username>.github.io/m39029-contact-id/`.

## Alternative: Netlify Drop

Go to app.netlify.com/drop and drag this folder onto the page. You get a live HTTPS link right away (make a free account to keep it).

## Updating

Replace the changed files, then open `sw.js` and bump `VERSION` (e.g. `contact-id-v3`) so installed copies refresh.

## Installing on a phone

- iPhone: open the link in Safari > Share > Add to Home Screen
- Android: open in Chrome > Install app (or menu > Add to Home screen)

Open it in a real browser, not inside another app's built-in viewer, or the camera buttons may not work.
