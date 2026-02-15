# Reshma Narkhede - Personal Website

[![Deploy to GitHub Pages](https://github.com/anrevi/anrevi.github.io/actions/workflows/deploy.yml/badge.svg)](https://github.com/anrevi/anrevi.github.io/actions/workflows/deploy.yml)

A modern, innovative, and SEO-optimized personal portfolio website showcasing professional experience, skills, and achievements in Quality Engineering.

🌐 **Live Site**: [https://anrevi.github.io/](https://anrevi.github.io/)

## ✨ Features

### Design & UX
- 🎨 **Innovative Design**: Modern, futuristic aesthetic with animated gradients and glassmorphism effects
- 📱 **Fully Responsive**: Optimized for mobile, tablet, and desktop devices
- 🌓 **Dark Theme**: Elegant dark theme with vibrant accent colors
- ✨ **Smooth Animations**: Scroll-triggered animations and micro-interactions
- 🎯 **Interactive Elements**: Hover effects, transitions, and dynamic backgrounds

### Technical Features
- ⚡ **Lightning Fast**: Optimized for performance with minimal dependencies
- 🔍 **SEO Optimized**: Meta tags, structured data, and semantic HTML
- 📊 **Analytics Ready**: Google Analytics integration
- 🤖 **Search Engine Friendly**: robots.txt and sitemap.xml included
- 🚀 **Auto Deploy**: GitHub Actions workflow for automatic deployment
- ♿ **Accessible**: Semantic HTML and ARIA labels

### SEO Features
- ✅ Meta tags (title, description, keywords)
- ✅ Open Graph tags for social media sharing
- ✅ Twitter Card meta tags
- ✅ JSON-LD structured data (Schema.org)
- ✅ Sitemap.xml for search engines
- ✅ robots.txt for crawler management
- ✅ Canonical URLs
- ✅ Semantic HTML5 structure

## 🚀 Quick Start

### Prerequisites
- A GitHub account
- Git installed on your computer

### Setup Instructions

1. **Clone or Fork the Repository**
   ```bash
   git clone https://github.com/anrevi/anrevi.github.io.git
   cd anrevi.github.io
   ```

2. **Customize the Content**
   - Edit `index.html` to update your personal information
   - Replace Google Analytics ID (`G-XXXXXXXXXX`) with your actual tracking ID
   - Update contact information, skills, experience, and certifications

3. **Enable GitHub Pages**
   - Go to your repository Settings
   - Navigate to "Pages" section
   - Under "Source", select "GitHub Actions"
   - The site will automatically deploy on every push to main/master branch

4. **Push Your Changes**
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

5. **Access Your Website**
   - Your site will be live at: `https://anrevi.github.io/`
   - Wait 2-3 minutes for the first deployment

## 📝 Customization Guide

### Update Personal Information

1. **Hero Section**
   - Update name, title, and description in the hero section
   - Modify the hero labels and subtitle

2. **Skills & Competencies**
   - Edit skill cards in the "About" and "Skills" sections
   - Add or remove skills as needed

3. **Experience Timeline**
   - Update work experience in the timeline
   - Modify dates, companies, and descriptions

4. **Certifications**
   - Add your certifications in the certifications grid
   - Update icons and names

5. **Contact Information**
   - Update email, LinkedIn, GitHub links
   - Modify location information

### Update Colors & Theme

Edit CSS variables in the `<style>` section:
```css
:root {
    --primary: #00ff88;      /* Primary accent color */
    --secondary: #0088ff;    /* Secondary accent color */
    --accent: #ff0088;       /* Additional accent color */
    --dark: #0a0a0f;         /* Background color */
    --darker: #050508;       /* Darker background */
}
```

### Update Fonts

Replace the Google Fonts link in the `<head>` section to change fonts:
```html
<link href="https://fonts.googleapis.com/css2?family=YOUR_FONT&display=swap" rel="stylesheet">
```

## 🔧 SEO Setup

### Google Search Console

1. Go to [Google Search Console](https://search.google.com/search-console/)
2. Add your property: `https://anrevi.github.io/`
3. Verify ownership (use the HTML file method or meta tag)
4. Submit your sitemap: `https://anrevi.github.io/sitemap.xml`

### Google Analytics

1. Create a Google Analytics 4 property
2. Get your Measurement ID (format: G-XXXXXXXXXX)
3. Replace `G-XXXXXXXXXX` in `index.html` with your actual ID:
   ```html
   <script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
   ```

### Bing Webmaster Tools

1. Go to [Bing Webmaster Tools](https://www.bing.com/webmasters/)
2. Add and verify your site
3. Submit your sitemap

### Open Graph Image

Create an OG image (1200x630px) and add it to your repository:
- Name it `og-image.png`
- Update the path in meta tags if needed

## 📱 Responsive Breakpoints

The site is optimized for:
- 📱 Mobile: < 768px
- 💻 Tablet: 768px - 1024px
- 🖥️ Desktop: > 1024px

## 🎨 Design Features

- **Animated Background**: Dynamic gradient animation with floating particles
- **Glassmorphism**: Frosted glass effect on cards and navigation
- **Scroll Animations**: Elements fade in as you scroll
- **Interactive Cards**: Hover effects with transformations and glows
- **Timeline**: Visual experience timeline with connecting lines
- **Mobile Menu**: Smooth hamburger menu animation
- **Scroll to Top**: Floating button appears on scroll

## 🔄 Auto-Deployment

The GitHub Actions workflow (`.github/workflows/deploy.yml`) automatically:
1. Triggers on push to main/master branch
2. Builds the site
3. Deploys to GitHub Pages
4. Makes the site live in 2-3 minutes

## 📊 Performance Optimization

- Minimal external dependencies
- Optimized images (use WebP format)
- Inline critical CSS
- Lazy loading for images
- Compressed and minified code

## 🐛 Troubleshooting

### Site Not Deploying?
1. Check GitHub Actions tab for errors
2. Ensure GitHub Pages is enabled in settings
3. Verify the workflow has proper permissions

### 404 Error?
1. Wait 2-3 minutes after deployment
2. Check if the repository name matches your GitHub username
3. Clear browser cache

### Styling Issues?
1. Check browser console for errors
2. Verify CSS is loading properly
3. Test in different browsers

## 📄 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Feel free to fork this repository and customize it for your own use!

## 📧 Contact

**Reshma Narkhede**
- Email: reshmavnarkhede@gmail.com
- LinkedIn: [reshmapatilnarkhede](https://www.linkedin.com/in/reshmapatilnarkhede)
- GitHub: [reshmavnarkhede](https://github.com/reshmavnarkhede)

---

**Built with ❤️ and modern web technologies**

## 🌟 Star This Repository

If you found this helpful, please consider giving it a star ⭐
