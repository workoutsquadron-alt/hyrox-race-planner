# HYROX Race Planner

A self-contained, static training plan generator for HYROX athletes.

## How it works

- Enter your race date, level (Beginner / Intermediate / Advanced), and days per week
- The page deterministically assembles a periodized plan: Base -> Build -> Peak -> Taper
- No external API calls. No backend. Runs entirely in the browser.

## Setup

Open `index.html` in any browser, or deploy to any static host (GitHub Pages, Netlify, Cloudflare Pages).

## Extending the block library

Open `planner.js` and find the `BLOCKS` array. Blocks tagged `level: 'beginner'` and `level: 'advanced'` are stubbed with TODO comments - add your own programming there.

## Checkout link

Search for `[SHOPIFY_CHECKOUT_URL]` in `index.html` and replace it with your real Shopify checkout URL before going live.

## Style

- Background: `#0A0E14`
- Text: `#ECE4D4`
- Gold accent: `#C8A24B`
- Fonts: Anton (headlines), Oswald (subheads), Space Mono (labels), Barlow (body)