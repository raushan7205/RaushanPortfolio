# Raushan Portfolio

A cyber-blue, terminal-inspired personal portfolio built with static HTML and Tailwind CSS (CDN).

## Overview

This project is a multi-page developer portfolio with a command-center style UI. It includes:

- A main dashboard page with profile, skills, experience, projects, certifications, and contact sections.
- Dedicated detail pages for skills, experience, projects, and certifications.
- A consistent visual theme: charcoal background + cyber-blue accents + glow hover effects.

## Pages

- [index.html](index.html): Main command center (single-page sections + links to detail pages)
- [skills.html](skills.html): Full skills listing
- [experience.html](experience.html): Full timeline
- [projects.html](projects.html): Project repository showcase
- [certifications.html](certifications.html): Certification showcase

## Tech Stack

- HTML5
- Tailwind CSS via CDN
- Google Fonts (Montserrat, Space Mono)
- Material Symbols icons

No Node.js build step is required.

## Project Structure

```text
RaushanPortfolio/
|- index.html
|- skills.html
|- experience.html
|- projects.html
|- certifications.html
|- README.md
`- assets/
	|- raushan-profile.jpg
	|- AuraAI.png
	|- r1.png
	|- r2.png
	|- r3.png
	`- r4.png
```

## Run Locally

Option 1: open [index.html](index.html) directly in your browser.

Option 2 (recommended): serve with a local HTTP server.

Using Python:

```bash
python -m http.server 5500
```

Then open:

```text
http://localhost:5500/index.html
```

## Design Notes

- Theme colors are defined in inline Tailwind config (`blue` and `charcoal` palettes).
- Each page contains its own inline Tailwind config and utility style block.
- Cards and pill tags use glow-based hover transitions for the gamified cyber look.

## Content Update Guide

Common updates are done directly in HTML:

- Profile details and hero section: [index.html](index.html)
- Skills cards and tags: [index.html](index.html), [skills.html](skills.html)
- Project cards, links, and images: [index.html](index.html), [projects.html](projects.html)
- Certification cards, links, and images: [index.html](index.html), [certifications.html](certifications.html)
- Experience timeline: [index.html](index.html), [experience.html](experience.html)

Image replacements:

- Put new files in [assets](assets)
- Update `src="assets/..."` paths in the relevant HTML cards

## Current Notes

- Some sidebar social/profile links still use `href="#"` placeholders.
- Project and certification detail pages are synced with the latest index card content and links.

## License

Personal portfolio project. Update licensing text here if you plan public redistribution.




