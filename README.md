# Holokleria LLC website

Source for the public website at https://holokleria.net, the parent presence
page for Holokleria LLC and the home of its free book resources.

Plain static HTML with the CSS inside each page. There is no build step.
Netlify is connected to this repository and automatically publishes every
push to the `main` branch.

## Structure

- `index.html` — homepage
- `resources/` — the Free Resources hub page
- `toomanypills/` — "Too Many Pills?" resource page and its printable PDF
- `prediabetes/` — "You Have Prediabetes. Now What?" (Anchor Meals) resource page and its printable PDF
- `_redirects` — URL redirect rules (handles capitalized addresses)
- `robots.txt` — search-engine indexing and AI-crawler rules
