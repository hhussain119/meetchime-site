# meetchime.app

Static site for MeetChime, served by GitHub Pages at https://meetchime.app (see `CNAME`).
Plain HTML and CSS, no build step: edit the files and push.

- `index.html` – landing page. Set `RELEASED = true` at the bottom once a release with
  `MeetChime.dmg` is published to this repo's GitHub Releases; the download buttons then point at
  `releases/latest/download/MeetChime.dmg`.
- `privacy.html` – privacy policy (also required for Google OAuth verification).
- `signed-in.html`, `sign-in-problem.html` – where the app sends the browser after Google sign-in.
- `assets/` – icon and screenshots.
