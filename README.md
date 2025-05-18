# 3R4-OS Website

<h1 align="center">
  <a href="https://github.com/3R4-TBNKZ"><img src="https://github.com/3R4-TBNKZ/Book-s/blob/main/static/image/preview-banner-v1.png" alt="3R4"></a>
</h1>

3R4-OS is an optimized modification of Microsoft Windows tailored for gaming and performance. This repo contains the source code for the official website (https://3r4os.net), built with Astro, Tailwind CSS, and Bun.

---

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Available Scripts](#available-scripts)
- [Configuration](#configuration)
- [License](#license)

---

## Prerequisites

- **Bun** ≥ 1.0.0
- **Node.js** ≥ 18.0.0

## Installation

```bash
bun install
```

## Available Scripts

| Command         | Description                          |
| --------------- | ------------------------------------ |
| `bun dev`       | Start local Astro development server |
| `bun run build` | Build production site & run Jampack  |
| `bun preview`   | Preview production build locally     |
| `bun format`    | Format files with Prettier           |
| `bun run lint`  | Lint code with ESLint                |
| `bun run check` | Runs the Astro check command         |

## Configuration

- **Astro config**: `astro.config.mjs` (integrations, `site`)
- **Tailwind config**: `globals.css` (minimal config, theme)
- **ESLint config**: `.eslintrc.cjs` (Astro + TypeScript rules)
- **EditorConfig**: `.editorconfig` (consistent editor settings)
- **Gitignore**: ignores Jampack cache in `.jampack/`, build output, lockfiles, etc.

## License

This project is licensed under the **MIT License**. See the `license` field in `package.json` for details.
