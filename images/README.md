# Images Directory

This directory contains all the images for your Hedoniz blog.

## How to Add Your Own Images

### 1. Add images to this folder:
- `hero-background.jpg` - Main hero background image (1600x800px recommended)
- `travel-1.jpg` - Travel blog post image (400x280px)
- `food-1.jpg` - Food blog post image (400x280px)
- `garden-1.jpg` - Gardening blog post image (400x280px)

### 2. Update the HTML file paths:

Replace the Unsplash URLs in `index.html` with:

**Hero Background:**
```html
<img src="images/hero-background.jpg" alt="Travel Adventure" class="hero-bg-image">
```

**Blog Cards:**
```html
<!-- Travel card -->
<img src="images/travel-1.jpg" alt="Weekend Travel Adventure">

<!-- Food card -->
<img src="images/food-1.jpg" alt="Cooking Adventure">

<!-- Garden card -->
<img src="images/garden-1.jpg" alt="Garden Project">
```

### 3. Recommended Image Sizes:
- **Hero Background**: 1600x800px (landscape, high quality)
- **Blog Cards**: 400x280px (landscape)
- **File Format**: JPG or WebP for best performance
- **File Size**: Keep under 500KB for fast loading

### 4. After adding images:
```bash
git add .
git commit -m "Add custom images"
git push origin main
```

Your images will be automatically deployed with Cloudflare Pages!