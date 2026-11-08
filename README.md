# Gareth Manning — Educational Rebuild

Bilingual Arabic/English educational reconstruction of a personal education and technology portfolio website.

> **Independent educational prototype.** This is not the official website. All content is either original to this reconstruction or clearly marked as illustrative.

## Project Goals

- Reconstruct the information architecture and user experience of an education/technology portfolio in a bilingual (Arabic + English) format.
- Demonstrate proper RTL/LTR handling, responsive design, and progressive enhancement.
- Provide a clean, documented foundation for further educational and technical development.
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
gareth-manning-educational-rebuild/
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

- Do not change the current visual design without explicit approval.
- Preserve existing functionality.
- Keep the Git history clear and atomic.
- Never commit secrets, API keys, or private data.
- Respect licensing: do not copy protected content from the original site without permission.

## Future Stages

See [docs/roadmap.md](docs/roadmap.md) for the planned evolution of the project.

---

© 2026 — Independent educational prototype