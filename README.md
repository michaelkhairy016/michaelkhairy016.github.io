# michael-khairy.github.io

Personal portfolio of **Michael Amgad Khairy** — Industrial Engineer, supply chain planning & optimization.
Static single-page site: plain HTML/CSS/JS, no build step, no external dependencies.

**Live:** https://michael-khairy.github.io

## Local preview
Open `index.html` directly in a browser, or serve the folder:

```
python -m http.server 8080
# then open http://localhost:8080
```

## Structure
```
index.html                      # the whole page (hero, about, work, experience, skills, contact)
css/style.css                   # design system (navy/teal, serif display, light corporate)
js/main.js                      # mobile nav, scroll-reveal, active nav link
assets/img/                     # SVG diagrams, screenshots, favicon
assets/Michael_Khairy_CV.pdf    # downloadable CV
```

## Updating
Edit, commit, push — GitHub Pages redeploys automatically in about a minute:

```
git add -A
git commit -m "update: <what changed>"
git push
```

## Notes
- Car Flow Command screenshots are captured from the live app; Seif platforms are represented by architecture diagrams only (no real data published).
- CV PDF: replace `assets/Michael_Khairy_CV.pdf` to update the download.
