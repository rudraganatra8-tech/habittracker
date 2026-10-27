# Daily Progress

Habit streaks with punishments, 30/60/90-day challenges, charts and a glass floating nav.
Installable on iPhone from Safari (Share > Add to Home Screen).

## Files
- `index.html` the whole app (HTML, CSS, JS)
- `manifest.json`, `sw.js`, `icons/` PWA install files

## Status
Accounts and data are stored in the browser (`localStorage`) for now. Next step: Cloudflare Worker + D1
for shared accounts and server-side storage. Only the `lget/lset` storage helpers and `doAuth()` need to change.

## Not possible in a web app
Home screen widgets and automatic Apple Health sync need a native iOS app.
