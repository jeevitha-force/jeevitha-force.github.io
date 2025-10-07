# Yoga Studio Website

A minimalist, Jony Ive-inspired website for a yoga trainer built with Astro and Tailwind CSS.

## 🧘 Features

- **Full-page background image** - Immersive yoga imagery throughout
- **Instagram-style gallery** - Showcase yoga poses and studio photos
- **Responsive navigation** - Split left/right nav with mobile menu
- **Frosted glass sections** - Modern glassmorphism design
- **Smooth animations** - Elegant transitions and hover effects
- **Fast & optimized** - Built with Astro for maximum performance

## 🚀 Quick Start

### Local Development

```bash
# Install dependencies
npm install

# Start dev server
npm run dev
```

Visit `http://localhost:4321`

### Build for Production

```bash
npm run build
npm run preview
```

## 📁 Project Structure

```
/
├── public/
│   └── gallery/          # Add your yoga images here
│       ├── 1.jpeg
│       ├── 2.jpeg
│       └── background2.jpeg
├── src/
│   ├── pages/
│   │   └── index.astro   # Main page
│   └── styles/
│       └── global.css    # Tailwind CSS
└── astro.config.mjs
```

## 🎨 Customization

### Update Your Information

Edit `src/pages/index.astro`:

- **Line 10**: Page title and name
- **Line 27**: Logo/studio name
- **Line 68-69**: Hero title and tagline
- **Lines 77-85**: About text
- **Lines 94-110**: Class schedule
- **Line 172**: Contact email

### Change Images

1. **Background Image** (Line 17):
   ```html
   url('/gallery/background2.jpeg')
   ```

2. **Gallery Images** (Lines 126-163):
   - Add images to `public/gallery/`
   - Update `src` attributes

### Adjust Colors

Tailwind color classes used:
- `bg-stone-50` - Light background
- `text-stone-900` - Dark text
- `bg-stone-600` - Buttons/accents

## 🌐 Deployment

This site auto-deploys to GitHub Pages via GitHub Actions.

### Setup:

1. Go to repository Settings → Pages
2. Source: Select "GitHub Actions"
3. Push to master branch:
   ```bash
   git add .
   git commit -m "Deploy yoga studio site"
   git push origin master
   ```

Site will be live at: **https://jeevitha-force.github.io**

## 🛠 Tech Stack

- **Astro 5** - Static site generator
- **Tailwind CSS v4** - Styling
- **TypeScript** - Type safety
- **GitHub Actions** - CI/CD

---

**Find your balance.** 🧘‍♀️
