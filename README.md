# Module 4 — Electronic Fundamentals Study Set

Self-contained static HTML pages, ready to drop into a GitHub Pages repo (e.g. as a `module4/` folder inside `devpb412022.github.io`, or as the repo root for its own Pages site).

## Files
- `index.html` — hub page, links to all four tools below
- `mcq-mock-test.html` — 20-question multiple-choice mock test
- `oral-review.html` — 20-question oral/recall review (flashcard style)
- `combined-40.html` — both sets merged (40 questions, duplicates kept)
- `answerkey-check.html` — bilingual EN/TH accuracy check against a separate answer-key PDF

All pages are single self-contained `.html` files (fonts load from Google Fonts CDN; everything else is inline — no build step, no other assets needed).

## Deploy on GitHub Pages
1. Upload all 5 files into the same folder in your repo (root, or a subfolder like `module4/`).
2. In the repo's **Settings → Pages**, make sure the Pages source is set to the branch/folder you uploaded to.
3. Open `index.html` (or `module4/index.html`) at your Pages URL — the hub page links to the other four using plain relative paths, so as long as all 5 files stay in the same folder, the links work as-is.

## Source
Questions come from photographed exam-prep sheets; every answer and page reference is checked against *Module_4_Electronic_Fundamentals_CAT-B1.pdf* (176 pages, AERO-Bildung / EASA Part-66 CAT B1 training material).
