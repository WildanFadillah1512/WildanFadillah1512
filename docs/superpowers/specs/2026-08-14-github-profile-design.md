# GitHub Profile README Design Spec

## Overview
This document specifies the design and structure for the GitHub profile README for `WildanFadillah1512`. The goal is to create a modern, dynamic, and visually appealing profile that highlights the developer's tech stack, projects, and GitHub metrics.

## Architecture & Structure
The README will follow a top-to-bottom layout, utilizing Markdown, HTML, and dynamic SVG widgets.

### 1. Hero Header
- **Typing Animation**: Using `readme-typing-svg` to display a dynamic greeting.
  - Text lines: "Hi there 👋, I'm Wildan Fadillah", "Full-Stack Developer", "Always learning and building"
  - Styling: Color `#00F0FF` (Cyan/Neon), size 22, center aligned.

### 2. About Me
A concise section using emoji bullet points:
- 🔭 Saat ini fokus pada: Pengembangan Full-Stack (Vue, Laravel, TS)
- 🌱 Sedang memperdalam: Arsitektur software dan praktik modern web
- 💬 Tanyakan saya tentang: Vue, Laravel, TypeScript, atau Frontend Design
- 📫 Hubungi saya: Melalui LinkedIn atau Email (Tautan akan disesuaikan di file)

### 3. Tech Stack & Tools
Categorized skills using customized `shields.io` badges for a clean look.
- **Frontend**: Vue.js, TypeScript, HTML5, CSS3
- **Backend**: PHP, Laravel (Blade)
- **Tools**: Git, VS Code
- **Styling**: `for-the-badge` style with specific hex colors matching the brand of each technology.

### 4. GitHub Stats
Utilizing `github-readme-stats` to dynamically display GitHub metrics.
- **Stat Cards**:
  1. **Overall Stats**: Shows Stars, Commits, PRs, and Issues.
  2. **Top Languages**: Shows a pie/bar chart of the most used languages in repositories.
- **Theming**: Dark mode theme (e.g., `tokyonight`, `dracula`, or custom neon colors) to match the modern aesthetic. Both cards aligned side-by-side using an HTML table or flex/wrap equivalent in markdown.

## Testing & Verification
- Verify that SVGs load correctly.
- Ensure the layout remains intact on both desktop and mobile views (especially the side-by-side stats cards).
- Confirm the `github-readme-stats` URLs correctly target the `WildanFadillah1512` username.

## Out of Scope
- Creating actual code repositories. This task focuses entirely on the profile README itself.
