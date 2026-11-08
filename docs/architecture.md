# Architecture

This repository contains a bilingual (Arabic/English) educational reconstruction of a personal education and technology portfolio website.

## Current State (Prototype)

- Single-page static site.
- HTML + CSS + Vanilla JavaScript.
- Client-side language switching (RTL/LTR).
- No backend, no database, no build step.

## Target Architecture (Future)

```
┌─────────────┐     ┌─────────────┐     ┌─────────────┐
│   Frontend  │────▶│   Backend   │────▶│  Database   │
│  (Next.js)  │     │  (Node/API) │     │ (PostgreSQL)│
└─────────────┘     └─────────────┘     └─────────────┘
       │                   │
       └──────────┬───────┘
                   ▼
            Content CMS / i18n
```

- **Frontend**: Static or Next.js App Router with proper i18n.
- **Backend**: Optional API for contact form, analytics, or content management.
- **Database**: For dynamic content if the site grows beyond static.

The current prototype preserves the original structure and design while preparing the repository for gradual evolution.