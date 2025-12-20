# Wedding Timeline Website

A beautiful, minimalist wedding website with an animated timeline and dynamic days counter.

## Project Structure

```text
/
├── public/              # Static assets (images, fonts, etc.)
├── src/
│   ├── components/
│   │   ├── DaysCounter.astro      # Sticky counter showing days to wedding
│   │   └── TimelineSection.astro  # Reusable timeline section component
│   ├── layouts/
│   │   └── Layout.astro           # Base HTML layout
│   ├── pages/
│   │   └── index.astro            # Main timeline page
│   └── styles/
│       └── global.css             # Custom styles for timeline and counter
└── package.json
```

## Features

- **Scroll-triggered animations** - Timeline sections fade in as you scroll
- **Dynamic days counter** - Updates to show days from each event to the wedding
- **Tufte CSS styling** - Elegant, minimalist typography
- **Mobile responsive** - Looks great on all devices
- **Lightweight** - Fast loading, minimal JavaScript

## Customization

### Update Your Dates and Stories

Edit `src/pages/index.astro` to customize:
- Wedding date (eventDate in first TimelineSection)
- Each timeline section's date, title, and content
- Add or remove timeline sections as needed

### Add Photos

Place images in the `public/` folder and reference them in your content:
```html
<img src="/photo.jpg" alt="Description" />
```

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
