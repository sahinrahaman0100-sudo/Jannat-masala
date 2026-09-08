# Jannat Masala — Website

React + Vite + Tailwind CSS. No backend, no database, no payment gateway —
every order goes straight to WhatsApp.

## Run it locally

```
npm install
npm run dev
```

## Build for hosting (Netlify, Vercel, Hostinger, etc.)

```
npm run build
```

This creates a `dist` folder — upload that folder to your host.

## Where to edit things

Everything you'll ever need to change lives in **`src/config.js`**:
product names, Bengali names, prices, weights, and every image URL.
You never need to touch any component file to update a product or a photo.

---

## IMAGE URLS TO CHANGE

All of these are in `src/config.js`.

| What | Variable in `src/config.js` |
|---|---|
| Hero image | `HERO_IMAGE_URL` |
| Haldi Guro image | `products[0].image` |
| Lonka Guro image | `products[1].image` |
| Jeera Guro image | `products[2].image` |
| Dhaniya Guro image | `products[3].image` |
| Garam Masala image | `products[4].image` |
| Chicken Curry recipe image | `recipes[0].image` |
| Dal recipe image | `recipes[1].image` |
| Aloo Dum recipe image | `recipes[2].image` |
