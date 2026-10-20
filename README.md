# Elsewhere — Travel Roulette

A premium, responsive travel discovery site for an in-class assignment. Built using plain HTML, CSS, and JavaScript: **no npm installation, paid APIs, keys, or build step needed**.

## Features
- Animated roulette wheel selecting from 36 handpicked destinations
- Filters by budget, trip length, vibe and region
- Destination reveal with highlights, price estimates and a mini itinerary
- Browse all destinations, search by city/country and filter by region
- Add/remove favorites in a bucket list saved using browser localStorage
- Responsive desktop and mobile layouts, keyboard-friendly interactions

## Run locally
Simply open `index.html` in a web browser (internet access loads destination images and Google Fonts). For a local server you can also run `python3 -m http.server 8000` inside this folder and visit http://localhost:8000.

## Publish with GitHub + Vercel
1. Create a **new GitHub repository** (for example `travel-roulette`).
2. Upload `index.html`, `styles.css`, `script.js`, `vercel.json`, and `README.md` into the **repository root** (not a subfolder).
3. In [Vercel](https://vercel.com/new), select **Add New → Project** and import your GitHub repository.
4. Choose framework preset **Other**. Leave build command blank. The output directory should be the project root (`.`) or the default for a static project.
5. Click **Deploy**, then open the new `.vercel.app` URL. Later GitHub commits trigger new deployments.

## Testing checklist
- Spin with default settings and try restrictive filter combinations.
- Search destinations and change regional tabs.
- Save a destination, check the bucket list, and refresh: it should remain saved on that browser.
- Check on phone-sized viewport and test the navigation menu.
- Confirm external photos load with internet access.

## Notes
Trip budgets are **illustrative per-person on-location estimates**, not live flight/hotel quotations. Destination photos are loaded from Unsplash URLs and may require an internet connection. Favorites are stored locally to the browser, not shared across devices. This is a front-end assignment demo, not a booking service.
