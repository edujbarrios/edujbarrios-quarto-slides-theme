# edujbarrios Quarto Slides Theme

[![License: MIT](https://img.shields.io/badge/License-MIT-40e0d0.svg)](LICENSE)
[![Quarto](https://img.shields.io/badge/Quarto-%3E%3D1.4.0-8b5cf6.svg)](https://quarto.org/)

An open-source Quarto presentation theme based on the visual branding of
[edujbarrios.com](https://edujbarrios.com/): dark charcoal surfaces, turquoise
signals, violet depth, and warm orange highlights.

## Preview

![Example presentation theme preview](assets/example-preview.png)

## Features

- Revealjs format extension for Quarto presentations
- Dark brand palette with turquoise, violet, and orange accents
- Utility classes for cards, metric tiles, tags, section titles, and columns
- Sensible defaults for code blocks, slide numbers, transitions, and links

## Palette

The theme mirrors the current site identity:

![Turquoise primary signal](https://img.shields.io/badge/turquoise-primary_signal-40e0d0?style=for-the-badge)
![Teal accent reference](https://img.shields.io/badge/teal-accent_reference-008080?style=for-the-badge)
![Violet secondary depth](https://img.shields.io/badge/violet-secondary_depth-8b5cf6?style=for-the-badge)
![Violet soft gradient](https://img.shields.io/badge/violet_soft-gradient-a78bfa?style=for-the-badge)
![Orange warm highlight](https://img.shields.io/badge/orange-warm_highlight-fb923c?style=for-the-badge)
![Canvas dark surface](https://img.shields.io/badge/canvas-dark_surface-0b0f14?style=for-the-badge)
![Surface dark panel](https://img.shields.io/badge/surface-dark_panel-111827?style=for-the-badge)
![Surface 2 dark depth](https://img.shields.io/badge/surface_2-dark_depth-1b1b1d?style=for-the-badge)

## Install

```bash
quarto add edujbarrios/edujbarrios-quarto-slides-theme
```

## Use

```yaml
---
title: "Your Talk"
format: edujbarrios-revealjs
---
```

For local development in this repository, render the included example:

```bash
quarto render example.qmd
```

The rendered `example.html` and supporting files are generated artifacts and are
not committed to the repository.

## Slide Helpers

The theme includes a small utility vocabulary:

- `.eyebrow`: compact label above a headline
- `.brand-card`, `.compact-card`: bordered content blocks
- `.metric`, `.value`, `.label`: stat cards
- `.tag-list`, `.tag`: skill or topic chips
- `.two-column`, `.three-column`: responsive layout helpers
- `.accent`, `.violet`, `.orange`, `.muted`: brand color helpers

See `example.qmd` for a complete product-style deck based on
[`edujbarrios/neural-audio-theory`](https://github.com/edujbarrios/neural-audio-theory).

## License

MIT
