# Riya's Portfolio — GitHub Pages Deploy

This folder contains the **fully built static website** ready to deploy on GitHub Pages.

## How to Deploy

### Step 1 — Create a GitHub Repo
- Go to github.com and create a **new repository**
- Name it `yourusername.github.io` → your site will be live at `https://yourusername.github.io`

### Step 2 — Push this folder
Open Terminal and run:

```bash
cd /Users/ellerecon/Desktop/riya-portfolio-deploy
git init
git add .
git commit -m "Deploy portfolio site"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages
1. Go to your repo on GitHub → Settings → Pages
2. Under Source, select "Deploy from a branch"
3. Set branch to `main`, folder to `/ (root)`
4. Click Save

Your site will be live in ~1-2 minutes! 🎉

> NOTE: The .nojekyll file is required — do NOT delete it!
