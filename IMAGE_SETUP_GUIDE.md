# Image Setup Guide

## Required Images for Your Website

To complete your website setup, you'll need to create and add the following images:

### 1. Favicon (Browser Tab Icon)
- **File**: `favicon.ico`
- **Size**: 32x32 pixels or 64x64 pixels
- **Format**: ICO or PNG
- **Description**: Small icon that appears in browser tabs

### 2. Open Graph Image (Social Media Preview)
- **File**: `og-image.png`
- **Size**: 1200x630 pixels
- **Format**: PNG or JPG
- **Description**: Image shown when sharing your site on social media
- **Content Suggestions**: 
  - Your name and title
  - Professional photo or logo
  - Brand colors matching your site

### 3. PWA Icons (Mobile App Icons)
- **File 1**: `icon-192.png`
  - Size: 192x192 pixels
  - Format: PNG
  
- **File 2**: `icon-512.png`
  - Size: 512x512 pixels
  - Format: PNG

## How to Create These Images

### Option 1: Using Canva (Free & Easy)
1. Go to [Canva.com](https://www.canva.com/)
2. Create a new design with custom dimensions
3. Use your brand colors (#00ff88, #0088ff, #ff0088)
4. Add your name, title, and design elements
5. Download as PNG

### Option 2: Using Figma (Professional)
1. Create artboards with required dimensions
2. Design using your brand colors
3. Export as PNG at 2x resolution

### Option 3: Online Favicon Generators
- [Favicon.io](https://favicon.io/) - Generate from text or image
- [RealFaviconGenerator](https://realfavicongenerator.net/) - Complete favicon package

## Design Tips

### For OG Image (1200x630px):
```
+--------------------------------+
|                                |
|    Reshma Narkhede            |
|    Senior Quality Analyst      |
|                                |
|    [Professional Photo/Logo]   |
|                                |
|    Quality Engineering         |
|    Insurance Domain Expert     |
|                                |
+--------------------------------+
```

### Color Palette:
- Primary Green: #00ff88
- Blue: #0088ff
- Pink: #ff0088
- Dark Background: #0a0a0f

### Fonts to Use:
- Headings: Syne (Bold/ExtraBold)
- Body: Space Mono

## Where to Place Images

After creating images, add them to your repository root:
```
anrevi.github.io/
├── index.html
├── favicon.ico
├── og-image.png
├── icon-192.png
├── icon-512.png
├── manifest.json
└── ...
```

## Testing Your Images

1. **Favicon**: Refresh your browser and check the tab icon
2. **OG Image**: Use these tools:
   - [Facebook Sharing Debugger](https://developers.facebook.com/tools/debug/)
   - [Twitter Card Validator](https://cards-dev.twitter.com/validator)
   - [LinkedIn Post Inspector](https://www.linkedin.com/post-inspector/)

## Optional: Professional Photo

Consider adding a professional headshot for the hero section:
- **Size**: 400x400 pixels minimum
- **Format**: WebP (best) or PNG/JPG
- **Background**: Transparent or matching site colors
- **Style**: Professional business casual

## Quick Start Templates

### Text-Based Favicon (No Design Skills Needed)
1. Visit [Favicon.io](https://favicon.io/favicon-generator/)
2. Enter "RN" (your initials)
3. Choose font and colors matching your site
4. Download and add to your site

### Simple OG Image
1. Use a solid color background (#0a0a0f)
2. Add your name in large text (Syne font)
3. Add subtitle "Senior Quality Analyst"
4. Add accent elements (lines, shapes) in your brand colors

## Need Help?

If you need custom design:
- Hire on [Fiverr](https://www.fiverr.com/) - $5-20
- Post on [r/freedesign](https://www.reddit.com/r/freedesign/)
- Use AI tools like Midjourney or DALL-E

---

**Pro Tip**: Keep all images optimized (compressed) for faster loading. Use tools like [TinyPNG](https://tinypng.com/) or [Squoosh](https://squoosh.app/).
