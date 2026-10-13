# ANYUL CREATION Review Assistant

A mobile-friendly, static review-writing assistant using the supplied logo and Google Maps link.

## Deployment
1. Unzip this folder.
2. Deploy the folder to Vercel as a static site (or upload to Netlify / GitHub Pages).
3. Open the published link on your phone.

## Important
This version is fully functional without an API key, but it is **not generative AI**: it formats customer-written feedback with a translated introduction and conclusion. To add true AI paraphrasing, implement a server-side API endpoint and keep the API key on the server. Never expose API keys in the browser.

The Google Maps button opens the supplied Maps short link; it may open the listing rather than the review composer. For a direct review flow, replace it with your Google Business Profile 'Ask for reviews' URL.
