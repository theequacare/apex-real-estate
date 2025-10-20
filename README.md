# 🏢 Apex Real Estate Agency - Static Website

**Pure HTML/CSS/JavaScript website** - No backend required!

---

## 📂 Project Structure

```
apex-static/
├── index.html          # Main webpage (bilingual: English/Nepali)
├── css/
│   └── styles.css      # All styling (2,202 lines)
├── js/
│   ├── script.js       # Interactive features
│   └── translations.js # English/Nepali translations
└── README.md           # This file
```

---

## ✨ Features

- 🌐 **Bilingual** - English & Nepali language switcher
- 📱 **Responsive Design** - Works on all devices
- 🎨 **Modern UI** - Clean, professional design
- 🔗 **Nepal Niwas Integration** - Links to properties and mobile app
- ⚡ **Fast Loading** - Pure static files, no backend
- 🚀 **Easy Hosting** - Deploy anywhere!

---

## 🌐 View Website Locally

### Option 1: Python HTTP Server
```bash
cd apex-static
python3 -m http.server 8080
```
Then visit: **http://localhost:8080/**

### Option 2: Any Web Server
Just open `index.html` in any web browser, or use:
- Node.js: `npx serve`
- PHP: `php -S localhost:8080`
- Live Server (VS Code extension)

---

## 🚀 Deployment Options

### 1️⃣ **GitHub Pages** (FREE & Easy!)

**Steps:**
1. Create a GitHub account at https://github.com
2. Create a new repository (e.g., `apex-realty`)
3. Upload all files from `apex-static` folder
4. Go to Settings → Pages
5. Select "main" branch → Save
6. Your site will be live at: `https://yourusername.github.io/apex-realty/`

**Tutorial:** https://pages.github.com/

---

### 2️⃣ **Netlify** (FREE - Recommended!)

**Steps:**
1. Go to https://www.netlify.com/
2. Sign up (free account)
3. Drag & drop the `apex-static` folder
4. Your site is LIVE instantly!
5. Get a free URL: `https://apex-realty.netlify.app`
6. Optional: Add custom domain

**Features:**
- ✅ Automatic HTTPS
- ✅ Global CDN (fast worldwide)
- ✅ Easy updates (just drag & drop new files)
- ✅ Free custom domain support

**Tutorial:** https://www.netlify.com/blog/2016/09/29/a-step-by-step-guide-deploying-on-netlify/

---

### 3️⃣ **Vercel** (FREE)

**Steps:**
1. Go to https://vercel.com/
2. Sign up with GitHub
3. Import the `apex-static` folder
4. Deploy!
5. Get URL: `https://apex-realty.vercel.app`

---

### 4️⃣ **Traditional Web Hosting**

Upload files via FTP to any web host:
- **Nepal-based hosts:** Websaathi, Webmount, Himalayan Host
- **International:** Bluehost, HostGator, SiteGround

Just upload:
- `index.html` → to root directory
- `css/` folder
- `js/` folder

---

## 🎨 Customization

### Change Contact Information

Edit `index.html` around line 160-180:

```html
<p data-lang-key="contact_address_value">Kathmandu, Nepal</p>
<p><a href="tel:+9771234567890">+977 123-456-7890</a></p>
<p><a href="mailto:info@apexrealty.com">info@apexrealty.com</a></p>
```

### Update Translations

Edit `js/translations.js`:

```javascript
const translations = {
    en: {
        contact_address_value: "Your New Address",
        // ... more translations
    },
    ne: {
        contact_address_value: "तपाईंको नयाँ ठेगाना",
        // ... more translations
    }
};
```

### Change Colors

Edit `css/styles.css` (lines 1-20):

```css
:root {
    --primary-color: #1e3a8a;    /* Dark blue */
    --secondary-color: #10b981;  /* Emerald green */
    --accent-color: #14b8a6;     /* Teal */
    /* ... change these colors */
}
```

---

## 📱 Features Included

### Navigation
- Smooth scrolling to sections
- Mobile hamburger menu
- Language switcher (English ⇄ Nepali)
- Link to Nepal Niwas property map

### Sections
1. **Hero** - Beautiful Nepali home image with intro
2. **About** - Company description with features
3. **Team** - Link to Nepal Niwas team directory
4. **Contact** - Address, phone, email, app downloads

### Mobile App Integration
- Google Play Store link (Nepal Niwas app)
- App Store link
- Beautiful app download buttons

---

## 🔧 Technical Details

- **No Database** - All content is in HTML
- **No Backend** - Pure frontend files
- **No Build Process** - Ready to deploy as-is
- **SEO Friendly** - Semantic HTML structure
- **Accessible** - ARIA labels included
- **Modern CSS** - Flexbox, Grid, CSS Variables
- **Vanilla JS** - No framework dependencies

---

## 📞 Support

For customization help:
- Edit files directly in any code editor
- Use browser DevTools to inspect elements
- Test locally before deploying

---

## 🎯 Quick Start Checklist

- [ ] Test website locally (`python3 -m http.server 8080`)
- [ ] Update contact information in `index.html`
- [ ] Update translations in `js/translations.js` (if needed)
- [ ] Choose hosting platform (Netlify recommended)
- [ ] Deploy files
- [ ] Test live website
- [ ] Share your URL!

---

## 🌟 Recommended: Netlify Deployment

**Fastest way to go live:**

1. Visit: https://app.netlify.com/drop
2. Drag the entire `apex-static` folder
3. Done! ✅

Your website will be live in seconds with:
- ✅ Free HTTPS certificate
- ✅ Global CDN
- ✅ Custom domain support
- ✅ Instant updates

---

**Made with ❤️ for Apex Real Estate Agency**  
**Last Updated:** October 2025  
**Status:** Production Ready 🚀

