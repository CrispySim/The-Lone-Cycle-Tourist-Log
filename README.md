# The Lone Cycle Tourist

Static site for GitHub Pages. Files: `index.html` (page), `trips.js` (all trip data), `img/` (logo and banner), `vendor/` (map library), `photos/<trip-id>/` (your pictures).

## Add photos
1. Resize photos to ~1600px wide (keeps the site quick) and drop them in `photos/netherlands-2026/`.
2. In `trips.js`, under the day, change `"photos": []` to e.g.
   `"photos": [{"src": "photos/netherlands-2026/day1-ferry.jpg", "caption": "Harwich to Hook of Holland"}]`
3. Optional: add `"notes": "Your words about the day"` to a day.

## Add a trip
Copy a trip block in `trips.js`, give it a new `id`, and add its rides (Strava activity id, distance in metres, moving seconds, elevation metres, kcal, encoded polyline).

## Publish
Upload everything to a GitHub repo, then Settings > Pages > deploy from the main branch.

Live address: https://crispysim.github.io/The-Lone-Cycle-Tourist-Log/ (repo name `The-Lone-Cycle-Tourist-Log`). All links are relative, so it works from that sub-folder.
