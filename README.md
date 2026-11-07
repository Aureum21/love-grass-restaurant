# Love Grass Restaurant

An ET Digital project, published by Alazar Wake Kore.

**[Visit the website](https://www.lovegrassdubai.com/)**

## The project

A restaurant menu and editorial website for Ethiopian food in Dubai. Includes English and Amharic dish names, food photography, restaurant information, and stories about teff, injera, and coffee.

Built with Astro, vanilla CSS, local fonts, optimized food images, Lottie, and atmosphere videos.

## Run locally

Use Node.js 22.12 or newer.

```sh
git clone https://github.com/Aureum21/love-grass-restaurant.git
cd love-grass-restaurant
npm ci
npm run dev
```

Open http://localhost:4321.

```sh
npm run build
npm run preview
```

## Project guide

`src/pages/` contains routes; `src/components/` shared and page-specific components; `src/data/` menu, reviews, and FAQ content; `src/styles/` design tokens; `src/assets/` source images; `public/` fonts, videos, and static files.

No database or environment variables are required. The static production build is written to `dist/`. The canonical domain is configured in `astro.config.mjs`; review metadata and business details when adapting the site. Payment processing and delivery ordering are outside this repository.

## Credits

Published under ET Digital with fresh Git history from the supplied archive. Love Grass Restaurant retains its branding and business content.

Branding, photography, fonts, and third-party media remain subject to their respective rights. No open-source license has been added.
