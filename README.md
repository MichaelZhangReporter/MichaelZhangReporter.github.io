# Journalism Portfolio (GitHub Pages starter)

This is a minimal, clean portfolio site you can host on GitHub Pages. It showcases *five* pieces:
- 3 internal pages on this site (edit the files: `article-data-story.html`, `article-feature.html`, `article-investigation.html`)
- 2 external live links (update the `href` URLs inside `index.html`)

## How to use

### 1) Fill in your content
- Replace `Your Name`, contact links, and the placeholder text in each file.
- Put images in `/assets` and update the `<img src="assets/...">` paths.
- For Datawrapper embeds, open each chart and copy the **Embed** code (iframe). Replace the `https://datawrapper.dwcdn.net/XXXX1/` and `XXXX2` URLs in `article-data-story.html` with your chart IDs.

### 2) Publish on GitHub Pages
**Option A: User/Org site (recommended if this is your primary homepage)**
1. Create a repository named **`USERNAME.github.io`** (replace USERNAME with your GitHub username).
2. Upload all files in this folder to that repo (drag-and-drop on GitHub or push via Git). Make sure `index.html` is in the root of the repo.
3. Visit `https://USERNAME.github.io` after a minute or two; your site should be live.

**Option B: Project site (if you want a subpath URL)**
1. Create a repository with any name, e.g., `portfolio`.
2. Upload files to the repo root.
3. Go to **Settings → Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**; pick the `main` branch and **/ (root)** folder. Save.
4. Your site will appear at `https://USERNAME.github.io/REPO-NAME/`.

> If you customize the branch/folder, keep `index.html` at the root of whatever you publish.

### 3) Local preview (optional)
You can open `index.html` in a browser directly. For cleaner local testing, run a local static server (e.g., `python3 -m http.server 8000` in this folder) and visit `http://localhost:8000`.

### 4) Customize
- Colors and layout live in `styles.css`.
- Add new pieces by cloning one of the article HTML pages and linking to it from `index.html`.
- Add analytics or metadata in the `<head>` section if desired.

### Notes
- The `.nojekyll` file disables Jekyll processing and ensures plain HTML/CSS are served as-is.
- Datawrapper iframes resize automatically via the included listener script.
- All pages are lightweight and accessible; no build step required.

---

**Happy publishing!**