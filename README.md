# 🛒 SajiloStore — Premium Static Ecommerce + WhatsApp Ordering

> **Launch your online store in minutes without the hassle.** Zero monthly fees, lightning fast, and orders directly via WhatsApp.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Now-25D366?style=for-the-badge&logo=googlechrome&logoColor=white)](https://statictemplate.sajilodigital.com.np)
[![Made by Sajilo Digital](https://img.shields.io/badge/Made%20by-Sajilo%20Digital-1e4b6e?style=for-the-badge)](https://sajilodigital.com.np)
[![License](https://img.shields.io/badge/License-Proprietary-red?style=for-the-badge)](#)

---

## Overview

**SajiloStore** is a beautifully crafted, fully static ecommerce landing page and store template built with pure HTML, CSS, and JavaScript. It replaces expensive, subscription-based platforms like Shopify with a one-time-purchase solution that is:

-  **Lightning fast** — no backend, no database, instant load times
-  **Mobile-first** — fully responsive on all screen sizes
-  **WhatsApp-powered** — customers order directly to your WhatsApp
-  **Free to host** — deploy on GitHub Pages, Vercel, or Netlify at zero cost
-  **Yours forever** — you own the code with no recurring fees

---

##  Features

| Feature | Description |
|---|---|
|  **Premium Design** | Glassmorphic navbar, AOS animations, hero section, bento grid |
|  **WhatsApp Checkout** | Orders are auto-formatted & sent directly to your WhatsApp |
|  **3 Pricing Tiers** | Basic ($98), Standard ($130), Premium ($165) with NPR equivalents |
|  **Store Showcase Gallery** | Horizontal scroll gallery on mobile, tall grid on desktop |
|  **Product Demo Video** | Autoplay looping video embedded in the demo section |
|  **3 Legal Pages** | Privacy Policy, Terms of Service, Refund Policy |
|  **Animated Marquee** | Scrolling announcement banners |
|  **Testimonials** | Real customer cards with star ratings |
|  **FAQ Accordion** | Interactive expandable FAQ section |
|  **SEO Ready** | Meta descriptions, keywords, Open Graph, Twitter Cards |
|  **Social Links** | Instagram, WhatsApp, Facebook, LinkedIn |
|  **Back to Top Button** | Smooth scroll to top button |

---

## 📁 File Structure

```
sajilo-pricing/
│
├── index.html          # Main landing page
├── store.html          # Product/store page
├── privacy.html        # Privacy Policy legal page
├── terms.html          # Terms of Service legal page
├── refund.html         # Refund Policy legal page
├── README.md           # This file
│
└── images/
    ├── favicon.png         # Browser tab icon
    ├── og-image.png        # Social share preview image
    ├── mockup.png          # Hero section product mockup
    ├── SajiloDigital.png   # Brand logo
    ├── sajlostore.mp4      # Demo walkthrough video
    ├── img1.jpeg           # Store showcase image 1
    ├── img2.jpeg           # Store showcase image 2
    ├── img3.jpeg           # Store showcase image 3
    └── img4.jpeg           # Store showcase image 4
```

---

##  Getting Started

### Local Preview

No build tools required! Just open `index.html` in your browser:

```bash
# Option 1: Double-click index.html in File Explorer

# Option 2: Use VS Code Live Server extension
# Right-click index.html → Open with Live Server
```

### Deployment (Free Hosting)

#### GitHub Pages
1. Push the entire folder to a GitHub repository
2. Go to **Settings → Pages → Deploy from branch → main**
3. Your site will be live at `https://arundada9000.github.io/sajilo-pricing`

#### Vercel (Recommended)
1. Go to [vercel.com](https://vercel.com) and sign in
2. Click **Add New Project → Import Git Repository**
3. Select your repo — Vercel auto-detects it as a static site
4. Click **Deploy** — done! ✅

#### Netlify
1. Go to [netlify.com](https://netlify.com)
2. Drag and drop the entire project folder onto the dashboard
3. Get a live URL instantly

---

## Customization

### 1. Update WhatsApp Number
In `index.html`, find and change:
```javascript
const WHATSAPP_NUMBER = "9779811420975";
```

### 2. Update Pricing
Find the `<!-- Pricing Section -->` in `index.html` and update the `data-package` attribute and price text in each `.pricing-card`.

### 3. Update Contact Info
Search for `arunneupane0000@gmail.com` and replace with your email address.

### 4. Replace Images
Drop your images into the `/images/` folder and update the `src` attributes in the HTML.

### 5. Update Social Media Links
In the footer of all HTML files, update the `href` values for Instagram, Facebook, LinkedIn, and WhatsApp links.

### 6. Update Legal Page Content
Edit the content sections in `privacy.html`, `terms.html`, and `refund.html` to reflect your actual business policies.

---

##  Dependencies (CDN — No Install Required)

All dependencies are loaded via CDN links in the `<head>` — no `npm install` needed.

| Library | Version | Purpose |
|---|---|---|
| [Font Awesome](https://fontawesome.com) | 6.x | Icons throughout the UI |
| [AOS](https://michalsnik.github.io/aos/) | 2.x | Animate On Scroll entrance effects |
| [Google Fonts](https://fonts.google.com) | — | Inter typeface |

---

##  WhatsApp Ordering — How It Works

1. Customer visits the landing page and clicks a **"Get this package"** button
2. The JavaScript `sendWhatsApp()` function constructs a pre-filled message with the package name
3. The customer is redirected straight to WhatsApp with the message ready to send
4. **You receive the order request directly** — no middleman, no platform fees

---

## 🗂️ Included Legal Pages

All legal pages share the same design system as the main site, with proper navigation back to the homepage.

| Page | File | Description |
|---|---|---|
| Privacy Policy | `privacy.html` | Data collection & usage practices |
| Terms of Service | `terms.html` | Usage rules & disclaimers |
| Refund Policy | `refund.html` | 7-day refund & delivery guarantees |

---

## SEO & Social Sharing

Every page includes:
- `<meta name="description">` — for Google search snippets
- **Open Graph tags** (`og:title`, `og:image`, etc.) — for Facebook & LinkedIn previews
- **Twitter Card tags** — for rich Twitter/X link previews
- `<link rel="icon">` — site favicon
- Semantic HTML5 structure with a single `<h1>` per page

---

##  Contact & Support

| Channel | Details |
|---|---|
|  WhatsApp | [+977-9811420975](https://wa.me/9779811420975) |
|  Email | arunneupane0000@gmail.com |
|  Website | [sajilodigital.com.np](https://sajilodigital.com.np) |
|  Instagram | [@arundada9000](https://www.instagram.com/arundada9000) |

---

## 📄 License

This project is **proprietary software** developed by [Sajilo Digital](https://sajilodigital.com.np). The source code is provided as part of a one-time purchase. You may use and modify it for your own business, but you may not resell or redistribute the template.

---

<p align="center">Made with ❤️ in Nepal by <a href="https://sajilodigital.com.np">Sajilo Digital</a></p>
