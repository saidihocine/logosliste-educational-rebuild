# logosliste — Educational Platform

Bilingual Arabic/English educational platform prototype.

> **Independent educational prototype.** All content is original to this project or clearly marked as illustrative. Developed by **logosliste**.

## Project Goals

- Build a clean, bilingual (Arabic + English) educational platform focused on periodic review and interactive assessments.
- Demonstrate proper RTL/LTR handling, responsive design, and progressive enhancement.
- Provide a documented, editable foundation for further educational and technical development.
- Serve as a learning artifact for bilingual web development and content structure.

## Technologies

- HTML5
- CSS3 (custom properties, responsive grid/flex, RTL support)
- Vanilla JavaScript (i18n switching, mobile menu)
- Google Fonts (IBM Plex Sans Arabic + DM Sans) with system fallbacks
- No frameworks, no build step, no backend

## Run Locally

No installation required.

```bash
# Option 1: Open directly
open index.html

# Option 2: Local server (recommended)
python -m http.server 8000
# or
npx serve
```

Visit `http://localhost:8000`.

## Language Support

- Default: Arabic (RTL)
- Toggle: English (LTR)
- Full `dir` and `lang` attribute switching
- Translations stored in `script.js`

## Repository Structure

```
logosliste-educational-rebuild/
├── index.html
├── styles.css
├── script.js
├── README.md
├── .gitignore
├── docs/
│   ├── architecture.md
│   ├── roadmap.md
│   └── content-structure.md
├── assets/
│   ├── images/
│   ├── icons/
│   └── fonts/
└── future/
    ├── frontend/
    ├── backend/
    └── database/
```

## Development Principles

- Keep the structure editable and content-driven.
- Preserve bilingual support and existing functionality.
- Keep the Git history clear and atomic.
- Never commit secrets, API keys, or private data.
- Content is experimental and should be replaced with final material.

## Future Stages

See [docs/roadmap.md](docs/roadmap.md) for the planned evolution of the project.

---

© 2026 — logosliste — Independent educational prototype