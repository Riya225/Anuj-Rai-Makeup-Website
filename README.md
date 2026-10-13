# Anuj Rai — Professional Makeup Artist Website

Premium portfolio website for Anuj Rai, a professional makeup artist based in Chandigarh, India.

## Technology Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Bootstrap 5
- Bootstrap Icons
- Google Fonts

No React, Vite, Tailwind, or build step is required.

## Run Locally

1. Open `anuj-rai-makeup-website` in VS Code.
2. Install the VS Code Live Server extension if needed.
3. Right-click `index.html`.
4. Choose **Open with Live Server**.

The site also opens directly in a browser, but Live Server is recommended.

## Replace Images

Main image locations:

- `assets/images/hero-makeup.jpg`
- `assets/images/anuj-rai.jpg`
- `assets/images/artist-portrait.jpg`
- `assets/images/portfolio/`
- `assets/videos/`

The portfolio images currently included are supplied work photographs. You can replace, remove, or add more original photographs as the portfolio grows.

Suggested portfolio filenames:

- `bridal-look-01.jpg`
- `soft-glam-01.jpg`
- `party-makeup-01.jpg`
- `editorial-look-01.jpg`
- `nail-work-01.jpg`
- `makeup-kit-01.jpg`

After adding images, update the `portfolio` array in `js/script.js` with the image path, category, caption, and alt text.

## Add or Replace Videos

Video clips live in `assets/videos/`.

To add, remove, or rename clips, update the `videos` array in `js/script.js`. The site uses native browser video controls and does not autoplay videos.

## Edit Services and Contact Details

Open `js/script.js` and edit the `SITE_CONFIG` object.

You can update:

- Artist name
- Phone number
- WhatsApp number
- Instagram URL
- Location
- Services
- Portfolio items
- FAQ answers
- Promotion visibility
- Testimonials visibility

WhatsApp links use this configured number:

```js
whatsappNumber: "918168736309"
```

## Instagram

The Instagram profile is configured in `SITE_CONFIG.instagramUrl`.

The preview section is manually managed. Add or remove preview images by editing the `portfolio` array or adapting `renderInstagramPreview()` in `js/script.js`.

This site does not create a fake live feed and does not fabricate post URLs, follower counts, likes, or comments.

## Testimonials

The testimonials section is hidden by default:

```js
testimonialsVisible: false
```

Keep it hidden until genuine reviews are available and clients have given permission to display their words, names, or photographs.

## Promotional Banner

The banner is controlled here:

```js
promotionVisible: true
```

Only add real promotion details when they are confirmed. Do not invent discounts, validity dates, availability, or offers.

## Deployment

### GitHub Pages

1. Push the `anuj-rai-makeup-website` folder to a GitHub repository.
2. Go to repository **Settings > Pages**.
3. Choose the branch and folder containing `index.html`.
4. Save and wait for GitHub Pages to publish.

### Netlify

1. Drag the `anuj-rai-makeup-website` folder into Netlify Drop, or connect a Git repository.
2. Use no build command.
3. Use the folder containing `index.html` as the publish directory.

## Publishing Checklist

- Replace generated sample visuals with original photographs where available.
- Confirm all service names and descriptions.
- Confirm phone and WhatsApp number.
- Confirm Instagram URL.
- Add real testimonials only with permission.
- Test the WhatsApp enquiry message before sharing the site publicly.
