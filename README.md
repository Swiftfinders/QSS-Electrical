# QSS Electrical - Premium Website

A modern, high-end single-page website for QSS Electrical, a Southern Ontario-based electrical contracting company. Built for lead generation and portfolio showcase.

## 🌟 Features

- **Modern Luxury Design**: Clean, professional, minimalist aesthetic
- **Fully Responsive**: Mobile-first design optimized for all devices (320px to 1920px+)
- **Premium Color Scheme**: Deep navy (#1a2940) and electric blue (#0066FF)
- **Smooth Animations**: Scroll-triggered fade-in and slide-up effects
- **SEO Optimized**: Proper semantic HTML structure with h1-h6 hierarchy
- **High Performance**: Inline critical CSS, optimized images
- **Netlify Forms**: Integrated contact/quote form with success page
- **Accessibility**: High contrast design for better readability

## 📋 Sections

1. **Navigation Header** - Fixed/sticky nav with smooth scroll links
2. **Hero Section** - Bold headline with professional imagery and CTA
3. **About/Why Us** - Trust points (Licensed, Insured, 24/7, Quick Response)
4. **Services** - 6 main services with professional images
5. **Portfolio/Gallery** - 6 project showcase images
6. **Testimonials** - 4 customer reviews with ratings
7. **Why Choose QSS** - 3 key differentiators
8. **Quote Form** - Netlify-compatible contact form
9. **Footer** - Complete contact info, hours, and links

## 🚀 Deployment to Netlify

### Option 1: Drag & Drop (Easiest)
1. Create a ZIP file of this repository (or just drag the folder)
2. Go to [Netlify Drop](https://app.netlify.com/drop)
3. Drag and drop the folder
4. Your site will be live instantly!

### Option 2: Git Integration (Recommended)
1. Push this repository to GitHub
2. Log into [Netlify](https://netlify.com)
3. Click "Add new site" → "Import an existing project"
4. Connect to your GitHub repository
5. Build settings:
   - **Build command**: (leave empty)
   - **Publish directory**: `.` (root)
6. Click "Deploy site"

### Option 3: Netlify CLI
```bash
# Install Netlify CLI
npm install -g netlify-cli

# Login to Netlify
netlify login

# Deploy
netlify deploy --prod
```

## 🎨 Customization

### Update Contact Information
Edit `index.html` and `success.html`:
- Phone number: Search for `(905) 555-1234`
- Email: Search for `info@qsselectrical.ca`
- Service area: Search for "Southern Ontario"

### Change Colors
Update CSS variables in `index.html` (around line 18):
```css
:root {
    --navy: #1a2940;
    --electric-blue: #0066FF;
    --light-bg: #f8f9fa;
}
```

### Replace Images
Images are sourced from Unsplash. To use your own:
1. Find image URLs in `index.html`
2. Replace Unsplash URLs with your own hosted images
3. Recommended: Use Cloudinary or Imgix for optimization

### Modify Form Fields
Edit the form section in `index.html` (search for `contact-quote`):
- Add/remove fields as needed
- Update dropdown options
- Netlify will auto-detect changes

## 📧 Form Setup

The contact form is configured for Netlify Forms:
- Form submissions appear in Netlify dashboard under "Forms"
- Email notifications can be configured in Netlify settings
- Form includes spam protection (honeypot field)
- Success page redirect to `/success/`

### Enable Email Notifications:
1. Go to Netlify dashboard → Forms
2. Click on "Form notifications"
3. Add email notification with your email address

## 🔧 Technical Details

- **Single HTML File**: All CSS and JavaScript inline for optimal performance
- **No External Dependencies**: Pure HTML, CSS, and JavaScript
- **Mobile-First**: Responsive breakpoints at 768px and 480px
- **Browser Support**: Modern browsers (Chrome, Firefox, Safari, Edge)
- **Performance**: Fast loading with optimized images and minimal code

## 📱 Responsive Breakpoints

- **Desktop**: 1920px+ (full layout)
- **Laptop**: 1200px - 1920px (standard layout)
- **Tablet**: 768px - 1199px (adjusted grid)
- **Mobile**: 320px - 767px (single column, hamburger menu)

## 🎯 Custom Domain Setup

1. In Netlify dashboard, go to "Domain settings"
2. Click "Add custom domain"
3. Enter your domain (e.g., `qsselectrical.ca`)
4. Follow DNS configuration instructions
5. Enable HTTPS (automatic with Netlify)

## 📊 SEO Checklist

- ✅ Semantic HTML structure
- ✅ Proper heading hierarchy (h1-h6)
- ✅ Meta description and keywords
- ✅ Alt text for images (update as needed)
- ✅ Mobile-friendly design
- ✅ Fast loading speed
- ⬜ Submit sitemap to Google Search Console (after deployment)
- ⬜ Add Google Analytics (optional)

## 🔒 Security Features

- X-Frame-Options header (prevents clickjacking)
- X-XSS-Protection enabled
- Content-Type-Options set to nosniff
- Form spam protection with honeypot
- HTTPS enforced (via Netlify)

## 📝 File Structure

```
QSS-Electrical/
├── index.html          # Main website file
├── success.html        # Form success page
├── netlify.toml        # Netlify configuration
├── _redirects          # URL redirect rules
└── README.md           # This file
```

## 🎨 Design Philosophy

This website follows modern luxury design principles:
- **Whitespace**: Generous spacing for breathing room
- **Typography**: System fonts for fast loading and native feel
- **Colors**: Limited palette for sophistication
- **Animations**: Subtle, purposeful motion
- **Photography**: High-quality professional images
- **Trust Signals**: Prominent display of credentials

## 💡 Tips for Success

1. **Update Content Regularly**: Keep services and testimonials fresh
2. **Monitor Form Submissions**: Check Netlify dashboard daily
3. **Test on Real Devices**: Don't rely only on browser dev tools
4. **Optimize Images**: Use WebP format for better compression
5. **Add Analytics**: Track visitor behavior with Google Analytics
6. **Speed Test**: Use PageSpeed Insights to maintain performance

## 📞 Support

For questions about this website:
- Check Netlify documentation: https://docs.netlify.com
- HTML/CSS issues: Review code comments in index.html
- Form issues: Check Netlify Forms dashboard

## 📄 License

This website is proprietary and created for QSS Electrical.

---

**Built with ❤️ for QSS Electrical** | Last Updated: 2025