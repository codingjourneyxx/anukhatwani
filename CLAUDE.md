# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Static HTML/CSS/JavaScript portfolio website for Anu Khatwani, an architect and interior designer. No build system or package manager dependencies - files are served directly.

## Development

This is a static site with no build process. To develop:
- Open any HTML file directly in a browser, or
- Use a local server (e.g., `npx serve` or VS Code Live Server extension)

## Architecture

### Page Structure
- **Root HTML files**: Main pages (`index.html`, `about-us.html`, `contact.html`, `portfolio.html`, `service.html`, `brand.html`, `press.html`, `video.html`)
- **portfoliodetail/**: Individual project detail pages (15 properties)
- **services/**: Service-related images

### Frontend Assets (`front/`)
- **css/**: Stylesheets - `style.css` contains custom styles, `responsive.css` for breakpoints, `global.css` for base styles. Uses Bootstrap, Font Awesome, Owl Carousel, Slick, Fotorama, jGallery
- **js/**: Scripts - `common.js` contains site-specific jQuery code. Uses jQuery, Bootstrap JS, Owl Carousel, Slick, Fotorama, Isotope, mCustomScrollbar
- **fonts/**: Custom font files
- **images/**: UI assets

### Other Directories
- **images/**, **mediaimages/**, **videos/**: Media content
- **schema.org/**: Structured data pages
- **signals/**: Signal/tracking related files

## Key Libraries
- jQuery (DOM manipulation, animations)
- Bootstrap 3 (grid, components)
- Owl Carousel (sliders)
- Slick (sliders)
- Fotorama (image galleries)
- Isotope (filtering/sorting layouts)
