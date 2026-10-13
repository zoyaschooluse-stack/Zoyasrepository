# handoff.md — 1923 Tschichold Calendar Generator

## 1. Project Overview & Current State
* **Current Session:** Session 1 (Deconstruction, Typographic Hierarchy & AI Sourcing).
* **Reference Artifact:** Jan Tschichold's 1923 promotional calendar poster for *Fischer & Wittig* (Leipzig).
* **Status:** 
  - Archival image analyzed and deconstructed.
  - Core design logic, math, and typographic hierarchy encoded into `skills.md`.
  - Typefaces sourced, tested, and downloaded.
  - Project directory structure established.

---

## 2. Key Decisions & Rationale
* **Selected Specimen:** Jan Tschichold (1923). Chosen for its hybrid aesthetic: pre-modernist architectural symmetry paired with expressive German calligraphic ribbons and early inscriptional Roman lettering.
* **Typographic DNA:**
  * **Header / Roman Caps:** *Cinzel* (Google Fonts) was chosen to match the inscriptional, chiselled epigraphic Roman capitals in the header banners, year cartouche, and city label.
  * **Ribbon / Fraktur:** *UnifrakturMaguntia* (Google Fonts) was chosen for the service ribbons and month header to faithfully reproduce the high-contrast German blackletter calligraphy.
* **Color System:** Restricted 3-tone historical palette:
  * Aged Ivory / Cream (`#F6EEDB`)
  * Faded Sage / Mint Ground (`#A7C3B2`)
  * Carbon / Charcoal Black Ink (`#1B1E1C`)
* **Layout Geometry:** Symmetrical 3-bay division (31% left ribbon bay, 38% central architectural calendar spine, 31% right ribbon bay) with an overall 1 : 1.35 aspect ratio.

---

## 3. Directory Layout
```text
project-root/
├── assets/
│   ├── fonts/
│   │   ├── Cinzel-Regular.ttf (or .woff2)
│   │   └── UnifrakturMaguntia.ttf (or .woff2)
│   └── images/
│       └── calendar.jpg (reference poster)
├── skills.md (master design rule engine)
└── handoff.md (current project status & session log)