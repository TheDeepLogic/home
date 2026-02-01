# GitHub Pages Setup Instructions

This repository contains a static HTML homepage for TheDeepLogic's GitHub profile.

## Enabling GitHub Pages

To enable GitHub Pages for this repository:

1. Go to the repository Settings
2. Navigate to "Pages" in the left sidebar
3. Under "Source", select the branch you want to deploy (e.g., `main` or `copilot/add-homepage-github-pages`)
4. Select the root directory `/` as the folder
5. Click "Save"

GitHub Pages will automatically deploy your site to: `https://thedeeplogic.github.io/home/`

## Local Development

To test the site locally:

```bash
# Start a simple HTTP server
python3 -m http.server 8080

# Open your browser to http://localhost:8080
```

## Site Structure

- `index.html` - Main homepage with all content
- `style.css` - Retro computing theme with CRT effects
- `.nojekyll` - Disables Jekyll processing (ensures static files are served as-is)

## Features

- **Vintage CRT Monitor Theme**: Green phosphor colors, scanlines, and glow effects
- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Repository Showcase**: Displays all repositories with their banner images
- **No Build Step**: Pure HTML/CSS, no compilation or build process needed

## Customization

To add new projects or update content:

1. Edit `index.html` to add new project cards
2. Follow the existing format for consistency
3. Use banner images from your repositories (via raw.githubusercontent.com URLs)
4. Commit and push - GitHub Pages will automatically update

## Browser Compatibility

The site uses modern CSS features and should work in all current browsers. The fonts are loaded from Google Fonts:
- VT323 - Primary retro terminal font
- Share Tech Mono - ASCII art font
