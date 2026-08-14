# GitHub Profile README Design Spec

## Overview
This document specifies the design for `WildanFadillah1512`.
The chosen design direction is **The "Interactive CLI Terminal"**, utilizing native GitHub markdown features like `<details>` and `<kbd>` to simulate a terminal interface without relying on external SVGs.

## Architecture & Structure
The README is structured as a series of expandable terminal commands.

### 1. Terminal Interface
- Uses `<details>` and `<summary>` tags.
- Command lines are wrapped in `<code>` tags (e.g., `$ whoami`, `$ ls -l ./tech_stack/`).

### 2. Tech Stack Representation
- Tech stack is presented inside a markdown table.
- Each technology is wrapped in a `<kbd>` tag to resemble keyboard keys or native badges.

### 3. GitHub Stats
- Uses `github-readme-stats` with standard `tokyonight` theme.
- Placed inside an expanded `<details>` block (`$ ./get_system_stats.sh`).

### 4. Contribution Grid (Snake Animation)
- Restored to the `github-dark` palette (Cyan & Purple) to match the default terminal look.

## Testing & Verification
- Verify that `<details>` tags expand and collapse correctly.
- Ensure all markdown tables render without breaking the `<details>` wrapper.
