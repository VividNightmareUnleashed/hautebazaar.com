# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Haute Bazaar is a static website for a contemporary culture magazine featuring influential people in art, fashion, culture, and innovation. The site showcases individual portraits with in-depth features about remarkable individuals shaping our world.

## Architecture

This is a single-page static website with a simple structure:
- **No build tools or frameworks** - Pure HTML, CSS, and vanilla JavaScript
- **Single page application** with smooth scrolling between sections
- **Responsive design** using CSS Grid and Flexbox
- **Pink-themed aesthetic** with gradient backgrounds and glassmorphism effects

## File Structure

```
hautebazaar.com/
├── index.html       # Main HTML file with all content
├── css/
│   └── styles.css   # All styling (animations, responsive design, themes)
├── js/
│   └── main.js      # JavaScript for scroll effects and animations
└── images/          # Directory for images (currently empty, using Lorem Picsum)
```

## Key Features

1. **Navigation**: Fixed navbar with scroll-based styling changes
2. **Hero Section**: Large typography with gradient text effects
3. **Latest Issue**: Featured person highlight with cover image
4. **Featured Articles**: Grid of past featured individuals
5. **Past Issues Archive**: Grid view of all magazine issues
6. **Animations**: Intersection Observer for scroll-triggered animations

## Development Workflow

Since this is a static site with no build process:
1. Edit files directly in your preferred editor
2. Open `index.html` in a web browser to preview changes
3. Use a local web server (e.g., VS Code Live Server) for better development experience
4. All images currently use Lorem Picsum placeholders (https://picsum.photos/)

## Current State

The website is fully designed but uses placeholder content:
- All person names are fictional placeholders
- All images use Lorem Picsum random images
- Links are non-functional (href="#")
- Issue numbers go from 10-17 with seasonal dates