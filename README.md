# Purl & Paws

A lean, cat-filled knitting companion. Find your next project, plan it day by day, track progress across several projects at once, and keep a photo archive of everything you finish.

## Features

- **Inspire**: a library of patterns (sweaters, accessories, home) with yarn, needles, gauge, yardage and steps, plus a random "cat's pick". "Your Own Pattern" covers anything you found elsewhere.
- **Plan**: choose how many weeks you want to spend and which weekdays you knit. The app spreads the pattern's steps evenly over your knitting sessions and shows what to do each day, splitting long steps into parts.
- **Track**: every running project shows a progress ring, an on-track / ahead / behind status, a week-by-week calendar, per-step progress bars and a checklist for each day.
- **Archive**: when you bind off, take a photo (opens the camera on phones) and add a note. Finished knits land on your archive shelf.

## Run it

It is a single `index.html` (plus an icon and manifest for Home Screen installs) with no build step. Open it in a browser, or serve the folder:

```sh
python3 -m http.server 8000
# then open http://localhost:8000 on your computer or phone
```

To host it for free, enable GitHub Pages for this repository (Settings → Pages → deploy from branch).

Projects are saved in the browser's local storage and photos in IndexedDB, so data stays on the device you use. The first launch adds a few example projects marked "Example"; delete them whenever you like.

## Full screen on iPad or iPhone

1. Host it with GitHub Pages (see above) and open the Pages link in Safari.
2. Tap Share → **Add to Home Screen**.
3. Open Purl & Paws from the Home Screen icon. It runs full screen without the Safari toolbar.

On tablets and desktops the layout widens to fill the screen, with project pages split into two columns.
