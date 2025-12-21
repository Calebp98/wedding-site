# Wedding Website

Minimalist wedding site with generative tree art background and animated timeline.

## Features

- **Generative tree art** - Interactive p5.js background with tree, sun, and grass
- **Scroll effects** - Tree grows/shrinks as you scroll, sun shimmers
- **Pastel colors** - Burnt orange sun, dark green grass, brown tree
- **Timeline** - Tell your love story with scroll-triggered animations
- **Days counter** - Sticky counter showing days to/from the wedding
- **Mobile responsive** - Works on all devices

## Quick Start

```bash
npm install
npm run dev
```

Visit `localhost:4321` to see your site.

## Customization

### Wedding Details
Edit `src/pages/index.astro`:
- Change wedding date in the celebration section
- Update timeline dates and stories
- Modify wedding info (time, location, dress code)

### Colors
Edit `src/components/TreeBackground.astro`:
```javascript
const treeColor = "#A67C52";    // Tree
const grassColor = "#7A9B76";   // Grass
const sunColor = "#D8885F";     // Sun
```

### Content
- `src/components/WeddingInfo.astro` - Date, time, location details
- `src/components/Schedule.astro` - Event schedule
- `src/components/Menu.astro` - Meal options
- `src/components/Accommodations.astro` - Hotel info

## Deployment

```bash
npm run build
npm run preview
```

Deploy the `dist/` folder to any static host (Netlify, Vercel, GitHub Pages, etc.).
