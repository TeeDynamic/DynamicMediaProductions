# DynamicMediaPro Portfolio

Portfolio site for Adejumo Oluwatobi Emmanuel, video editor and motion specialist.
A single static page (`index.html`): no build step, no dependencies to install.

## Publish with GitHub Pages

1. Create a new repository on GitHub (for example `dynamicmediapro`).
2. Upload `index.html`, `videos.js`, `.nojekyll` and `README.md` to the repository root.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
5. Choose the `main` branch and the `/ (root)` folder, then click **Save**.
6. After a minute or two the site is live at `https://<your-username>.github.io/<repo-name>/`.

Tip: a repository named `<your-username>.github.io` is served at `https://<your-username>.github.io/`.

## Editing videos

The videos are listed in `videos.js`. There are two ways to change them.

**Edit on the page (easiest)**

1. Open your live site with `?edit` added to the address, for example `https://<your-username>.github.io/<repo-name>/?edit`.
2. Use the buttons that appear on each video: move earlier/later, edit, remove. Use **+ Add video** to add one (paste a Google Drive, YouTube, or direct `.mp4` link).
3. Click **Export videos.js**. A file downloads.
4. In your GitHub repository, upload that file to replace `videos.js`, then commit. The live site updates in a minute or two.

Your changes are a private draft in your browser until you export and upload. Visitors never see the edit tools or your draft, even if they add `?edit`.

**Edit by hand**

Open `videos.js` on GitHub (pencil icon) and change the lists. Each video needs a unique `id`, a `title`, a `category` (`youtube`, `commercials`, `events` or `social`), a `badge`, and one source: `youtubeId`, `gDriveId` with `type: "gdrive"`, or `videoUrl` with `type: "mp4"`. Videos go in the `vertical` (9:16) or `horizontal` (16:9) list.

Google Drive files must be shared as "Anyone with the link can view".

The WhatsApp number is in the `wa.me` links in `index.html` (search for `2348077140068`).

## Notes

- The logo and some video previews are hosted on `framerusercontent.com`. If you later delete the Framer project, download those files, add them to this repo, and update the links.
- Fonts, Tailwind and the icon set load from public CDNs, so the page needs an internet connection.
