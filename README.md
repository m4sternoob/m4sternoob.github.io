# m4sternoob.github.io

My portfolio site — the first thing a recruiter sees. Game programmer, Kitchener-Waterloo, ON.

**Live:** https://m4sternoob.github.io

## What's here

- **Portfolio** — hero, stats, Selected Work (click any card for the full breakdown), skills, about, contact
- **CV** — print-friendly one-page CV (open the CV tab, then Print → Save as PDF)
- **Game** — playable Nokia-1100-style Snake
- **Pixel Market** — a tiny canvas demo

## Tech

Hand-written HTML + CSS + JS. No framework, no build step, no dependencies.
Font is Bricolage Grotesque via Google Fonts. GitHub Pages serves it as static files
(`.nojekyll` disables Jekyll processing).

## Structure

- `index.html` — tab shell: nav, the CV section, the Snake game, Pixel Market
- `portfolio/index.html` — the actual portfolio: hero, stats, project cards, detail
  modals, skills, about, contact. Card copy and the per-project modal breakdowns
  all live in the `PROJECTS` object in the page's script.
- No screenshots or stock images anywhere — every visual is code (canvas) or CSS.

## Updating project cards

Edit the `PROJECTS` object at the bottom of `portfolio/index.html`. Every claim in
a card or modal must be verifiable against the linked repo — no invented features,
no mock screenshots.

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000 — portfolio/ resolves relative to the root
```

## Notes

- Contact email on the site is masternoob102030@gmail.com. No real names, phone
  numbers, or addresses anywhere in this repo.
- Card copy and its modal must stay consistent — the modal expands the card,
  it never contradicts it.
