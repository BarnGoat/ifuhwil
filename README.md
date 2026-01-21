# IFUHWIL - I Fucked Up, Here's What I Learnt

A clean, professional blog website for sharing meaningful mistakes and lessons learned.

## Features

✅ **Clean blog layout** - Card-based design for easy reading
✅ **No images required** - CSS gradient placeholders (easily replaceable)
✅ **Responsive design** - Works on all devices
✅ **Fast loading** - Minimal dependencies
✅ **Professional typography** - Crimson Pro + Work Sans

## Quick Setup for GitHub Pages

### 1. Create Repository

1. Go to https://github.com/new
2. Name: `ifuhwil-site`
3. Public repository
4. Create repository

### 2. Upload Files

Upload these files:
- `index.html`
- `styles.css`
- `script.js`
- `CNAME`
- `README.md`

### 3. Enable GitHub Pages

1. Repository Settings → Pages
2. Source: **main** branch
3. Save

Live at: `https://YOUR-USERNAME.github.io/ifuhwil-site/`

### 4. Custom Domain (ifuhwil.com)

**In GitHub Pages settings:**
- Enter: `ifuhwil.com`
- Save

**Update DNS at your domain provider:**

**A Records:**
```
Type: A
Name: @
Value: 185.199.108.153

Type: A  
Name: @
Value: 185.199.109.153

Type: A
Name: @
Value: 185.199.110.153

Type: A
Name: @
Value: 185.199.111.153
```

**CNAME Record:**
```
Type: CNAME
Name: www
Value: YOUR-USERNAME.github.io
```

Wait 5-60 minutes for DNS propagation.

## File Structure

```
ifuhwil-site/
├── index.html          # Homepage with featured posts
├── styles.css          # All styling
├── script.js           # Smooth scrolling, mobile menu
├── CNAME              # Custom domain
├── README.md          # This file
└── blog/              # Individual blog posts (create as needed)
    ├── post1.html
    ├── post2.html
    └── ...
```

## Adding Blog Posts

### Create Individual Post Pages

1. Create a `blog` folder
2. Add HTML files for each post:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Post Title | IFUHWIL</title>
    <link rel="stylesheet" href="../styles.css">
</head>
<body>
    <header class="header">
        <div class="header-content">
            <h1 class="logo"><a href="../index.html">IFUHWIL.</a></h1>
        </div>
    </header>
    
    <article class="post-content">
        <div class="container" style="max-width: 800px; padding-top: 8rem;">
            <h1>Your Post Title</h1>
            <p>Your content here...</p>
        </div>
    </article>
    
    <footer class="footer">
        <!-- Footer content -->
    </footer>
</body>
</html>
```

### Replace Placeholder Images

The gradient placeholders can be replaced with real images:

```html
<!-- Current: -->
<div class="placeholder-image" style="background: linear-gradient(...)"></div>

<!-- Replace with: -->
<img src="images/post-image.jpg" alt="Post title" style="width: 100%; height: 100%; object-fit: cover;">
```

## Customization

### Colors

Edit `styles.css`:
```css
:root {
    --color-primary: #2d3748;
    --color-accent: #667eea;
    /* Change these to your brand colors */
}
```

### Typography

Currently using:
- **Display**: Crimson Pro (elegant serif for headlines)
- **Body**: Work Sans (clean sans-serif)

Change in `index.html` Google Fonts link and `styles.css` font variables.

### Blog Posts

Update the blog cards in `index.html` with your actual posts:
- Change titles
- Update dates
- Modify categories
- Link to actual blog post pages

## Current Posts (from your Framer site)

1. **Cultural garden** - Culture - Aug 8, 2024
2. **First impressions** - Reputation - Oct 16, 2024
3. **Success** - Culture - Nov 23, 2024
4. **One more decision** - Product - Dec 6, 2024
5. **Reality distortion fields** - Reputation - Jan 15, 2025
6. **Games Funding** - Finance - Sep 19, 2025

## Design Philosophy

- **Clean & Readable** - Focus on content
- **Professional** - Serious blog, not playful
- **Fast** - Minimal dependencies
- **Accessible** - Good contrast, readable fonts

## Browser Support

- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Mobile browsers

## Going Live Checklist

- [ ] Create GitHub repository
- [ ] Upload all files
- [ ] Enable GitHub Pages
- [ ] Add custom domain
- [ ] Update DNS records
- [ ] Test site
- [ ] Create individual blog post pages
- [ ] Add actual blog content

## Future Enhancements

Optional improvements you could add:
- RSS feed
- Search functionality
- Blog post categories/tags page
- Archive page
- Newsletter signup
- Social sharing buttons

## Support

Questions? Email: (add your contact)

---

© 2024 IFUHWIL. All Rights Reserved.
