# Mindora (frontend demo)

Open `index.html` in a browser (or run `python3 -m http.server` in this folder and visit http://localhost:8000).

- `index.html` - app shell
- `styles.css` - pastel design system
- `src/services.js` - mock API (`api`), `authService`, `userService`, `exploreService`, `recEngine`, Soundscape engine
- `src/app.js` - pages, router, check-in flow, Mindi chat, games

Demo login: use the "Try the demo account" button (demo@mindora.app).
Mindora is a wellness support tool, not a medical diagnostic system.

To connect a backend: replace the bodies of the functions in `src/services.js` with fetch() calls
(POST /api/checkin, GET /api/dashboard, GET /api/recommendations, POST /api/chat, POST /api/activity, ...).
