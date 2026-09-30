# Suhas Morisetty — Personal Portfolio

A minimal, light-only portfolio hosted at https://suhas1999.github.io/.

## Structure

- `index.html` — short introduction and dated news.
- `cv.html` — career, education, and research overview with the full CV download.
- `contact.html` — email, LinkedIn, and CV links.
- `styles.css` — shared black-and-white styling, mobile layout, and print styles.
- `assets/` — favicon and original resume PDF.
- `.nojekyll` — tells GitHub Pages to serve these static files directly.

## Update

Edit the relevant HTML file. All content is directly editable, with no framework, package installation, or build step. Add news in `index.html` as a new item in `news-list`, newest first. Keep expected milestones labeled as expected. Replace the PDF at `assets/suhas-morisetty-resume.pdf` to update the CV download.

To add writing, replace the placeholder with an article title, date, summary, and working link. On the Publications page, replace placeholder text only when the official title, author list, paper URL, and code URL are confirmed. Current project headings are descriptive labels from the resume, not asserted official paper titles.

## Preview

From this repository, run:

```sh
python3 -m http.server 5173
```

Open http://localhost:5173. Alternatively, open `index.html` directly. The website has no JavaScript dependency.

## Publish

GitHub Pages publishes the root of the `main` branch. Commit and push changes to `main`; GitHub deploys them automatically. In repository Settings → Pages, the source should remain “Deploy from a branch,” branch `main`, folder `/ (root)`.

## Content source

All personal facts come from the supplied resume. Columbia graduation is expected in December 2026; no enrollment date was provided. The Capital One internship ended in August 2026. WACV is dated only to 2023. The Capital One publication remains in preparation. Missing links and writing are explicitly marked as placeholders. The downloadable original resume includes the supplied contact details.

The layout takes inspiration from https://r-rishabh-j.github.io/: a concise personal introduction followed by news. It uses original markup and styling, with no copied photos or personal content.
