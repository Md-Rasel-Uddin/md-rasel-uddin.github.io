# Md. Rasel Uddin — academic portfolio

A static website for GitHub Pages (https://md-rasel-uddin.github.io/). It needs no installation or build step.

It brings together the demo design and all the content from the old Google Site (https://sites.google.com/view/mdraseluddin): Home, About, Research, Project/Code, Selected Works, Recognition of Achievement and Contact.

## Files
- `index.html`: main page (About, Research, Publications, Selected Works, Projects, Experience & Education, Honors & Training, Leadership, Contact)
- `gallery.html`: photo gallery with captions and a click-to-enlarge viewer
- `style.css`: all styling, including responsive layout and dark mode
- `site.js`: mobile menu, dark-mode toggle, active-section highlight and gallery viewer
- `assets/img/`: photos, figures and project screenshots, resized from the old site
- `favicon.svg`, `.nojekyll`

## Preview locally
Open `index.html` in a browser, or run `python -m http.server` in this folder and open http://localhost:8000.

## Publish
Upload **the contents of this folder** (not the folder itself) to the root of the `md-rasel-uddin.github.io` repository, replacing the old `index.html` and `style.css`. Make sure the `assets` folder and `site.js` are included. GitHub Pages redeploys in about a minute.

## Updating content
- New publication: copy one `<div class="pub">…</div>` block in `index.html` under `#publications`.
- New gallery photo: put the image in `assets/img/` and copy one `<figure>` line in `gallery.html`.
- CV: the "Curriculum Vitae" button links to the Google Drive CV used on the old site (dated March 2025). Replace that link when a newer public CV is ready.
- Certificates link to the original Google Drive scans used on the old site.

## Content notes
- The TL-MED DOI was confirmed through Crossref.
- The UITS student email and the embedded Google Map from the old Contact page were left out as outdated or unnecessary. The Facebook link was left out as personal.
