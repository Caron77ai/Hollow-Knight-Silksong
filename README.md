
# Hollow Knight: Silksong HTML5 game online

A static, fan‑made website themed around Hollow Knight: Silksong. The site includes a homepage with content sections, an in‑browser play area (embedding third‑party web content via an iframe), and a region‑focused guide page, all with responsive styling and light interactions.

Note: This project is not affiliated with Team Cherry. Hollow Knight, Silksong, characters, and artwork are the property of their respective owners. This repository is for learning and non‑commercial sharing only.

If you’ve deployed the site, visit your own domain to view it. Some meta and share examples in the pages reference `https://silksonggame.online`; these references come from the existing page markup and are not a guarantee of availability.

## Features

- Static site: plain `HTML` + `CSS` (Tailwind CDN) + light vanilla `JavaScript`
- Responsive layout for desktop and mobile
- Content sections: Home / Story / Gameplay / Features / Gallery / Play
- In‑browser play: embeds third‑party content via `<iframe>` 
- Sharing and effects: social share buttons, smooth scrolling, parallax, fade‑in animations
- Lightweight reviews: stored with `localStorage` 

## Local Preview

- Open the site’s homepage in a modern browser
- For production‑like behavior, use a local static server:
  - VS Code Live Server extension
  - Or Python: `python -m http.server 5500`

Note: The pages rely on online resources (Tailwind CDN, Google Fonts). Keep your device online.

## Development & Customization

- No build step: edit the pages and media assets directly
- Styling via inline styles and Tailwind CDN; add or remove sections as needed
- Behavior scripts at the bottom of the pages: smooth scrolling, sharing, local review persistence
- Images: place your assets in your images folder and reference them in the pages

## Deployment

- Works with any static hosting (GitHub Pages, Vercel, Netlify, Cloudflare Pages, etc.)
- GitHub Pages example: set the default branch as the publish source and use the repository’s Pages URL

## Copyright & Disclaimer

- This repository contains static pages and media resources only; no commercial code or backend services
- This is a non‑official project; all Hollow Knight / Silksong names, characters, and materials belong to their owners
- Before publishing third‑party images or assets, ensure you have proper rights and permissions

## Contributing

Contributions via Issues / PRs are welcome for content corrections, style tweaks, i18n additions, or accessibility improvements.


