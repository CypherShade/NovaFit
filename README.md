# NovaFit — Fitness & Wellness Studio Landing Page

A fully responsive, pixel-conscious landing page built for **NovaFit**, a fictional boutique fitness and wellness studio. Built as Assignment 1 (Level 1 — Foundation) of the DigiHust Frontend Web Development Internship Roadmap.

**Live demo:** https://nova-fit-ecru.vercel.app/

## Overview

The brief called for a modern, mobile-first landing page for a fitness studio client, built with pure HTML5 and CSS3 — no UI frameworks. The page covers navigation, a hero section, services, an about section, testimonials, membership pricing, a contact form, and a footer.

## Features

- Semantic HTML5 structure (`header`, `main`, `section`, `article`, `nav`, `footer`)
- Fully responsive layout using CSS Grid and Flexbox, with mobile-first media queries at 900px (tablet) and 640px (mobile)
- Sticky header with a working hamburger menu on tablet/mobile
- Hero section with a schedule preview card and dual call-to-action buttons
- Services list, About section with studio stats, and a horizontally scrollable testimonials strip
- Three-tier pricing/membership cards with a highlighted "featured" plan
- Contact form with labeled, accessible form fields
- Hover states and transitions on nav links, buttons, cards, and social icons
- Accessible focus states, `prefers-reduced-motion` support, and alt/label text throughout

## Tech Stack

- HTML5
- CSS3 (Flexbox, Grid, custom properties, media queries)
- Vanilla JavaScript (mobile menu toggle only)
- Google Fonts: Fraunces (display) and Work Sans (body)

## Project Structure

```
novafit-landing-page/
├── index.html
└── README.md
```

All CSS and JS are embedded directly in `index.html` — no build step or dependencies required.

## Running Locally

1. Clone the repository:
   ```
   git clone [your-repo-url]
   ```
2. Open `index.html` directly in a browser, or serve it locally:
   ```
   npx serve .
   ```

## Responsive Breakpoints

| Breakpoint | Width      | Behavior |
|---|---|---|
| Desktop | > 900px | Full nav links visible, hero side-by-side |
| Tablet | 641px – 900px | Nav collapses to hamburger, hero stays side-by-side |
| Mobile | ≤ 640px | Hero stacks (copy first, schedule card below), single-column layout throughout |

## Deployment

Deployed on Vercel

## Author

Muhammad Owais
Frontend Development Intern, DigiHust
