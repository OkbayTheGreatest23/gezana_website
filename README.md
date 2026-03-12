# Gezana Landing Website

Beautiful, professional landing website for Goitom Connections' Gezana VoIP application.

## Project Structure

```
gezana-website/
├── index.html           # Main landing page
├── privacy.html         # Privacy policy
├── terms.html          # Terms of service
├── README.md           # This file
└── .gitignore          # Git ignore file
```

## Features

✨ **Responsive Design** - Works perfectly on mobile, tablet, and desktop  
🎨 **Modern Aesthetic** - Beautiful gradient design with smooth animations  
⚡ **Fast Loading** - Lightweight, no external dependencies  
📱 **Mobile-First** - Optimized for all screen sizes  
🔒 **Professional** - Legal-compliant terms and privacy policies  
♿ **Accessible** - Clean semantic HTML structure  

## Quick Start

### Option 1: GitHub Pages (Recommended - Free)

```bash
# 1. Create a new GitHub repo (name it: gezana-web)
# 2. Clone it
git clone https://github.com/YOUR_USERNAME/gezana-web.git
cd gezana-web

# 3. Copy website files to the repo folder
# 4. Initialize git and push
git init
git add .
git commit -m "Initial commit: Gezana landing website"
git remote add origin https://github.com/YOUR_USERNAME/gezana-web.git
git push -u origin main

# 5. Enable GitHub Pages in repo Settings
# Your site will be live at: https://YOUR_USERNAME.github.io/gezana-web
```

### Option 2: Vercel (Alternative - Free)

1. Go to https://vercel.com
2. Click "New Project" and import from GitHub
3. Select the gezana-web repository
4. Deploy with one click
5. Get live URL instantly (also supports custom domains)

### Option 3: Netlify (Alternative - Free)

1. Go to https://netlify.com
2. Drag and drop this folder
3. Custom domain available
4. Automatic SSL/HTTPS

## Using with Stripe

This website is designed for Stripe verification:

1. Deploy the site using one of the methods above
2. Get your live URL
3. Add the URL to your Stripe account during activation
4. Verify corporate information and payment details
5. Stripe will activate live mode

## Customization

### Company Info
- Email: `admin@gezana.app` (update throughout if needed)
- Company: Goitom Connections
- Service: Gezana VoIP

### Colors
Primary colors in CSS:
- Primary: `#667eea` (purple-blue)
- Secondary: `#764ba2` (darker purple)

### Pricing
Update the pricing section in `index.html` with your actual rates.

## SEO Best Practices

- ✅ Meta descriptions included
- ✅ Mobile viewport configured
- ✅ Semantic HTML structure
- ✅ Fast load times
- ✅ Schema.org structured data ready

## Analytics (Optional)

Add Google Analytics by inserting before `</head>`:

```html
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_ID');
</script>
```

Replace `GA_ID` with your Google Analytics ID.

## SSL/HTTPS

All deployment options (GitHub Pages, Vercel, Netlify) provide automatic SSL/HTTPS.

## Support

For questions, email: admin@gezana.app

---

**Website Deployed:** March 12, 2026  
**Company:** Goitom Connections  
**Service:** Gezana VoIP Platform
