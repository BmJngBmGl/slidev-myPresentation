# Slidev on GitHub Pages (No Local Build)

This repository builds and deploys your Slidev deck via GitHub Actions. Just edit `slides.md` and push to `main`.

## Setup
1. Ensure the default branch is `main`.
2. Go to **Settings → Pages** and set **Source** to the **`gh-pages`** branch (created by the first deployment).
3. Your slides will be available at:
   - User/org site repo (`<user>.github.io`): `https://<user>.github.io/`
   - Project repo: `https://<user>.github.io/<repo>/`

## Editing
- Edit `slides.md` right in GitHub → Commit → GitHub Actions deploys automatically.

## Local (optional)
If you ever want to preview locally:
```bash
npm i
npm run dev
```

## License
MIT
