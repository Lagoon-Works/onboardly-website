# Onboardly Website

A static website for Onboardly - Hire the top 1% non-tech talent.

## Deployment Options

### Option 1: Netlify (Recommended)

1. **Sign up for Netlify** at [netlify.com](https://netlify.com)
2. **Connect your GitHub repository:**
   - Push this code to GitHub
   - In Netlify dashboard, click "New site from Git"
   - Choose GitHub and select your repository
   - Set build command to: `echo "No build required"`
   - Set publish directory to: `.`
3. **Add your custom domain:**
   - Go to Site settings > Domain management
   - Add your domain
   - Follow the DNS configuration instructions

### Option 2: Vercel

1. **Sign up for Vercel** at [vercel.com](https://vercel.com)
2. **Deploy:**
   - Install Vercel CLI: `npm i -g vercel`
   - Run: `vercel`
   - Follow the prompts
3. **Add custom domain:**
   - Go to your project dashboard
   - Settings > Domains
   - Add your domain and configure DNS

### Option 3: GitHub Pages

1. **Push to GitHub** (already done)
2. **Enable GitHub Pages:**
   - Go to repository Settings > Pages
   - Source: Deploy from a branch
   - Branch: main
   - Folder: / (root)
3. **Add custom domain:**
   - In Pages settings, add your domain
   - Create a CNAME file in your repository

### Option 4: Traditional Web Hosting

For traditional hosting providers (cPanel, etc.):

1. **Upload files** to your hosting provider's public_html folder
2. **Configure domain** in your hosting control panel
3. **Set up SSL certificate** (usually free with hosting)

## File Structure

```
├── index                    # Main HTML file
├── css/                     # Stylesheets
├── js/                      # JavaScript files
├── images/                  # All images and assets
├── netlify.toml            # Netlify configuration
├── vercel.json             # Vercel configuration
└── README.md               # This file
```

## Features

- Responsive design
- Optimized for performance
- SEO-friendly
- Custom domain ready
- SSL certificate support

## Performance Optimizations

- Static file caching configured
- Security headers enabled
- Optimized image delivery
- CDN-ready deployment

## Support

For deployment issues, check the hosting provider's documentation or contact their support team. 