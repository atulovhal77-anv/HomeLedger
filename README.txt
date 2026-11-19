घरहिशोब / HomeLedger — MVP

Start:
- Open index.html in a browser. This works as a local app; data is stored in browser localStorage.
- To install as a PWA and use offline, host this folder on HTTPS (GitHub Pages, Netlify, etc.) and open the hosted URL on Android Chrome. Then use browser menu > Install app / Add to Home screen.
- Service worker offline cache works only on HTTPS or localhost.

Features:
- Marathi/English toggle, monthly selection
- Dashboard totals, category cards, budget
- Itemized grocery records, milk entries, gas cylinder, newspaper, daily and other expenses
- Member names, paid-by attribution
- Monthly reports, print/save as PDF, CSV export
- JSON backup and restore

Storage note:
- This version is single-device local storage. It is not cloud-synced across family members. Back up regularly in Settings.
