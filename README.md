# Shubham — Video Editor Portfolio

A one-page portfolio site. It's plain HTML, so there's no build step and nothing to install.

## 1. Add your details
Open `index.html` and edit the block at the top marked **EDIT YOUR DETAILS HERE**:
- `whatsapp`, `email`, `instagram`, `youtube`, `linkedin`
- `WORK`: one line per video (title, client, category, file or YouTube ID)

To change the text (headline, stats, about), search for it in `index.html` and type over it.

## 2. Add your videos
Copy the files into the `videos/` folder (see `videos/PUT-YOUR-VIDEOS-HERE.txt`).
- Short ads/reels: mp4 under ~20 MB each
- Long YouTube edits: upload to YouTube as **Unlisted**, then use `youtube: "VIDEO_ID"`

Preview: double-click `index.html` to open it in your browser.

## 3. Put it online for free (Vercel)
1. Create a free account at https://github.com and make a new repository called `shubham-portfolio`.
2. Upload everything in this folder: on the repo page, click **Add file → Upload files** and drag the files in.
3. Go to https://vercel.com, sign up with GitHub, click **Add New → Project**, pick the repo, and click **Deploy**.
4. Your site is live at `shubham-portfolio.vercel.app` (you can rename the project to change the address).

To update the site later, upload the changed files to GitHub. Vercel puts the new version live automatically.

Optional: buy a domain (about ₹800/year) and add it under Vercel → Project → Settings → Domains.

> GitHub's web upload accepts files up to 25 MB each. Keep videos under that limit, or use YouTube for big ones.
