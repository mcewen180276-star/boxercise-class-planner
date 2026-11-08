# Boxercise Class Planner — Version 2

Open `index.html` locally or upload it to the root of a GitHub Pages repository.

## Updates
- Redesigned mobile-friendly dashboard and clearer builder.
- 120 original exercises plus 130 expanded entries, each with written technique guidance.
- 135 fitness-oriented combinations.
- Choose Everyone together, Circuit stations, or Mixed class.
- Select 2–20 circuit stations; generator requires enough different matching exercises.
- Exercise descriptions appear in the library and inside generated plans.
- Removed misleading generic video searches. Custom exercises can store instructor-reviewed demonstration URLs from supported sites.
- Saved plans and custom entries remain compatible with the prior localStorage format (`boxercise-planner-v1`).

## Important
Existing browser data is stored per site and browser. Export a backup before changing hosting domains or clearing browser storage. This app is for supervised non-contact fitness, not sparring.

## Version 3 — App icon and installation
Upload **all** files in this folder to the root of your existing GitHub Pages repository (not just index.html). The manifest, icons and service worker are needed for installable app behavior. Keep the same repository URL to preserve browser-saved classes.

On Android Chrome, open the published site, use the browser menu and choose **Install app** or **Add to Home screen**. The app icon should appear on your home screen. Installation support varies by browser and device. Service worker supports basic offline loading after the first successful online visit.
