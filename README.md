# Secure Guard — React Frontend

A responsive multi-page security company website built with React + Vite.

## Included pages
- Home
- About Us
- Services
- Packages
- Industries
- Why Us
- Request a Quote
- Contact

## Features
- Responsive desktop/tablet/mobile UI
- React Router navigation
- Animated hover states and WhatsApp floating CTA
- PKR package pricing
- Working quotation form
- Quotation form opens WhatsApp with the entered details
- No backend required
- External image URLs from Unsplash for the visual content

## Run

```bash
npm install
npm run dev
```

Production build:

```bash
npm run build
npm run preview
```

## WhatsApp
Change `WA_NUMBER` in `src/main.jsx` to your business WhatsApp number in international format without `+`.

This is frontend WhatsApp click-to-chat, not the official WhatsApp Cloud API. A real WhatsApp Cloud API requires a server-side integration because access tokens/secrets must not be exposed in browser code.
