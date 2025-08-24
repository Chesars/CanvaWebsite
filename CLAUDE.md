# Claude Configuration

This file contains configuration and commands for Claude Code to better assist with this project.

## Project Overview

This is a **static HTML + JavaScript website** designed for **GitHub Pages** deployment with custom domain support via `CNAME`. The project is primarily HTML-based (≈99.8%) with minimal JavaScript.

## Project Commands

### Local Development
- `python3 -m http.server 8000` - Start local server (recommended)
- Or simply open `index.html` directly in browser


## Project Structure

```
├─ index.html        # Main page
├─ sitemap.xml       # SEO sitemap  
├─ CNAME            # Custom domain for GitHub Pages
├─ images/          # Images and assets
├─ fonts/           # Web fonts
├─ js/              # JavaScript files
├─ AGENTS.md        # Internal documentation
└─ README.md        # Project documentation
```

## Deployment

- **Target:** GitHub Pages
- **Branch:** main (root directory)
- **Domain:** Custom domain configured via CNAME
- **URL Pattern:** `https://<username>.github.io/CanvaWebsite/`

## Notes for Claude

- This is a static site with no build process or package.json
- No linting/testing commands available
- Focus on HTML/CSS/JS editing directly
- Always test locally with Python server before suggesting changes
- Maintain existing file structure and naming conventions
- Be mindful of GitHub Pages compatibility