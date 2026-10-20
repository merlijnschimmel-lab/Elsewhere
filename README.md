# Elsewhere — Travel Roulette

A premium, responsive travel discovery site for an in-class assignment. Built using plain HTML, CSS, and JavaScript: **no npm installation, paid APIs, keys, or build step needed**.

## Features
- Animated roulette wheel selecting from 80 handpicked destinations
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

## Version 2 — Trip Studio upgrade

The new **Trip Studio** section lets visitors:
- Create a 2–14 day illustrative day-by-day itinerary for any of the 80 destinations.
- Set the number of travelers (1–12), pace (relaxed/balanced/packed) and accommodation tier.
- See recalculated estimated ground costs per person, for the group, and per day.
- Copy a short itinerary to the clipboard (requires clipboard permission and HTTPS; Vercel provides HTTPS).
- Compare up to three destinations side by side using the **COMPARE** buttons on destination cards.
- Save comparison selections to the same browser with localStorage.

**Important:** Costs and activities are illustrative examples, not live prices, bookings, or verified schedules. The itinerary uses curated highlights and is not AI-generated. No account or paid API is needed.

### Updating a previous deployment

Unzip the files and replace the existing root-level `index.html`, `styles.css`, `script.js`, `README.md` and `vercel.json` in your GitHub repository. Commit the changes. Vercel should automatically redeploy if its GitHub integration is active.


## Version 3.0 — Travel DNA quiz

A seven-question interactive travel personality quiz is now included under **Travel DNA**. Answers identify one of five travel archetypes and rank three matching destinations using the existing curated destination data. Results can be copied, and recommendations open destination details or build a trip in Trip Studio. No third-party API or account is needed.

## Version 4.0 — Expanded destination collection

Added 44 destinations to bring the total to **80** while preserving stable numeric IDs for all previous favorites and comparisons. New entries are searchable and available to roulette filters, Travel DNA recommendations, the bucket list, comparisons and Trip Studio. All new estimated ground budgets are illustrative. Several new destinations temporarily reuse regional stock travel imagery; replace with verified destination-specific photos before public promotion.
