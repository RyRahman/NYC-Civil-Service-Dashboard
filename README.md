# NYC Civil Service Dashboard

A lightweight, zero-dependency web dashboard to query and visualize candidate records directly from NYC Open Data. It provides city employees and candidates with an interactive visual timeline and tabular overview of active civil service eligible lists and recent certification actions.

---

## Features

- **Live NYC Open Data Integration:** Queries public Socrata endpoints directly from the browser with no server-side proxy or API keys required.
- **Interactive Visual Timelines:**
  - **Active Lists:** Visualizes eligibility periods using established dates, anniversary dates, and list extensions.
  - **Recent Certifications:** Highlights certification records within the trailing 12 months with a 30-day action window.
- **Instant Summary Metrics:** Displays real-time counts for active list entries, recent certifications, unique civil service exams, and the most recent certification date.
- **Data Exporting & Printing:**
  - One-click CSV export for active lists and certifications.
  - Dedicated print stylesheet optimized for generating PDF reports via browser print dialog.
- **Zero Build / Zero Dependencies:** Single standalone `index.html` file using vanilla JavaScript, CSS, and HTML.

---

## Data Sources

The dashboard queries the following NYC Open Data datasets:

- **Civil Service List (Active):** [`vx8i-nprf`](https://data.cityofnewyork.us/resource/vx8i-nprf.json)
- **Civil Service Certifications:** [`a9md-ynri`](https://data.cityofnewyork.us/resource/a9md-ynri.json)

---

Demo: https://ryrahman.github.io/NYC-Civil-Service-Dashboard/
