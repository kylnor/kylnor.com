# kylnor.com - Session Status

## Site is LIVE! 🚀
- https://kylnor.com (redirects to www)
- https://www.kylnor.com

## Completed
- [x] Favicon created from logo (favicon-32x32.png, favicon-16x16.png, apple-touch-icon.png)
- [x] Removed social links except Email, X, and LinkedIn
- [x] Added GTM tracking (GTM-TNZG5D6G) with GDPR-compliant cookie consent
- [x] Cookie banner - blocks tracking until user accepts
- [x] DNS configured in Cloudflare pointing to Vercel

## Test Checklist
- [ ] Favicon shows in browser tab (try hard refresh: Cmd+Shift+R)
- [ ] OG share image works: https://developers.facebook.com/tools/debug/
- [ ] Cookie banner appears on first visit
- [ ] GTM loads only after accepting cookies (check in browser DevTools → Network)

## Tech Stack
- **Hosting:** Vercel
- **DNS:** Cloudflare
- **Analytics:** Google Tag Manager (GTM-TNZG5D6G)
- **Form submissions:** Formspree + Google Sheets
- **Address autocomplete:** Radar API

## Key Files
- `index.html` - Main site
- `vercel.json` - Vercel config
- `images/og-share.png` - Social share image (1200x630)
- `images/kylnorKeepMovingForwardLogo.png` - Logo
