# Sankhya – An Infinite Learning Solution

Static, responsive website for Sankhya, an online coaching and mentorship platform for regulatory body and banking exams.

## Structure
```
index.html        page markup
css/style.css     styles (light/dark theme tokens)
js/main.js        data arrays (exams, courses, resources, FAQs, mock quiz) and interactions
assets/           logo, icon, favicon
```

## Run locally
Open `index.html` in a browser, or run `python3 -m http.server` and visit http://localhost:8000.

## Deploy on GitHub Pages
1. Push this folder to a GitHub repository.
2. Go to **Settings → Pages**, choose branch `main` and folder `/ (root)`, then save.
3. The site goes live at `https://<username>.github.io/<repo>/`.

## Editing content
Edit the arrays at the top of `js/main.js`. Items marked `[placeholder]` (prices, ratings, instructors, stats, contact details) are mock values to be replaced. The login, enrol and quiz features are frontend demos with no backend.

## Next steps
Course detail pages, blog, student dashboard, and a React + TypeScript + Tailwind port with real authentication, payments and CMS.
