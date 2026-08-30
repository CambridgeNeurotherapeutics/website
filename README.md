# Cambridge Neurotherapeutics — Website

Static site for Cambridge Neurotherapeutics (landing page + about/team page). No build step — plain HTML/CSS.

## Structure

- `index.html` — landing page (mission, approach, contact)
- `about.html` — team page (currently placeholder bios — **update before sharing externally**)
- `styles.css` — shared styles

## Local preview

Open `index.html` directly in a browser, or run a local server:

```
python3 -m http.server 8000
```

then visit `http://localhost:8000`.

## Deployment

Deployed via GitHub Pages from the `main` branch. Any push to `main` updates the live site.

## TODO

- [ ] Replace placeholder team bios/photos in `about.html` with real content
- [ ] Set `info@cambridgeneurotherapeutics.com` to a real, monitored inbox (or update the address)
- [ ] Add a real domain (e.g. cambridgeneurotherapeutics.com) once purchased, via repo Settings → Pages
