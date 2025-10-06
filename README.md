# DataSurface Website

This repository contains the source code for the DataSurface website, hosted on GitHub Pages at datasurface.com.

## Quick Start

This is a Jekyll-based GitHub Pages website. The main content is in `index.md`, which you can edit to customize the homepage.

### Files Overview

- `index.md` - Homepage template (customize this for your content)
- `_config.yml` - Jekyll configuration for GitHub Pages
- `Gemfile` - Ruby dependencies for local development
- `.gitignore` - Excludes build artifacts and dependencies

### Customization

1. Edit `index.md` to update the homepage content
2. Update `_config.yml` with your actual:
   - Site title and description
   - Contact information
   - Social media handles
   - Domain URL

### Local Development (Optional)

If you want to preview changes locally:

```bash
bundle install
bundle exec jekyll serve
```

Visit `http://localhost:4000` to see your site.

### GitHub Pages Deployment

Changes pushed to the main branch will automatically deploy to GitHub Pages. Make sure to:

1. Enable GitHub Pages in repository settings
2. Set source to "Deploy from a branch" and select your main branch
3. Optionally configure a custom domain in repository settings
