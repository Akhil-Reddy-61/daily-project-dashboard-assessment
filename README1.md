
# Daily Project Details — Mini Dashboard

A self-contained web dashboard that displays daily project details from a JSON file. Built with plain HTML, CSS, and JavaScript — no frameworks or libraries.

## 🌐 View Live

**Website:** [https://akhil-reddy-61.github.io/daily-project-dashboard-assessment/](https://akhil-reddy-61.github.io/daily-project-dashboard-assessment/)

Just click the link above — no setup needed.

---

## 💻 Run Locally

1. Download or clone this repository
2. Make sure `index.html` and `entries.json` are in the **same folder**
3. Double-click `index.html` — it opens in your browser

No server, no build step, no installation required.

---

## Features

- Loads project entries from `entries.json`
- Sortable columns (Username, Project Hours)
- Filters: search by username, multi-select by Site and Role
- Interactive summary cards (filter by Total, Site, Overdue, WF Type)
- Add new entries (top-level or per-username as sub-entries)
- Edit individual ETA with TBD reason tracking
- Delete user-added entries with confirmation
- Overdue detection and badge with detail popup
- Dark/Light theme toggle (persists in localStorage)
- Download filtered data as CSV
- Fully responsive design

---

## Tech Stack

- HTML5
- CSS3 (CSS Variables, Flexbox)
- Vanilla JavaScript (ES5)
- No external libraries or frameworks

---

## Files

| File | Purpose |
|------|---------|
| `index.html` | Complete dashboard (HTML + CSS + JS) |
| `entries.json` | Project data source |
| `README.md` | This file |

