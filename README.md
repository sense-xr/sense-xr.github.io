# SENSE-XR 2027 workshop website

Live site: https://sense-xr.github.io/

Static HTML, CSS, and JavaScript. No build tools or server dependencies required.

## Files

- `index.html`: workshop content, dates, organizers, and links.
- `styles.css`: layout and responsive styling.
- `script.js`: accessible mobile navigation.
- `.nojekyll`: serves the static files directly through GitHub Pages.

## Preview locally

Run `python3 -m http.server 8000 --bind 127.0.0.1` in this folder and open http://127.0.0.1:8000.

## Publish updates

GitHub Pages publishes the repository's `main` branch, from the root folder. Commit and push changes to update the live site:

```sh
git add index.html styles.css script.js README.md
git commit -m "Update workshop website"
git push origin main
```

Deployment status is available in the repository's Actions tab and Settings → Pages.

## Content to finalize

- Add the workshop-specific EasyChair submission URL when available.
- Add the assigned workshop date, time, and room.
- Add confirmed speakers and accepted papers once the conference schedule is finalized.

The December 15 camera-ready deadline, January 25–27 conference dates, UBC Robson Square venue, and workshop listing were checked against the official AIxVR 2027 website on October 1, 2026. Other workshop content comes from the supplied proposal. Unconfirmed speakers and program committee invitations are not published.

The original proposal documents are intentionally ignored by Git and are not part of the public website. Google Fonts is used for typography, with local sans-serif fallbacks.

The public submission policies follow the organizer guide. The original logo archive and organizer guide remain local; only the selected conference logo in `assets/` is published.

Confirmed workshop deadlines: paper submission November 23, 2026; author notification December 4, 2026; camera-ready December 15, 2026.
