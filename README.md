# Waitlist

Single-page daycare waitlist app. Pure HTML + vanilla JS, persisted to browser localStorage.

## Live URL

After enabling GitHub Pages: https://daviscenter.github.io/Waitlist/

## Local use

Open `index.html` in any modern browser. localStorage works fully when opened from a real origin (https URL or `file://`).

## Features

- Six classrooms (Infant A through PreK) auto-grouped by child's age at preferred start date
- Sort each classroom by date added, preferred start, age at start, or last contacted
- Optional secondary sort ("tiebreak") by date added
- "Mark contacted" tracking with freshness color (green ≤14d, amber older)
- CSV export
- Add / edit / delete entries via modal form
- Auto-classroom hint on the form based on DOB and start date

## Data shape

See the comment block at the top of the `<script>` in `index.html` for the entry schema and `window.WaitlistAPI` integration hooks for future website-form connections.
