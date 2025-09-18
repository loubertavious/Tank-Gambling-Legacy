# GitHub Pages Deployment Guide

## Files Added for Deployment

1. **index.html** - Landing page that redirects to the game
2. **.github/workflows/deploy.yml** - GitHub Actions workflow for automatic deployment

## Manual Setup Steps

Since Git isn't installed locally, here are the steps to set up GitHub Pages:

### Option 1: Using GitHub Web Interface

1. Go to your repository: `https://github.com/[your-username]/Tank-Gambling-Legacy`
2. Click on **Settings** tab
3. Scroll down to **Pages** section in the left sidebar
4. Under **Source**, select **GitHub Actions**
5. The workflow will automatically deploy when you push changes

### Option 2: Using GitHub Desktop

1. Open GitHub Desktop
2. Clone your repository
3. Copy the new files (`index.html` and `.github/workflows/deploy.yml`) to the repository folder
4. Commit and push the changes
5. GitHub Actions will automatically deploy to Pages

### Option 3: Install Git and Use Command Line

1. Install Git from https://git-scm.com/
2. Open Command Prompt or PowerShell
3. Navigate to your repository folder
4. Run these commands:
   ```bash
   git add .
   git commit -m "Add GitHub Pages deployment"
   git push origin main
   ```

## After Deployment

Once deployed, your game will be available at:
`https://[your-username].github.io/Tank-Gambling-Legacy/`

The `index.html` file will automatically redirect visitors to the game, so they don't see the README first.

## Files Structure

```
Tank-Gambling-Legacy/
├── index.html                          # Landing page (redirects to game)
├── tank_gambling_prototype_CRT_V_09_05.html  # Main game file
├── .github/
│   └── workflows/
│       └── deploy.yml                  # GitHub Actions deployment
├── music/                              # Music directory
├── README.md                           # Project documentation
├── LICENSE                             # MIT License
└── .gitignore                          # Git ignore file
```
