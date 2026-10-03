# Vortizo AI

A responsive React website rebuilt for Vortizo AI. Designed for Vercel using Vite.

## Run locally

```sh
npm install
npm run dev
```

## Production

```sh
npm run build
```

In Vercel, import this folder/repository, choose the Vite preset, use `npm run build`, and set the output directory to `dist`. No environment variables are required.

## Contact

The contact form validates fields and opens the visitor's email client with an enquiry addressed to contact@vortizoai.com. It does not send or store submissions. Replace with an email API or form provider before using a server-backed contact flow. Booking CTAs currently lead to the contact section.

## Content

AI operations and ProfilePro interfaces are illustrative examples. They do not connect to live products. Unverified client testimonials and business statistics have been omitted. Fonts use Google Fonts with system fallbacks; icons use lucide-react.

## Project layout

- `src/main.jsx`: sections and interactions
- `src/styles.css`: responsive styling
- `public/favicon.svg`: brand favicon
- `work/references`: supplied inspiration files
- `work/qa.cjs`: browser interaction checks

Verification: production build, desktop/mobile screenshots, service dialog, industry tabs, FAQ, mobile navigation, form validation, overflow, and browser errors.
