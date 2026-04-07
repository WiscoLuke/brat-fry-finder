# 🌭 Brat Fry Finder

**Wisconsin's #1 Brat Fry Directory** — Find community brat frys, cookouts & fundraisers happening near you.

## Live Demo

Visit: `https://<your-username>.github.io/brat-fry-finder/`

## Features

- Browse and search brat fry listings across Wisconsin
- Interactive Google Maps integration
- Submit your own brat fry event
- Sponsored listing option ($25) with priority placement
- Flyer/menu upload support
- Mobile-friendly responsive design

## Deploying to GitHub Pages

1. Create a new repository on GitHub (e.g. `brat-fry-finder`)
2. Push this code:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/<your-username>/brat-fry-finder.git
   git push -u origin main
   ```
3. Go to **Settings → Pages** in your GitHub repo
4. Under **Source**, select **Deploy from a branch**
5. Choose **main** branch and **/ (root)** folder
6. Click **Save**
7. Your site will be live at `https://<your-username>.github.io/brat-fry-finder/` within a few minutes

## Note

This is a proof-of-concept / prototype. The sample data is hardcoded and submissions are stored in-memory only (they reset on page reload). A production version would need a backend database and API.
