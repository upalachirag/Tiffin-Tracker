# Tiffin Tracker — Blue Edition v3

- Roommate renamed to Member
- Add, update, and delete members
- Optional email and mobile number for each member
- Select multiple members when adding tiffins
- Default price ₹70, editable per entry
- Edit/delete individual tiffin records
- Daily and monthly totals, JSON backup/restore, CSV export
- Offline-ready PWA using local IndexedDB only

## GitHub Pages
Upload all files in this folder to the root of a GitHub repository. Enable Settings → Pages, deploy from `main` / root, then open the HTTPS URL in Android Chrome and choose Add to Home screen / Install app.

## Local testing
From this folder run `python -m http.server 8000`, then open `http://localhost:8000`. Service workers require HTTPS or localhost.

## Data safety
Data stays in the browser on this device. Export JSON backups regularly. No automatic sync or server database is included.
