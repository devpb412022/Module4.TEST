# Module 4 — Electronic Fundamentals Study Set (v3)

Self-contained static HTML pages, ready to drop into a GitHub Pages repo (e.g. as a `module4/` folder inside `devpb412022.github.io`, or as the repo root for its own Pages site).

## Files
- `index.html` — hub page, links to all five tools below
- `oral-as-mcq.html` — **main study set**: the real oral/recall exam content, converted to the real 3-option MCQ exam format, distractors built to EASA's GM Question Bank methodology, transistor-labeling question includes inline diagrams, every item has a 🧠 memory trick
- `oral-review.html` — the same real question content in open-ended flashcard form (reveal + self-mark), also with memory tricks
- `oral-review-longform.html` — same 20 questions as one long scrollable page — question, answer, explanation and memory trick all visible at once, nothing to click through
- `mcq-highlighted.html` — a separate real MCQ question set (its own highlighted answers), extra coverage of the same textbook chapters
- `answerkey-check.html` — bilingual EN/TH accuracy check against a separate answer-key PDF

All pages are single self-contained `.html` files (fonts load from Google Fonts CDN; everything else is inline — no build step, no other assets needed).

## Deploy on GitHub Pages
1. Upload all 6 files into the same folder in your repo (root, or a subfolder like `module4/`).
2. In the repo's **Settings → Pages**, make sure the Pages source is set to the branch/folder you uploaded to.
3. Open `index.html` (or `module4/index.html`) at your Pages URL — the hub page links to the other five using plain relative paths, so as long as all 6 files stay in the same folder, the links work as-is.

## Source
Questions come from photographed exam-prep sheets; every answer and page reference is checked against *Module_4_Electronic_Fundamentals_CAT-B1.pdf* (176 pages, AERO-Bildung / EASA Part-66 CAT B1 training material).
