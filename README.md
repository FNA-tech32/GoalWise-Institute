# GoalWise Institute

GoalWise Institute is a simple web playbook for drawing, animating, and exporting basketball plays.

The site is two HTML files: a landing page (`index.html`) and an editor (`app.html`). There is no backend, no account, no database, and no build step.

## Pages

- **Landing page** (`index.html`) — presents the playbook, the main features, live court previews, and the export options.
- **Editor** (`app.html`) — the working tool. Place players, move the ball, animate the play, and export it.

## Features

- Build a play phase by phase.
- Move players directly on a FIBA court.
- Ball handling: holder, pass, and shot.
- Optional defenders with automatic placement.
- Screens, curved paths, and playback animation.
- Half court or full court.
- Automatic local save in the browser.
- JSON import and export.
- PNG export for each phase.
- Printable board / PDF export.
- Video export as MP4 or WebM, depending on the browser.

## Run it locally

Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8080
```

Then open:

```text
http://localhost:8080
```

## Data

GoalWise Institute does not store anything on a server. The current play is saved in the browser with `localStorage`. Export JSON to keep a copy or share it.

## Contact

GoalWise Institute
