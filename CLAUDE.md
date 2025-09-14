# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static website for "The Lounge Bars" - a gin & cocktail bar business with locations in Alcester and Astwood Bank. The project is a simple HTML/CSS website showcasing the business locations and information.

## Architecture

- **Static HTML Site**: Single-page website built with vanilla HTML, CSS, and no build process
- **Structure**: 
  - `index.html` - Main HTML file containing the complete page structure
  - `styles.css` - All styling including responsive design and CSS custom properties
  - `images/` - Static image assets for the business locations

## Key Components

- **Header**: Centered logo with location names on either side using CSS Grid
- **Hero Section**: Background image with overlay text using CSS custom properties for dynamic image URLs
- **Content Cards**: Responsive card layout for location information with hover effects
- **CSS Variables**: Custom properties defined in `:root` for consistent branding colors

## Development

This is a static website with no build process, package manager, or testing framework. Changes can be made directly to the HTML and CSS files and viewed by opening `index.html` in a browser.

### File Structure
```
/
├── index.html          # Main HTML file
├── styles.css          # All CSS styling
└── images/            # Static image assets
    ├── img2.jpg
    ├── lounge-26-card.jpeg
    └── lounge-card.jpeg
```

### CSS Architecture
- Uses CSS custom properties for theming (`--lounge-blue`, `--lounge-red`, `--white`)
- Mobile-first responsive design with breakpoints at 768px and 480px
- CSS Grid for header layout, Flexbox for content cards
- Utility classes for responsive typography

### Known Issues
- TODO comment in HTML indicates logo centering issue due to different text sizes in header (line 13)
- Second lounge card is currently commented out (lines 45-57)