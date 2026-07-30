# 🚀 Sabyrka Vanilla Starter

A lightweight starter template for building websites with pure HTML, CSS and JavaScript.

## ✨ Features

- Semantic HTML structure
- Modern CSS setup
- Global styles and utility classes
- Normalize styles
- ESLint configuration
- Stylelint configuration
- Prettier formatting
- Husky + lint-staged
- GitHub Actions CI

## ⚙️ Getting started

Clone the repository:

```bash
git clone https://github.com/itssabyrka/vanilla-starter.git
```

Install dependencies:

```bash
pnpm install
```

## 📜 Available scripts

Format all supported files:

```bash
pnpm format
```

Run ESLint:

```bash
pnpm lint
```

Run Stylelint:

```bash
pnpm stylelint
```

Run all checks:

```bash
pnpm check
```

## 📁 Project Structure

```text
src/
├── assets/              # Static assets
│   ├── favicons/        # Favicon files
│   ├── fonts/           # Local fonts
│   ├── icons/           # SVG icons
│   └── images/          # Images
├── scripts/             # JavaScript files
│   └── main.js
├── styles/
│   ├── base/            # Normalize, variables, globals, fonts
│   ├── components/      # Reusable UI components
│   ├── layouts/         # Header, hero, footer, sections, grid
│   ├── utils/           # Utility classes and helpers
│   └── main.css
└── index.html
```

## 🎯 Purpose

This template is designed as a reusable foundation for small and medium frontend projects. It provides a ready-to-use setup so new projects can start with a clean architecture instead of an empty folder.
