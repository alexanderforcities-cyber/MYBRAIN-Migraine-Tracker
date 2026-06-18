# MyBrain — Migraine Tracker

A self-contained migraine / headache tracking interface. Log episodes (pain, timing, location,
symptoms, triggers, medication, notes), browse History, view pattern Insights, and export a
Doctor report (CSV / print).

## Test it

`index.html` is a single, fully self-contained file — no build step, no dependencies.

- **Locally:** open `index.html` in any modern browser.
- **GitHub Pages:** push this repo, then enable Pages (Settings → Pages → deploy from branch,
  root). The app is served at the Pages URL. Add it to your phone's home screen to test as an app.

Data is stored locally in the browser (`localStorage`); nothing is sent anywhere.

## Source

The editable source is `MyBrain Aura.dc.html` (+ `support.js` runtime). `index.html` is the
compiled/bundled output of that file — edit the source and re-bundle to regenerate it.
