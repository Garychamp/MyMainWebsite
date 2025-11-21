# Deployment Status

## ✅ This website IS deployed

This repository contains source code for a personal website project that is **automatically deployed** to GitHub Pages.

### Where is it deployed?

The website is live at: [https://garychamp.github.io/MyMainWebsite](https://garychamp.github.io/MyMainWebsite)

### How does deployment work?

- **Automatic Deployment**: Changes pushed to the `main` branch are automatically deployed via GitHub Actions
- **Manual Deployment**: Can also be triggered manually from the Actions tab
- **Build Time**: Typically takes 1-2 minutes to deploy changes

### Viewing the Website

You can view the website in two ways:

1. **Online**: Visit [https://garychamp.github.io/MyMainWebsite](https://garychamp.github.io/MyMainWebsite)
2. **Locally**: Clone this repository and open `index.html` in a web browser, or use a local development server (e.g., `python -m http.server` or VS Code Live Server)

### Deployment Configuration

The deployment is configured through GitHub Actions workflow (`.github/workflows/deploy.yml`) which:
- Triggers on push to main branch
- Uses GitHub Pages for hosting
- Deploys all static files (HTML, CSS, JS, media)

---

**Last Updated:** November 2025  
**Status:** Deployed to GitHub Pages
