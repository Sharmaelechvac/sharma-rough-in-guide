# Residential Rough-In Guide

Sharma Electric & HVAC's field guide for helpers and apprentices — hosted on GitHub Pages:
https://sharmaelechvac.github.io/sharma-rough-in-guide/

Formerly "Electrician 101" (renamed by Sanjay, 2026-11-15) and previously served by a
Cloudflare Worker; moved to GitHub like Sharma's other apps (Sanjay, 2026-11-15:
"It's all GITHUB").

GitHub edition notes:
- Look up, cheat sheets, Residential Rough-in section, glossary — full content, static.
- Practice quizzes run on the device (same curriculum and grading code the worker
  used, `docs/curriculum.js`); scores save on the phone only, 80% to pass.
- Ask the NEC is OFF in this edition — it needs a live server holding a secret
  token, which GitHub Pages cannot do. The page says so plainly.
- SPA deep links work via `docs/404.html` (a copy of `index.html`).

Source of truth for the original worker app remains the private repo
Sharmaelechvac/sharma-electrician-101; this repo is the static GitHub build
(`docs/`), generated from its `public/` + `src/curriculum.js`.
