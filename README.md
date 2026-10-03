# STAKIP | Premium Streaming Platform

A custom streaming platform with Netflix-like interface featuring movies, series, documentaries, and exclusive originals. Built for the domain `stakip.website`.

## 🚀 Features

- **Animated Landing Page** - Beautiful entrance with the STAKIP brand
- **Interactive Start Button** - Smooth transition to the streaming homepage
- **Premium Dark UI** - Netflix-inspired dark theme with modern design
- **Search Functionality** - Real-time search across all content
- **Content Categories**:
  - Trending Now
  - Movies
  - Series
  - Documentaries
  - Mr. Robot (Complete Seasons)
- **Responsive Design** - Works on desktop, tablet, and mobile
- **Smooth Animations** - Beautiful hover effects and transitions

## 🛠️ Deployment to stakip.website

### Option 1: GitHub Pages (Free & Easy)
1. Go to repository Settings → Pages
2. Select "Deploy from a branch"
3. Choose `main` branch, `/root` folder
4. Your site will be live at `https://stakip.github.io/stakip-streaming`
5. Then point your domain to GitHub Pages via DNS

### Option 2: Vercel (Recommended - Free & Fast)
1. Visit [vercel.com](https://vercel.com)
2. Connect your GitHub account
3. Import this repository
4. Add your domain `stakip.website` in project settings
5. Vercel will auto-generate SSL and deploy

### Option 3: Netlify (Free & Easy)
1. Visit [netlify.com](https://netlify.com)
2. Connect GitHub repository
3. Deploy (auto-builds from main)
4. Add custom domain `stakip.website` in Site Settings

## 📋 Domain Setup Steps

After deploying to a hosting platform:

1. **Purchase Domain** (Already done: `stakip.website`)
2. **Point Domain to Hosting**:
   - For GitHub Pages: Add CNAME record pointing to `stakip.github.io`
   - For Vercel: Vercel handles this automatically
   - For Netlify: Add Netlify's DNS records

3. **DNS Configuration**:
   - A Record: `185.199.108.153`
   - CNAME: Depends on your hosting platform

## 📁 Project Structure

```
stakip-streaming/
├── index.html          # Main landing & home page
├── styles.css          # All styling & animations
├── script.js           # Search & interactivity logic
└── README.md           # This file
```

## 🎬 Content Data

All content is managed in `script.js` - easily add more:
- Movies
- TV Series
- Documentaries
- Mr. Robot episodes (all 4 seasons included)

## 🎨 Customization

Edit `script.js` to add:
- Your own movie/series data
- Change content images
- Modify colors in `styles.css` (CSS variables at top)
- Add more sections

## 📱 Responsive Breakpoints

- Desktop: Full 6-column grid
- Tablet (1100px): 3-column grid
- Mobile (820px): 2-column grid + stacked navigation

## 🔧 Development

No build process needed - just edit and push to GitHub!

```bash
# Clone locally
git clone https://github.com/STakip/stakip-streaming.git
cd stakip-streaming

# Open in browser
open index.html
```

## 🚀 Next Steps

1. Deploy to hosting platform (Vercel recommended)
2. Point `stakip.website` domain
3. Customize content in `script.js`
4. Add more movies/series
5. Optional: Add video player functionality

## 📞 Support

For deployment help:
- [Vercel Docs](https://vercel.com/docs)
- [Netlify Docs](https://docs.netlify.com)
- [GitHub Pages Docs](https://pages.github.com)

---

**STAKIP Streaming** © 2026. All rights reserved.
