# SportFlow

SportFlow is a standalone French-language prototype for managing a sports club. It demonstrates member and session management, class reservations, attendance tracking, and summary reports.

## Run locally

The app has no build step or package dependencies. Open `index.html` in a recent browser, or start a local static server from this directory:

```bash
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Included features

- Responsive dashboard and French-language navigation
- Create and edit members and training sessions
- Reservation checks for duplicate bookings and session capacity
- Basic coach scheduling conflict checks
- Attendance tracking and summary statistics
- CSV and JSON data export
- Browser-local persistence using `localStorage`

## Prototype limitations

This is a front-end demonstration. It has no server, shared database, authentication, or external service integration. Data is stored only in the browser profile where the app is used. The weekly attendance chart is illustrative; the main summary values use the current local demo data.

The project was supplied as a ZIP archive containing `index.html` and a README. This repository preparation does not infer or alter individual authorship, create historical commits, or claim Jira validation. No license has been selected; add a license only after the project owners agree on its terms.
