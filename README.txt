FEEDBACK & INCIDENT LOG PWA

Files:
- index.html: app
- manifest.json: installable PWA settings
- sw.js: offline app shell cache
- icon.svg: app icon

Run locally:
For full PWA installation/offline support, host these files on HTTPS (for example GitHub Pages).
Opening index.html directly will allow basic use, but browser install and service worker features require HTTPS or localhost.

Data:
Entries are stored in localStorage in the current browser on the current device. They are not synchronised between devices.
Use Export backup regularly to save a JSON backup. Import backup merges entries by ID.
Print / Save PDF opens the browser print dialog; choose Save as PDF.

Privacy:
Avoid recording unnecessary sensitive personal information. Browser/site data clearing can remove saved entries.
