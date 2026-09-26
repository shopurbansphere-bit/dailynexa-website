# DailyNexa Key Website

Mobile-first static website ready for **Cloudflare Pages**.

## Features
- Clean dark theme
- Get Key flow with **15-second client-side countdown** (increases time-on-site for ads)
- Public endpoint `/api/today-key` on the backend
- Ad placeholders (top, in-content, bottom, countdown page)
- Sample original articles
- About / Privacy / Terms / Disclaimer / Contact pages

## Deploy on Cloudflare Pages (Free)

1. Create a GitHub repository and push this `website` folder
2. Go to Cloudflare Dashboard → Pages → Create project
3. Connect the repository
4. Build settings:
   - Framework preset: None
   - Build command: (leave empty)
   - Output directory: `/` (or leave default)
5. Deploy
6. Later: add your cheap custom domain in Cloudflare Pages settings

## After Backend is Live

1. Open `get-key.html`
2. Change this line:
   ```js
   const API_BASE = 'https://YOUR-API.onrender.com';
   ```
   to your real Render URL.

## Remaining Articles (placeholders)

You can copy any existing article and replace the content for:
- how-to-start-meditation.html
- better-study-habits.html
- improve-sleep.html
- how-wifi-works.html
- two-factor-authentication.html
- ssd-vs-hdd.html
- daily-routine.html
- reduce-screen-time.html

## AdSense
Once you have a real domain and enough original content, apply for AdSense and replace the `.ad-slot` divs with real ad code.
