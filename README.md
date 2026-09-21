# Crochet Creations - Showcase Website

A beautiful, responsive, single-page crochet product showcase website built with modern web technologies. Perfect for showcasing handmade crochet items!

## ✨ Features

- **Beautiful Design**: Modern, professional look with gradient accents and smooth animations
- **Responsive Layout**: Mobile-first design that looks great on all devices
- **Product Showcase**: Elegant product cards with hover animations and lazy loading
- **Smooth Animations**: CSS animations and transitions for a polished feel
- **Fast Loading**: Lightweight static site with minimal dependencies
- **Easy to Deploy**: Ready for instant deployment to Vercel or Netlify
- **SEO Friendly**: Proper meta tags and semantic HTML

## 📁 Project Structure

```
public/
├── index.html          # Main website
└── data/
    └── products.json   # Product data
package.json            # Project metadata
vercel.json             # Vercel deployment config
netlify.toml            # Netlify deployment config
README.md               # This file
```

## 🎨 Features Showcase

### Product Cards
- Beautiful image display with aspect ratio maintenance
- Color badges for product variants
- Price and description
- Smooth hover animations with scale effect
- Add to cart functionality with notifications

### Navigation
- Sticky navigation bar with smooth scroll
- Mobile responsive menu
- Shopping cart counter
- Smooth section linking

### Sections
1. **Hero Section** - Eye-catching introduction
2. **Products** - Grid of handmade items
3. **About** - Business information and stats
4. **Contact** - Multiple contact methods
5. **Footer** - Links and social media

## 🚀 Quick Start

### Local Development

The site is a static website with no build step needed!

1. **Open directly in browser**:
   - Double-click `public/index.html` to open in your default browser

2. **Using Python (for local server)**:
   ```bash
   cd public
   python -m http.server 3000
   # Visit http://localhost:3000
   ```

3. **Using Node.js (if available)**:
   ```bash
   cd public
   npx http-server -p 3000
   ```

## 📝 Customization

### Update Products

Edit `public/data/products.json`:

```json
{
  "products": [
    {
      "id": 1,
      "name": "Your Product",
      "price": 29.99,
      "image": "https://your-image-url.jpg",
      "description": "Product description",
      "color": "Color/Variant"
    }
  ]
}
```

### Customize Colors

The site uses a purple-to-pink gradient theme. To change:

1. Edit the `gradient-text` class in `public/index.html`
2. Modify the `from-purple-*` and `to-pink-*` Tailwind classes
3. Update button gradient colors

### Add Social Links

Update the footer section in `public/index.html`:

```html
<a href="https://instagram.com/yourhandle">Instagram</a>
```

### Update Contact Info

Edit the contact section with your actual email, phone, and location.

## 🌐 Deployment

### Deploy to Vercel (Recommended)

1. **Push to GitHub** first:
   ```bash
   git add .
   git commit -m "Initial crochet showcase site"
   git push origin your-branch
   ```

2. **Connect to Vercel**:
   - Go to [vercel.com](https://vercel.com)
   - Click "New Project"
   - Import your GitHub repository
   - Keep default settings (it will detect `vercel.json`)
   - Deploy!

3. **Your live link**: Your-project.vercel.app

### Deploy to Netlify

1. **Using Netlify Drop** (easiest):
   - Go to [netlify.com/drop](https://netlify.com/drop)
   - Drag and drop the `public` folder
   - Get instant live link!

2. **Using GitHub**:
   - Push to GitHub
   - Connect your repo on [netlify.com](https://netlify.com)
   - Select `public` as publish directory
   - Deploy!

3. **Your live link**: your-site.netlify.app

## 🎯 Performance Tips

- Images use Unsplash CDN (no local image files needed)
- CSS and animations are optimized for 60fps
- Lazy loading enabled for images
- Minimal JavaScript for fast page load
- No external dependencies (just Tailwind CDN)

## 📱 Browser Support

- Chrome/Edge (latest 2 versions)
- Firefox (latest 2 versions)
- Safari (latest 2 versions)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔄 Adding More Products

1. Add product object to `public/data/products.json`
2. Increase the grid count if needed (currently set to 3 columns on large screens)
3. Images auto-scale with responsive design

## 🎨 Customization Examples

### Change the color scheme
Replace all `purple` with your brand color and `pink` with your accent:
```html
<!-- Example: Change to blue-indigo theme -->
from-blue-600 to-indigo-600
```

### Add product categories
Enhance `products.json` with a category field and filter by it in JavaScript.

### Implement actual shopping cart
- Add simple localStorage persistence
- Create checkout flow
- Integrate payment processor (Stripe, PayPal)

## 📄 License

MIT - Feel free to use this for your business!

## 🤝 Support

For questions or customization needs, feel free to reach out!

---

Built with 💜 for creative entrepreneurs. Ready to showcase your handmade magic! ✨
