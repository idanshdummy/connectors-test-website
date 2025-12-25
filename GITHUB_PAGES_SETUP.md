# GitHub Pages Setup Instructions

## Step 1: Create GitHub Repository

1. Go to https://github.com/new
2. Repository name: `connectors-test-website` (or your preferred name)
3. Choose Public or Private
4. **DO NOT** initialize with README, .gitignore, or license
5. Click "Create repository"

## Step 2: Add GitHub Remote and Push

After creating the repository, GitHub will show you the repository URL. Use one of these commands:

### If using SSH (recommended):
```bash
git remote add github git@github.com:YOUR_USERNAME/connectors-test-website.git
git push -u github main
```

### If using HTTPS:
```bash
git remote add github https://github.com/YOUR_USERNAME/connectors-test-website.git
git push -u github main
```

Replace `YOUR_USERNAME` with your actual GitHub username.

## Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on **Settings** (top menu)
3. Scroll down to **Pages** in the left sidebar
4. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
5. Click **Save**

## Step 4: Access Your Site

Your website will be available at:
- `https://YOUR_USERNAME.github.io/connectors-test-website/`

It may take a few minutes for the site to be published. GitHub will show you the URL once it's ready.

## Note

You can keep both remotes:
- `origin` → Salesforce Git (git.soma.salesforce.com)
- `github` → GitHub

To push to both:
```bash
git push origin main    # Push to Salesforce Git
git push github main    # Push to GitHub
```

