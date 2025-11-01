# Muttukadu Lakefront Villa Website

A modern, fast, and responsive single-page website for showcasing a luxury lakefront villa in Muttukadu, India.

## Features

- **Fully optimized images**: All images locally hosted and optimized for fast loading
- **Lazy loading**: Images load only when scrolled into view
- **Responsive design**: Works perfectly on mobile, tablet, and desktop
- **Zero external dependencies**: No reliance on third-party image hosting
- **SEO optimized**: Proper meta tags and semantic HTML
- **Fast loading**: ~9.4MB total size with optimized JPEGs

## Project Structure

```
website_smriti/
├── index.html              # Main website file
├── images/                 # All property images (15 optimized JPEGs)
│   ├── hero.jpg
│   ├── front-exterior.jpg
│   ├── lakefront.jpg
│   └── ...
└── luxury_villa_imgur_urls (1).csv  # Original image URL reference
```

## Deploying to GitHub Pages

### Step 1: Push to GitHub

```bash
git add .
git commit -m "Add optimized images and update website"
git push origin main
```

### Step 2: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings"
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select "main" branch
5. Click "Save"
6. Your site will be published at: `https://yourusername.github.io/website_smriti/`

### Step 3: Wait for Deployment

GitHub will automatically build and deploy your site. This usually takes 1-2 minutes.

## Performance Improvements Implemented

1. **Local Image Hosting**: All images downloaded from Imgur and hosted locally
2. **Image Optimization**: JPEGs optimized to 85% quality (reduced file sizes)
3. **Lazy Loading**: Images load only when needed (`loading="lazy"` attribute)
4. **Hero Image Preload**: Critical hero image preloaded for instant display
5. **Responsive Images**: Images adapt to different screen sizes
6. **No External Dependencies**: Removed Imgur embed scripts

## Local Testing

To test the website locally:

```bash
# Option 1: Using Python 3
python3 -m http.server 8000

# Option 2: Using PHP
php -S localhost:8000

# Then open http://localhost:8000 in your browser
```

## Future Enhancements (Optional)

If you want to further optimize the website:

1. **WebP Conversion**: Convert JPEGs to WebP format for 50-80% additional file size reduction
2. **Responsive Images**: Create multiple sizes for different devices
3. **Image CDN**: Use Cloudflare or ImageKit for global CDN delivery
4. **Progressive Loading**: Add blur-up placeholders for better perceived performance

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Contact Information

For property inquiries:
- Phone: +1 (312) 442-2343 or +91 98400 24528
- Email: rochitav@gmail.com

## License

All images and content are proprietary and belong to the property owner.
