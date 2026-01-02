# GitHub Pages Setup Guide

This guide will help you deploy the ViP Officer Credit Tracking System presentation to GitHub Pages.

## Prerequisites

- Repository created: `vip-tracker-proposal`
- Repository cloned locally to: `~/localdev/vip/vip-tracker-proposal`
- Files committed to the repository

## Step 1: Commit and Push the Files

From your local repository directory:

```bash
cd ~/localdev/vip/vip-tracker-proposal

# Add all presentation files
git add index.html assets/ docs/

# Commit the files
git commit -m "Add ViP tracker proposal presentation"

# Push to GitHub
git push origin main
```

## Step 2: Enable GitHub Pages

1. Go to your repository on GitHub: `https://github.com/[your-username]/vip-tracker-proposal`

2. Click on **Settings** (top navigation)

3. In the left sidebar, click on **Pages**

4. Under "Build and deployment":
   - **Source**: Select "Deploy from a branch"
   - **Branch**: Select `main` and `/ (root)`
   - Click **Save**

5. GitHub will now build and deploy your site. This takes 1-2 minutes.

## Step 3: Access Your Presentation

Your presentation will be available at:

```
https://[your-username].github.io/vip-tracker-proposal/
```

Replace `[your-username]` with your actual GitHub username.

## Step 4: Share the Link

Copy the URL and share it with Community Owners. They can:
- View the presentation in their browser
- Navigate with arrow keys or on-screen controls
- View on any device (mobile, tablet, desktop)

## Viewing the Presentation

### Navigation Controls

- **Arrow Keys**: Navigate between slides
- **Space**: Next slide
- **Shift + Space**: Previous slide
- **ESC**: Overview mode (shows all slides)
- **?**: Help (show keyboard shortcuts)

### On-Screen Controls

- Bottom-right corner: Arrow buttons for navigation
- Bottom-left corner: Slide number

## Making Updates

If you need to update the presentation:

```bash
cd ~/localdev/vip/vip-tracker-proposal

# Make your edits to index.html or CSS files

# Commit and push changes
git add .
git commit -m "Update presentation content"
git push origin main
```

GitHub Pages will automatically rebuild and deploy your changes within 1-2 minutes.

## Testing Locally (Optional)

To preview the presentation locally before pushing:

```bash
cd ~/localdev/vip/vip-tracker-proposal

# Start a simple HTTP server (Python 3)
python3 -m http.server 8000

# Or using Node.js (if you have npx)
npx serve
```

Then open your browser to: `http://localhost:8000`

## Troubleshooting

### Presentation doesn't load

- **Check GitHub Pages status**: Settings → Pages → should show "Your site is published at..."
- **Wait**: Initial deployment can take 2-3 minutes
- **Clear cache**: Hard refresh your browser (Cmd+Shift+R on Mac, Ctrl+Shift+R on Windows)

### Styles look broken

- **Check file paths**: Ensure `assets/css/` files are committed
- **Check console**: Open browser developer tools (F12) and check for errors

### Changes not appearing

- **Verify push**: Run `git log` to see if your commit is in the repository
- **Wait**: GitHub Pages can take 1-2 minutes to rebuild
- **Hard refresh**: Clear browser cache and reload

## Repository Structure

```
vip-tracker-proposal/
├── index.html                 # Main presentation file
├── assets/
│   ├── css/
│   │   ├── custom.css         # ViP styling
│   │   └── discord-mockups.css # Discord interface styles
│   └── js/
│       └── reveal-config.js    # Presentation configuration
├── docs/
│   └── setup.md               # This file
└── README.md                  # Repository README
```

## Additional Resources

- [Reveal.js Documentation](https://revealjs.com/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Markdown Guide](https://www.markdownguide.org/) (if you add content in Markdown)

## Questions?

If you encounter any issues with the setup, check:
1. GitHub repository settings
2. File paths in index.html
3. Browser console for errors
4. GitHub Pages build status
