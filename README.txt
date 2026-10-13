# My PCOS Daily Dashboard

A small installable web app for tracking daily weight, steps, calories, macros, habits, workouts, cycle notes, and symptoms.

## Privacy
- Data is stored in localStorage in the browser on the device where you use it.
- It is not uploaded to a server and does not automatically sync between devices.
- Export a CSV backup regularly.
- Clearing browser/site data may erase the log.

## Make it an app on your phone
For installable home-screen app behaviour and offline caching, host these files on an HTTPS static host (for example GitHub Pages or Netlify).

1. Extract this ZIP.
2. Upload `index.html`, `manifest.json`, and `sw.js` to a static HTTPS site.
3. Open that HTTPS URL on your phone.
4. Android/Chrome: browser menu → **Install app** or **Add to Home screen**.
5. iPhone/Safari: Share → **Add to Home Screen**.

You can also open `index.html` locally to try the tracker, but browser storage and install/offline features are more reliable when served over HTTPS.

## Included tracker
- Daily date navigation and separate logs by date
- Calories, protein, carbohydrates, fibre, water, weight, and steps
- Habit and workout checklists
- Period/symptom notes and energy rating
- CSV export for backup
- Editable targets are displayed as starting estimates; the nutrition target values in the UI are not a medical prescription

This is a wellness tracker, not a diagnostic or treatment tool. Because PCOS and irregular periods require individual care, discuss prolonged gaps between periods with a clinician.
