# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

A static website guide for Chicago Restaurant Week 2026, created in collaboration with Chicago content creator Paige Serena (@plateswithps). The site helps diners identify the best value deals by comparing Restaurant Week special menus against regular pricing.

## Development

This is a static HTML/CSS site with no build system, package manager, or dependencies.

**To view locally:**
```bash
open index.html
```

## Architecture

- **index.html** (~314KB) - Main guide with all restaurant listings, comparison data, filtering/sorting UI, and shortlist functionality. Contains embedded CSS and JavaScript.
- **disclaimer.html** - Methodology, disclaimers, and support information page.

All styles are inline within each HTML file using CSS custom properties for theming.

## Design System

Color palette (CSS variables in `:root`):
- `--cream` / `--warm-white` - Background colors
- `--terracotta` / `--terracotta-light` - Accent/brand colors
- `--sage` / `--sage-light` - Secondary accent
- `--charcoal` / `--warm-gray` - Text colors
- `--light-gray` - Borders and dividers

Typography:
- Cormorant Garamond (serif) - Headings
- DM Sans - Body text

Both fonts loaded from Google Fonts.
