# Imtithaal Manuel — Eportfolio

A 4-page eportfolio (About, CV, Projects, Experience) built with plain HTML/CSS
in a baby-pink "circuit board" theme. No build tools needed — just upload and go.

## File structure
```
eportfolio/
├── index.html        (About / homepage)
├── cv.html            (CV page + download button)
├── projects.html      (5 course projects)
├── experience.html    (timeline of experience)
├── style.css           (all styling — one file, shared by every page)
├── images/             (all photos)
└── files/
    └── Imtithaal_Manuel_CV.pdf   (downloadable CV)
```

## How to publish it with GitHub Pages (free, no domain needed)

1. **Create a GitHub account** at github.com if you don't have one already.
2. **Create a new repository**
   - Click the **+** icon top-right → **New repository**
   - Name it `eportfolio` (or anything — but if you name it
     `<your-username>.github.io` it becomes your main GitHub homepage URL)
   - Set it to **Public**
   - Don't tick "Add a README" (you already have one)
   - Click **Create repository**
3. **Upload your files**
   - On the new repo page, click **uploading an existing file**
   - Drag in *everything inside this `eportfolio` folder* — `index.html`,
     `cv.html`, `projects.html`, `experience.html`, `style.css`, and the
     whole `images` and `files` folders (drag the folders in as-is; GitHub
     keeps the folder structure)
   - Scroll down, add a commit message like "first upload of eportfolio",
     click **Commit changes**
4. **Turn on GitHub Pages**
   - In your repo, go to **Settings** → **Pages** (left sidebar)
   - Under "Build and deployment" → **Source**, choose **Deploy from a branch**
   - Under **Branch**, choose `main` and folder `/ (root)`, click **Save**
   - Wait about a minute, then refresh — GitHub will show you a live link,
     usually `https://<your-username>.github.io/eportfolio/`
5. **That link is your hand-in.** Open it to double check every page loads,
   images appear, the nav links work, and the CV download button works.

## Making changes later
- Edit any file directly on GitHub (click the pencil icon on the file page),
  or edit locally and re-upload/replace the file.
- Every time you commit a change, GitHub Pages automatically rebuilds the
  live site within a minute or two.

## To-do for you
- [ ] Swap in your project reports where you see the "📎 Project report —
      coming soon" boxes on `projects.html` — either link a PDF (upload it to
      `files/` like the CV) or paste in a Google Drive link.
- [ ] Double-check alt text on images reads naturally if you add/replace photos.
- [ ] Update the LinkedIn link in the footer/nav if your profile URL changes.
