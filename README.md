# Nisrine Nouri — SEO & GEO portfolio

Static HTML, CSS, and JavaScript. No build or framework dependencies.

## Preview

Run `python -m http.server 4173 --bind 127.0.0.1` from this directory and open http://127.0.0.1:4173/.

## Structure

- `index.html`: professional overview, work, expertise, tools, and contact.
- `work/`: self-contained case studies.
- `styles.css`: shared responsive styles.
- `sitemap.xml`: canonical public pages.

## Content maintenance

Duplicate a case page, update its title, description, canonical, Open Graph metadata, JSON-LD, and next-case link. Add the page to the homepage and sitemap. Keep relative asset links compatible with the GitHub Pages project subdirectory.

## Confidentiality

Only sanitized editorial content belongs in this repository. Do not add source reports, screenshots, client identifiers, proprietary scores or formulas, or private review notes, including in comments, filenames, metadata, or Git history. Evidence panels are labelled reconstructions, not original product screenshots. Retain role and measurement limitations when editing.

## Publication

Prepared for https://nisrinenouri.github.io/nisrinenouri/. Publish only after owner approval. `.nojekyll` preserves static serving. A robots.txt in this project subdirectory would not govern the domain: domain-root robots configuration must be managed separately. Its absence does not prevent crawling. This site needs no analytics credentials or third-party runtime calls.
