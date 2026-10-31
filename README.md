# FitTrack

A get-in-shape app for your phone: three short full-body workouts a week (at home or at the gym) that get a
little harder each time, plus cardio and body-weight tracking with progress charts.

Plain HTML/JS installable app (same setup as Sample Keys: `sw.js` for offline use, `manifest.webmanifest` + `icons/`
so it can be installed). No build step and no backend: data lives in the phone's browser storage. Use
**Settings → Export backup** to save a copy.

## Run it locally

```bash
python3 -m http.server 8765
```

Then open <http://localhost:8765>.

## Put it on your phone

Host the folder on GitHub Pages (same steps as `Sample Keys/SETUP.md` section 3), open the address on your phone, then:

- **iPhone (Safari):** Share → Add to Home Screen
- **Android (Chrome):** ⋮ → Install app

## Files

| File | What it is |
| --- | --- |
| `index.html` | The whole app: plan, workout logger, rest timer, cardio/weight logs, charts, settings |
| `sw.js` | Offline support |
| `manifest.webmanifest`, `icons/` | Lets phones install it as an app |
