# GitHub Profile README Design Spec

## Overview
This document specifies the design for `WildanFadillah1512`.
The chosen design direction is **The "Swiss Data-Viz" (Editorial Minimalist)**, an anti-AI, bespoke design inspired by Swiss typography and enterprise dashboards.

## Architecture & Structure
The README utilizes strict left-alignment, off-white backgrounds, and large grotesque typography.

### 1. Hero Header (`assets/hero-swiss.svg`)
- A custom SVG utilizing strict grid alignments and hairline borders.
- Background: `#F4F4F0`.
- Typography: System sans-serif fonts (Helvetica/Inter) in `black` (`#111111`).
- Accents: Vermilion Red (`#E32636`).

### 2. Tech Stack (`assets/tech-stack-swiss.svg`)
- Columns of technical competencies laid out like a rigorous manual or data sheet.
- Utilizes the same stark `#F4F4F0` and `#111111` scheme with red square bullets.

### 3. GitHub Stats
- Uses `github-readme-stats` aligned in an HTML table.
- **Theme Config**: Completely custom colors matching the Swiss aesthetic (`bg_color=F4F4F0`, `title_color=111111`, `icon_color=E32636`, `border_color=111111`, `border_radius=0`).

### 4. Contribution Grid (Snake Animation)
- Customized to match the theme:
  - Snake color: Red (`#E32636`)
  - Dots color gradient: Ranging from off-white `#F4F4F0` to deep black `#111111`.

### 5. Contact
- `shields.io` badges in `flat-square` style.
- Colors overridden to match the paper-like background and black text.

## Testing & Verification
- SVGs must render beautifully without relying on external web fonts (using system UI fonts).
- Ensure no "AI-generated" neon artifacts remain.
