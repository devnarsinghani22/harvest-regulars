# The Regular's Club, concept rebuild

Static front end for Harvest Salad Co's subscription ordering flow. Demo data only: the page makes no API calls and nothing is ordered.

- `index.html`: the whole app (HTML, CSS, JS and menu data inline, about 24 KB gzipped)
- `img/`: dish photos as WebP, 232 px for the list and 720 px for the dish sheet

`orderPayload()` in `index.html` builds the same body the live app posts to `/api/app/order`.
