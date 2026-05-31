# Birthday Page

Simple static birthday page with audio, photos, and a video.

How to publish to GitHub Pages

1. Create a GitHub repository and push this folder (or use `gh`):

```bash
git init
git add .
git commit -m "Initial commit - prepare for GitHub Pages"
git remote add origin https://github.com/<user>/<repo>.git
git branch -M main
git push -u origin main
```

2. On GitHub: Settings → Pages → Deploy from a branch → select `main` and `/ (root)` → Save.

Your site will be available at: `https://<user>.github.io/<repo>/` after a minute.

Notes
- Keep media files (audio/video/images) in the repo and referenced with relative paths (already set in `index.html`).
- For large media consider Netlify/Vercel or external storage.
- If you want, I can help push the repo if you provide remote access or run `gh` locally.
