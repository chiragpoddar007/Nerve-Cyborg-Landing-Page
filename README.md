# NERVE — Synthetic Augmentation

A cyborg-themed responsive landing page built for **Techfest, IIT Bombay** (Web Development domain — *Cyborg-Themed Landing Page Development*).

🔗 **Live demo:** _add your GitHub Pages link here once enabled_

![status](https://img.shields.io/badge/status-concept_build-5eead4) ![type](https://img.shields.io/badge/type-single--file_HTML-8b5cf6)

---

## Concept

**NERVE** is a fictional neural-synthetic augmentation brand — think prosthetics engineered like instruments, not sci-fi robot parts. The pitch is "your body, extended, not replaced," which sets the tone for the whole design: clinical, technical, and grounded rather than flashy.

The signature visual is a hand-coded **SVG exploded-view diagram** of a cybernetic hand, styled like a patent drawing — palm, wrist, four fingers, and an angled thumb, each pulled apart with dashed leader lines and numbered spec callouts (sensor array, torque-feedback joint, neural relay palm, bio-interface cuff).

## Features

- **Exploded technical diagram** — fully hand-built SVG, no image assets, no 3D library
- **Product line section** — three spec-sheet styled cards (hand, eye, and neural relay units)
- **Process section** — 3-step fitting flow (Scan → Fit → Calibrate)
- **Field reports** — fictional client logs instead of generic testimonials, clearly labeled as a concept brand
- **Working waitlist form** — client-side only, shows a confirmation state on submit (no backend)
- **Fully responsive** — tested from mobile (390px) up through desktop
- **Respects `prefers-reduced-motion`** — animations disable for users who request it
- **Zero JS dependencies** — only Google Fonts is loaded externally; works offline once fonts are cached

## Tech Stack

- HTML5 + CSS3 (custom properties, CSS Grid, `clamp()` for fluid type)
- Vanilla JavaScript (no frameworks)
- Hand-coded SVG (no image assets, no icon libraries)
- Fonts: Space Grotesk, Inter, JetBrains Mono (Google Fonts)

## Running it locally

No build step required — it's a single self-contained HTML file.


git clone https://github.com/chiragpoddar007/nerve-cyborg-landing-page.git

cd nerve-cyborg-landing-page

start index.html

## Live Demo

Url - chiragpoddar007/Cybrog-Landing-Page

## Design notes

Built as a companion piece to a separate 3D Techfest submission, sharing the same core palette family (teal `#5eead4` / violet `#8b5cf6` / near-black `#060708`) for brand cohesion, with a copper accent (`#c8895a`) added here to represent the organic/human side of "augmentation."

## Credits

Built by **Chirag** for Techfest, IIT Bombay — Web Development.
