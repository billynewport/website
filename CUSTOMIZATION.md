# DataSurface Website Customization Guide

## Quick Customization Checklist

### 1. Update Site Configuration (`_config.yml`)

Edit these key settings:
- `title`: Your site title
- `email`: Your contact email
- `description`: Site description for SEO
- `url`: Your actual domain (e.g., "https://datasurface.com")
- `twitter_username`: Your Twitter handle
- `linkedin_username`: Your LinkedIn profile

### 2. Customize Homepage Content (`index.md`)

**Sections to update:**
- Company description and value proposition
- Services offered (replace with your actual services)
- Contact information (email, phone, address)
- About section with your company story

**Easy customization points marked in the template:**
- Look for sections marked with *"Edit this section..."*
- Replace placeholder contact information
- Update service descriptions
- Add your company's unique value proposition

### 3. Enable GitHub Pages

1. Go to your repository settings
2. Navigate to "Pages" section
3. Set source to "Deploy from a branch"
4. Select your main branch (or the branch with your content)
5. Save the settings

### 4. Optional: Custom Domain

If you own datasurface.com:
1. Add a CNAME file with your domain
2. Configure DNS to point to GitHub Pages
3. Update the `url` in `_config.yml`

### 5. Local Development

To preview changes locally:
```bash
bundle install
bundle exec jekyll serve
```

## Next Steps

- Replace placeholder content with your actual business information
- Add your logo and branding
- Create additional pages (about.md, services.md, contact.md)
- Customize the theme or add custom CSS