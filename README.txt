NEON BEATS — PWA package
========================

Files:
- index.html: music player
- manifest.json: app name, appearance and icons
- sw.js: offline caching for the app shell
- icons/: app icons

IMPORTANT:
To install as a real ChromeOS web app (PWA), the files need to be served from HTTPS
(for example, free GitHub Pages). Opening index.html as a local file is fine for
testing the player, but browsers do not enable full PWA installation/service-worker
features on file:// URLs.

The app shell can work offline after its first visit, but music files selected by
the user are not permanently saved in the app; select them again after reopening.
External music source links require an internet connection.
