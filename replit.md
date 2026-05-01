# David Cyril Portfolio

## Overview
A static portfolio website for David Cyril, a Full Stack Developer from Abuja, Nigeria. The site includes a personal portfolio page and a collection of small web tool projects.

## Tech Stack
- **Frontend:** Vanilla HTML, CSS, JavaScript (no framework)
- **Assets:** CDN-based (Google Fonts, Font Awesome, Google AdSense)
- **API calls:** Browser-side `fetch()` to external API at `https://apis.davidcyriltech.my.id/`

## Project Structure
- `index.html` — Main portfolio landing page
- `projects/index.html` — Projects hub page
- `projects/<name>/index.html` — Individual project pages:
  - YouTube Downloader (`projects/youtube/`)
  - TikTok Downloader (`projects/tiktok/`)
  - Spotify Downloader (`projects/spotify/`)
  - Facebook Downloader (`projects/facebook/`)
  - APK Downloader (`projects/apk/`)
  - Chatbot (`projects/chatbot/`)
  - All-in-One (`projects/aio/`)
  - Calculator (`projects/calculator/`)
  - Currency Converter (`projects/currency/`)
  - Image Generator (`projects/image-generator/`)
  - Quote Generator (`projects/quote/`)
  - Remini (`projects/remini/`)
  - Remove Background (`projects/removebg/`)
  - Temp Mail (`projects/tempmail/`)
  - WallVista (`projects/wallvista/`)
- `assets/` — JavaScript files for project pages
- `css/` — Stylesheet files
- `premium.json` — WhatsApp IDs for premium access

## Running the App
The app is served as a static site using Python's built-in HTTP server:
```
python3 -m http.server 5000 --bind 0.0.0.0
```

## Deployment
- **Type:** Static site
- **Public Directory:** `.` (project root)
- **Workflow:** "Start application" on port 5000
