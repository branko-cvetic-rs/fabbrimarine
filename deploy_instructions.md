# GitHub Pages Deployment Instructions

## Step 1: Create GitHub Repository
1. Go to https://github.com/new
2. Repository name: `fabbrimarine` (or your preferred name)
3. Set to **Public** (required for free GitHub Pages)
4. **DO NOT** initialize with README, .gitignore, or license
5. Click "Create repository"

## Step 2: Add Remote and Push
After creating the repository, run these commands (replace YOUR_USERNAME with your GitHub username):

```bash
git remote add origin git@github.com:YOUR_USERNAME/fabbrimarine.git
git push -u origin main
```

## Step 3: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click "Settings" tab
3. Scroll to "Pages" in the left sidebar
4. Under "Source", select "Deploy from a branch"
5. Select branch: `main`
6. Select folder: `/ (root)`
7. Click "Save"

Your site will be available at:
https://YOUR_USERNAME.github.io/fabbrimarine/

## Important Notes
- The `.nojekyll` file is already in place (required for GitHub Pages)
- Your site is ready for static hosting
- Changes pushed to `main` branch will automatically update the site
