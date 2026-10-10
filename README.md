# Human Mind Lab

Human Mind Lab is a multi-page educational website about the human brain, memory, focus and perception. It is built with **HTML5 and CSS3 only** (no JavaScript) as a fresher training project.

## Pages

| Page | File | What it has |
|------|------|-------------|
| Home | `index.html` | Hero section and a guided tour of the labs |
| Brain Explorer | `brain.html` | Interactive brain map, 6 brain regions, summary table, further reading |
| Memory Lab | `memory.html` | Word-list test that fades after 30 seconds, memory tips |
| Focus Lab | `focus.html` | Focus factors, tips, breathing exercise |
| Perception Lab | `perception.html` | Five senses table, two optical illusions |
| Brain Quiz | `quiz.html` | 5 questions with live feedback and a score |
| Feedback | `feedback.html` | Feedback form with validation |
| Not Found | `404.html` | Custom error page |

## Features

- **Sticky navigation bar** that stays at the top while scrolling, highlights the current page and shows a reading-progress line. On phones it becomes one swipeable row.
- **Interactive brain map** (inline SVG): hover, tap or tab to a region to see what it does.
- **Quiz with live feedback** and a CSS-only score, built with `:checked`, `:has()` and CSS counters.
- **Memory test timer** and **breathing exercise** built with CSS `@keyframes`.
- **Optical illusions** drawn with inline SVG.
- **Responsive layout** for desktop, tablet and mobile.
- **Accessibility:** skip link, keyboard focus outlines, labels on all form fields, `aria-current` on the active page, reduced-motion support.
- **Back-to-top button** that appears after scrolling.
- **CSS variables** in `:root` for the main colors.

## Concepts practiced

Semantic HTML5, forms and validation, `details`/`summary`, tables, `meter` and `progress`, inline SVG, CSS variables, Flexbox and Grid, `position: sticky`, animations, `:has()`, CSS counters, media queries.

## Project structure

```text
human-mind-lab/
├── index.html
├── brain.html
├── memory.html
├── focus.html
├── perception.html
├── quiz.html
├── feedback.html
├── 404.html
├── style.css
├── human-mind-hero.jpg
└── README.md
```

## How to run

Open `index.html` in a modern browser (Chrome, Edge, Firefox or Safari), or use VS Code Live Server.

## Notes

- Some features (`:has()`, scroll-linked animations) need a recent browser. Older browsers still show a working page, only without those effects.
- The feedback form does not send data because there is no backend. Connect a form service (for example Formspree) by adding its URL as the form `action`.

## Author

Kancheti Venkata Rao - 2026
