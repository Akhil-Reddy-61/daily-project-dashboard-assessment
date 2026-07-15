
# Daily Project Details — Mini Dashboard

A self-contained, interactive dashboard that loads project entries from a JSON file and displays them with search, filtering, and sorting capabilities.

## How to Run

1. Ensure `index.html` and `entries.json` are in the same folder.
2. Open `index.html` in any modern browser (Chrome, Firefox, Edge, Safari).
3. That's it — no build step, no server, no dependencies.

> **Note:** If opening via `file://` protocol and fetch fails, serve locally with `python -m http.server 8000` and open `http://localhost:8000`.

## Tech Stack

- Vanilla JavaScript (ES5 compatible)
- HTML5
- CSS3 (Custom Properties for theming)
- No frameworks or libraries

## Features — Core Requirements

- **Data table** with 7 columns: Username, Site, Active Project, Role, Type of WF, Project Hours, Individual ETA
- **Live search** filters rows by username as you type
- **Filter dropdowns** for Site (IN / EU / CN) and Role (CO / PO) — work together with search (AND logic)
- **Sortable columns** — Username and Project Hours toggle ascending/descending on click
- **Summary line** — "Showing X of Y" updates dynamically
- **Empty state** — friendly message when no entries match
- **Missing data handling** — null, empty, or "TBD" values display as "N/A"

## Stretch Goals Attempted

- **Overdue ETA highlighting** — entries with a past ETA date and an active project are flagged in red with an "OVERDUE" badge
- **Add Entry modal** — form with validation (Username, Site, Role required); saves new entries to localStorage for persistence across sessions
- **Loading & error states** — spinner shown during data fetch; error message displayed if entries.json cannot be loaded
- **Light/Dark theme toggle** — switch between themes; preference saved to localStorage

