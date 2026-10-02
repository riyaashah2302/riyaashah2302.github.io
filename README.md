# Riya XYZ Portfolio

This repository contains the static portfolio site for Riya XYZ and is ready to be published on GitHub Pages.

## Project structure

- `index.html` — Home page
- `projects/` — Project case studies and category pages
- `experience/` — Experience pages
- `resume.html` — Resume page
- `contact.html` — Contact page
- `.nojekyll` — Required for GitHub Pages to preserve static assets

## Deploy to GitHub Pages

### 1) Create a GitHub repository

- Open GitHub and create a new repository.
- Use the naming convention `yourusername.github.io` so it is published at `https://yourusername.github.io`.

### 2) Push the site

Run the following commands in your terminal:

```bash
cd /Users/riyashah/Desktop/Portfolio/riyaashah2302.github.io
git init
git add .
git commit -m "Deploy portfolio site"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git push -u origin main
```

### 3) Enable Pages in GitHub

1. Open the repository in GitHub.
2. Go to Settings → Pages.
3. Select "Deploy from a branch".
4. Set the branch to `main` and the folder to `/ (root)`.
5. Save the settings.

The site should go live within a couple of minutes.

> Important: keep the `.nojekyll` file in place. It prevents GitHub Pages from processing the site as a Jekyll project.

## Notes

- The site is a fully static portfolio built for fast publishing and minimal configuration.
- Generated Next.js assets under `_next/` are included for the deployed build and should not be removed unless rebuilding the site from the source project.
