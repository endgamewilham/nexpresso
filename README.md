# Nexpresso — Coffee Beans Shop (Vue.js)

A professional, single-page marketing site for a specialty coffee roaster that ships to all 50 US states.

## Quick start

```bash
npm install
npm run dev
```

Open the URL shown in the terminal (usually `http://localhost:5173`).

## Swap images & copy easily

**All editable content lives in one file:**

`src/content/siteContent.js`

| What to change | Where in `siteContent.js` |
|----------------|---------------------------|
| Brand name, tagline, contact | `brand` |
| Navigation links | `navLinks` |
| Hero slideshow images & captions | `heroSlides` |
| Shipping message | `shipping` |
| About / story section | `story` |
| Product cards | `products` |
| Customer reviews | `testimonials` |
| Call-to-action | `cta` |
| Footer & social | `footer` |

### Using your own photos

1. Add images to `public/images/` (e.g. `hero-1.jpg`)
2. In `siteContent.js`, set `image: '/images/hero-1.jpg'`

Paths starting with `/` are served from the `public` folder.

### Slideshow

Add or remove objects in the `heroSlides` array. Each slide needs `image`, `alt`, and `caption`.

### Testimonials

Edit the `testimonials` array — each entry has `quote`, `name`, `location`, and `rating` (1–5).

## Build for production

```bash
npm run build
npm run preview
```

Output is in `dist/` — deploy to Netlify, Vercel, or any static host.

## Stack

- Vue 3 (Composition API)
- Vite
- No UI framework — custom CSS with fluid motion and scroll reveals
