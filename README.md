# Conservancy Council

An integrated water resources management (IWRM) role-play game for six downstream stakeholder teams, plus two optional upstream teams, sharing one coastal water conservancy in Guyana. It covers water quantity (shortages, floods, dam safety) and water quality (fertilizer runoff, mining sediment, livestock and estuary impacts), and lets the facilitator switch the upstream basin between fixed scenarios and active play. Developed for teaching and capacity building at the Faculty of Earth and Environmental Sciences (FEES), University of Guyana.

- **`index.html`** is the game. Open it in any browser. It needs no server or installation.
- **`docs.html`** is the full documentation: rules, IWRM principles and theory, the water-balance model and every equation, scoring, default parameters, worked examples, limitations, calibration with real data and WEAP, and a facilitation guide.
- **`compare.html`** is the facilitator's comparison page. Each table downloads its results file (or copies a results code) from the game; the facilitator drops the files or pastes the codes here to rank the tables and compare their charts on the projector. Nothing is uploaded: it all runs on the facilitator's computer.
- **`assets/`** holds the faculty logo (see below).

## Playing with several tables

Every table opens the same GitHub link at the same time; each browser runs its own independent game. Ask each table to enter a table name, not to change Settings (so all tables share the same weather), and not to refresh the page (the game does not save). When finished, each table clicks **Download results file** or **Copy results code** and sends it to the facilitator. See section 14.4 of `docs.html`.

All numbers in the game are illustrative teaching values. Replace them in the game's Settings panel with real data before using results for anything beyond teaching.

## Adding the FEES logo

Save the official FEES logo as `assets/fees-logo.png` (PNG with a transparent background works best, about 200 px tall). Both pages pick it up automatically. If the file is missing, the pages show the faculty name as text instead.

## Publishing with GitHub Pages

1. Create a new repository on GitHub (for example `conservancy-council`).
2. Upload `index.html`, `docs.html`, `README.md` and the `assets` folder to the repository root. You can drag and drop them on the repository page with **Add file → Upload files**.
3. Go to **Settings → Pages**. Under **Build and deployment**, set **Source** to *Deploy from a branch*, choose the `main` branch and the `/ (root)` folder, and click **Save**.
4. After a minute or two the site is live at `https://<your-username>.github.io/conservancy-council/`. The documentation is at `.../docs.html`.

## Running offline

Download the files and double-click `index.html`. Everything except the web fonts works without internet. Without internet the pages fall back to system fonts.

## Credits

Game design and model: Faculty of Earth and Environmental Sciences, University of Guyana, 2026. Inspired by the River Basin Game (Lankford et al., IWMI), Irrigania (Seibert and Vis, University of Zurich) and the Wat-A-Game toolkit (CIRAD/INRAE). See `docs.html` for full references.
