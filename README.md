# Mastan Doors & Plywoods

A one-page website for **Mastan Doors & Plywoods**, a shop that sells doors, aluminium mesh doors, plywood, hinges, aldrops, tower bolts, handles and other hardware at wholesale rates.

The goal of the site is simple: help carpenters, contractors and builders find the shop and contact the owner quickly.

## Features

- 3D door in the hero section that swings open on hover and tilts with the mouse
- Product cards with a 3D tilt, lift and glare effect on hover
- "Ask for rate" button on every product that opens WhatsApp with the product name already filled in
- Contact form that turns the visitor's name, product and quantities into a WhatsApp or email message
- Sticky WhatsApp button that stays visible while scrolling
- Responsive layout for phones, tablets and desktops
- Automatic light and dark mode
- Respects the "reduce motion" setting on devices

## Products shown

Wooden doors, aluminium mesh doors, hinges, aldrops, tower bolts, door handles, plywood, and locks and other hardware.

## Tech

Plain HTML, CSS and JavaScript in a single file (`index.html`). No frameworks, no build step, and no dependencies except Google Fonts. Product illustrations are inline SVG.

## Run locally

1. Download or clone this repository.
2. Open `index.html` in any browser.

## Deploy for free

**GitHub Pages**
1. Go to the repository **Settings**, then **Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select the `main` branch and the `/ (root)` folder, then save.
4. The site goes live in a minute or two.

**Netlify:** drag the folder onto app.netlify.com/drop.

## Customize

- **Phone number:** search for `919390272849` in `index.html` and replace it with the new number in international format, without the plus sign.
- **Email:** search for `rasikuleman@gmail.com` and replace it.
- **Products:** each product is one `<article class="card tilt">` block in the products section. Copy a block to add a product.
- **Colors:** change the values at the top of the `<style>` section under `:root`.

## Contact

**Mastan Doors & Plywoods**
WhatsApp: +91 93902 72849
Email: rasikuleman@gmail.com
