# STATUS

## What was built

A beginner manual and large-print static HTML site on using free AI, created for Asdale Dynamics, LLC (Dylan Asdale, registered nurse turned AI author, Indiana, formed October 2026).

### Contents

- `README.md` — project overview, credits Asdale Dynamics, LLC, license info
- `LICENSE` — MIT License, copyright line exactly `Copyright (c) 2026 Asdale Dynamics, LLC`
- `docs/` — markdown source of the beginner manual:
  - `index.md` — table of contents
  - `01-what-is-ai.md` — what AI is and is not
  - `02-chatting-safely.md` — how to chat safely
  - `03-first-prompts.md` — first prompts with copy-and-paste examples
  - `04-privacy-basics.md` — privacy basics
  - `05-everyday-tasks.md` — everyday tasks
- `site/` — large-print static HTML site:
  - `index.html`, `01-what-is-ai.html`, `02-chatting-safely.html`, `03-first-prompts.html`, `04-privacy-basics.html`, `05-everyday-tasks.html`
  - `assets/style.css` — large-print friendly (20px base font, high contrast, ample spacing, big headings, skip link)

### Style

Plain English, step by step, never condescending, large-print friendly, local-first (static HTML, no server, no install), no secrets or personal data. Credits Asdale Dynamics, LLC on every page and in the README.

## How to run it

Open any file in `site/` in a web browser. The site is static — no server, no install, no internet required once downloaded. Start with `site/index.html`.

No build step. To edit, open `site/assets/style.css` and any `.html` file in a text editor.

## Verification results

A verification script checked the following and all passed:

- `LICENSE` contains the exact copyright line `Copyright (c) 2026 Asdale Dynamics, LLC`
- `README.md` credits Asdale Dynamics, LLC
- No `.github/workflows` directory present
- 6 HTML pages present, `site/assets/style.css` present
- All pages link to the CSS
- All internal links resolve to existing files (no broken links)
- Every HTML page contains the "Asdale Dynamics, LLC" credit and the copyright line

The script also scanned for secrets/API keys/personal data. The only matches were the words "password" and "secret" used in educational privacy content (e.g., "Never share passwords with an AI"). These are intentional instructional words, not actual secrets, API keys, or personal data. No real secrets, API keys, or personal data are present in any file.

## Known gaps

- The site is a single-author static HTML site; no automated test suite or CI (none requested, no `.github/workflows` added per instructions).
- HTML was validated by a custom link/credit parser, not a formal HTML validator.
- Large-print friendliness verified by CSS design (20px base font, high contrast, skip link), not by user testing with visually impaired readers.
- No search, dark mode, or print stylesheet included.
- Content covers free web AI tools; local AI and MCP/agent tooling are mentioned by name but not detailed in this edition (planned for future Asdale Dynamics manuals per the LLC's broader focus).
