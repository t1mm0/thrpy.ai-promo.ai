# THRPY Teaser Page - Deployment Package

This folder contains a standalone HTML page ready for deployment to https://thrpy.ai

## Files Structure

```
teaser-deploy/
├── index.html          # Main HTML file
├── assets/             # All image assets
│   ├── THRPY.AI-LOGO-final2026.svg
│   ├── THRPY_GFX_Wallpaper.svg
│   ├── blurple-blob.svg
│   ├── rorange-rob.svg
│   ├── furple-heart.svg
│   ├── star1.svg
│   ├── star2.svg
│   ├── star3.svg
│   └── thrpy-promo.png
└── README.md           # This file
```

## Deployment Instructions

1. Upload the entire `teaser-deploy` folder contents to your web server
2. Ensure `index.html` is accessible at the root or desired path
3. All assets are referenced with relative paths (`assets/...`)
4. Fonts are loaded from CDN (Google Fonts and CDN Fonts)

## Features

- Standalone HTML file (no dependencies)
- Responsive design
- Animated background elements (blobs, hearts, sparkles)
- Clickable elements:
  - "Three free months..." → https://beta.thrpy.ai/promo
  - App icon → https://beta.thrpy.ai
  - "sneak a peak" → https://beta.thrpy.ai

## Browser Compatibility

Works in all modern browsers that support:
- CSS Grid/Flexbox
- CSS Animations
- ES6 JavaScript

## Notes

- All paths are relative, so the folder structure must be maintained
- Fonts load from external CDNs
- No build process required - ready to deploy as-is
