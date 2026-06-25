# Max Crafter YT Personal Website

A professional, SEO-optimized personal website for Max Crafter YT - YouTube Shorts Creator, Roblox Streamer, and Entertainment Content Creator (950/960 Subscribers).

## 🌐 Features

- **Fully Responsive Design**: Mobile-first approach with breakpoints for tablets and desktops
- **SEO Optimized**: Complete meta tags, Open Graph, Twitter Cards, canonical URLs, structured data
- **Semantic HTML**: Proper use of HTML5 semantic elements for accessibility and SEO
- **Modern CSS**: Custom properties, flexbox, grid layouts, smooth animations
- **Interactive JavaScript**: Mobile navigation, content filtering, form handling, scroll animations
- **GitHub Pages Ready**: Optimized structure for static hosting
- **Fast Loading**: Optimized assets, lazy loading images, efficient code
- **Accessibility**: WCAG compliant with proper ARIA labels and keyboard navigation
- **Entertainment Focused**: Designed for YouTube Shorts creators and streamers

## 📁 Project Structure

```
MaxCrafterYT/
├── index.html              # Homepage with SEO meta tags and JSON-LD
├── about.html              # About page with detailed biography
├── projects.html           # Projects portfolio with filtering
├── contact.html            # Contact page with form and social links
├── links.html              # Link tree / link in bio page
├── robots.txt              # Search engine crawling instructions
├── sitemap.xml             # XML sitemap for SEO
├── css/
│   └── styles.css          # Complete stylesheet with responsive design
├── js/
│   └── script.js           # Interactive JavaScript functionality
├── assets/
│   └── README.md           # Asset file specifications
└── favicon/
    ├── site.webmanifest    # Web app manifest
    └── README.md           # Favicon file specifications
```

## 🚀 Quick Start

### Local Development

1. **Clone or download this repository**
2. **Open in a code editor** (VS Code, Sublime Text, etc.)
3. **Start a local server**:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (with http-server)
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```
4. **Open in browser**: `http://localhost:8000`

### GitHub Pages Deployment

1. **Create a GitHub repository** (can use any name)
2. **Upload all files** to the repository
3. **Enable GitHub Pages**:
   - Go to repository Settings → Pages
   - Source: Deploy from a branch
   - Branch: main (or master) / root
   - Save
4. **Wait for deployment** (usually 1-2 minutes)
5. **Access at**: The GitHub Pages URL provided in Settings

## 🎨 Customization

### Update Personal Information & Branding

1. **Profile Details** (in all HTML files):
   - Update "Max Crafter YT" to your name
   - Update "@max-yt2025" to your username
   - Update social media links
   - Update contact information
   - Update subscriber count "950/960 Subscribers" when it changes

2. **Content**:
   - Replace placeholder text with your actual content
   - Update content descriptions and categories
   - Customize the about section with your story
   - Modify contact information and collaboration details

### Add Images

1. **Profile Images**: Add to `assets/` directory
2. **Project Images**: Add project screenshots/thumbnails
3. **Favicons**: Add to `favicon/` directory (see `favicon/README.md`)
4. **Update references** in HTML files if you change filenames

### Modify Colors

Edit CSS variables in `css/styles.css`:

```css
:root {
    --primary-color: #2563eb;      /* Main brand color */
    --secondary-color: #10b981;    /* Secondary accent */
    --accent-color: #f59e0b;       /* Highlight color */
    --text-dark: #1f2937;          /* Main text color */
    --text-light: #6b7280;         /* Secondary text */
    /* ... more variables */
}
```

## 🔍 SEO Features

### Implemented SEO Elements

- ✅ Meta title and description
- ✅ Meta keywords
- ✅ Canonical URLs
- ✅ Open Graph tags (Facebook, LinkedIn)
- ✅ Twitter Card tags
- ✅ Robots.txt (allows indexing)
- ✅ Sitemap.xml (all pages listed)
- ✅ JSON-LD Structured Data (Person schema)
- ✅ Semantic HTML structure
- ✅ Proper heading hierarchy
- ✅ Image alt attributes
- ✅ Mobile-friendly responsive design
- ✅ Fast loading performance

### Google Search Console

1. **Verify ownership** in Google Search Console
2. **Submit sitemap**: `https://maxyt2025.github.io/sitemap.xml`
3. **Monitor indexing status**
4. **Check for SEO issues**

### Update SEO Information

Edit meta tags in each HTML file:

```html
<title>Your Page Title</title>
<meta name="description" content="Your page description">
<meta name="keywords" content="your, keywords, here">
```

Update canonical URLs:

```html
<link rel="canonical" href="https://yourdomain.com/your-page">
```

Update JSON-LD in `index.html`:

```json
{
    "@context": "https://schema.org",
    "@type": "Person",
    "name": "Your Name",
    "url": "https://yourdomain.com/",
    "sameAs": [
        "https://youtube.com/@yourchannel",
        "https://github.com/yourusername",
        "https://twitter.com/yourhandle"
    ]
}
```

## 📱 Responsive Breakpoints

- **Mobile**: < 480px
- **Small Tablet**: 480px - 768px  
- **Tablet**: 768px - 968px
- **Desktop**: > 968px

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with custom properties
- **JavaScript (ES6+)**: Interactive features
- **No Frameworks**: Pure, lightweight code
- **No Build Tools**: Simple, easy to maintain

## 📝 Browser Support

- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## ⚡ Performance Optimization

- Lazy loading images
- Optimized CSS and JavaScript
- Efficient DOM manipulation
- Minimal HTTP requests
- Proper image sizing
- Browser caching headers (configure on server)

## 🔒 Security

- No sensitive data in code
- Secure form handling (implement server-side validation)
- HTTPS recommended for production
- Content Security Policy (configure on server)

## 📄 License

This project is open source and available for personal and commercial use.

## 🤝 Contributing

Feel free to fork this project and customize it for your own needs!

## 📞 Support

For issues or questions about this template, please open an issue in the repository.

## 🔗 External Links

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [SEO Best Practices](https://developers.google.com/search/docs)
- [Web.dev Performance Guide](https://web.dev/performance/)
- [MDN Web Docs](https://developer.mozilla.org/)

---

**Created with ❤️ for Max Crafter YT - YouTube Shorts Creator & Roblox Streamer (950/960 Subscribers)**