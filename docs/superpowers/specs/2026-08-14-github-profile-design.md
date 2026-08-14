# GitHub Profile README Design Spec

## Overview
This document specifies the design and structure for the GitHub profile README for `WildanFadillah1512`.
The chosen design direction is **The "Enterprise Command Center"**, which highlights the developer's expertise in Enterprise-Grade Dashboards & Complex Monitoring Systems.

## Architecture & Structure
The README utilizes HTML tables to create a grid layout, populated with highly customized, animated SVG widgets and dynamic statistic cards. The visual theme is Dark Mode / Glassmorphism with Cyan (`#00F0FF`) and Purple (`#B14BF4`) accents.

### 1. Hero Header (`assets/hero-dashboard.svg`)
- A custom SVG imitating a terminal/dashboard booting up.
- Features CSS `keyframes` for glowing text and pulse animations.
- Displays the core identity: "Wildan Fadillah", "Software Engineer | Full-Stack Developer | Modern Web Architect".

### 2. Tech Stack (`assets/tech-stack.svg`)
- A custom SVG with a glassmorphism style (`rgba` fills and strokes).
- Categorizes skills into `FRONTEND_LAYER`, `BACKEND_INFRA`, and `OPS_&_ARCHITECTURE`.
- Uses a monospace font (`Fira Code`) to maintain the terminal aesthetic.

### 3. GitHub Stats
- Uses `github-readme-stats` for dynamic metrics.
- Two cards (Overall Stats & Top Languages) displayed side-by-side using an HTML table.
- **Theme Config**: `tokyonight` base, customized with `bg_color=0D1117`, `title_color=00F0FF`, and `icon_color=B14BF4` to blend seamlessly with the dashboard.

### 4. Contribution Grid (Snake Animation)
- Integrated via `.github/workflows/generate-snake.yml`.
- The dark mode snake is customized to match the theme:
  - Snake color: Purple (`#B14BF4`)
  - Dots color gradient: From Dark GitHub background (`#0D1117`) to Neon Cyan (`#00F0FF`).

### 5. Contact / Establish Connection
- Customized `shields.io` badges for LinkedIn and Email.
- Badges use the dashboard colors: `#0D1117` background with Cyan logos and Purple text/borders.

## Testing & Verification
- SVGs must render correctly on both desktop and mobile GitHub apps.
- The `generate-snake.yml` workflow must run successfully and produce the customized palette.
- No markdown parsing errors within the HTML table layout.
