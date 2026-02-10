# Customization Guide

## Quick Setup

1. **Update Site Config**
   - Edit `src/data/siteConfig.js`
   - Change name, tagline, description, socials, and email

2. **Update Pages**
   - Edit pages in `src/pages/`
   - Add/remove pages as needed
   - Content is in `.astro` format (HTML + frontmatter)

3. **Customize Styles**
   - Edit `src/styles/global.css`
   - Change colors, fonts, spacing
   - Dark theme defaults included

4. **Add Images**
   - Place images in `public/images/`
   - Reference as `/images/filename.jpg` in pages

5. **Deploy to Netlify**
   - Connect GitHub repo to Netlify
   - Netlify automatically builds and deploys on push
   - No additional config needed (netlify.toml is ready)

## File Structure Explanation

- `src/pages/` - Page files (auto-routed)
- `src/layouts/` - Reusable page layouts
- `src/components/` - Reusable components
- `src/data/` - Data files (config, etc.)
- `src/styles/` - Global CSS
- `public/` - Static assets

## Environment Variables

Create `.env.local` for environment variables:
```
PUBLIC_SITE_URL=https://yoursite.com
```

## Adding More Pages

1. Create new `.astro` file in `src/pages/`
2. Import `BaseLayout` and wrap content
3. Link from navigation in `BaseLayout.astro`

## Need Help?

- Astro docs: https://docs.astro.build
- Netlify docs: https://docs.netlify.com