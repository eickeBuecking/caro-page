# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a modern portfolio website for Carolin Genreith, a German filmmaker (Filmemacherin). The site is built with vanilla HTML and CSS, featuring a clean, responsive design that showcases her vita, films, TV work, awards, and contact information.

## Architecture

### Structure
- **index.html** - Single-page application with semantic HTML5 structure
- **style.css** - Modern CSS using CSS Grid, Flexbox, and CSS custom properties (variables)
- **img/** - Directory containing all background images from the original site

### Design Philosophy
- Modern, minimalist design with clean typography
- Mobile-first responsive approach
- Smooth scrolling navigation
- All content preserved from original website at carolin-genreith.de
- No frameworks or build tools - pure vanilla HTML/CSS/JavaScript

## Content Structure

The page follows a single-page scroll layout with these sections:
1. **Hero** - Full-screen hero image with site title
2. **Vita** - Biography text
3. **Filme** - Film projects and productions
4. **TV & Co** - TV work as author and producer
5. **Auszeichnungen** - Awards and recognitions
6. **Impressum** - Contact information

Each content section is separated by full-width background images.

## CSS Architecture

### Custom Properties (CSS Variables)
All design tokens are defined in `:root`:
- Colors: `--primary-color`, `--text-color`, `--bg-color`, etc.
- Typography: `--font-primary`, `--font-headings`
- Spacing: `--spacing-xs` through `--spacing-xl`
- Container widths: `--container-width`, `--content-width`

### Layout System
- Navigation: Fixed positioning with sticky behavior on scroll
- Sections: Flexbox for general layout
- Responsive: Mobile-first breakpoints at 768px and 480px
- Content containers: Max-width constraints for readability

## JavaScript Features

Minimal vanilla JavaScript for:
- Mobile menu toggle functionality
- Smooth scrolling to anchor links
- Sticky navigation on scroll
- Auto-closing mobile menu on navigation

## Development

### Local Development
Simply open `index.html` in a web browser. For a better development experience with live reload:
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js
npx serve
```

Then navigate to `http://localhost:8000`

### Editing Content
- All text content is in `index.html` within semantic HTML elements
- All styling is in `style.css` - no inline styles
- Images are referenced from the `img/` directory

### Responsive Testing
Test at these breakpoints:
- Desktop: 1200px+ (default)
- Tablet: 768px - 1199px
- Mobile: 480px - 767px
- Small Mobile: < 480px

## Important Notes

### Content Preservation
All original content from carolin-genreith.de has been preserved exactly:
- All text in German language
- All film titles and descriptions
- All dates and awards
- All contact information
- All background images

### Design Improvements
Modern enhancements over the original:
- Clean, minimal aesthetic
- Better typography and spacing
- Fully responsive on all devices
- Faster loading (no WordPress overhead)
- Smooth animations and transitions
- Better accessibility

## File Organization
```
caro-page/
├── index.html          # Main HTML file
├── style.css           # All styles
├── img/                # Image assets
│   ├── start.jpg
│   ├── filme.jpg
│   ├── tvundco.jpg
│   ├── auszeichnungen.jpg
│   └── backup.jpg
└── CLAUDE.md          # This file
```

## Future Enhancements

Potential improvements to consider:
- Add meta tags for social media sharing (Open Graph, Twitter Cards)
- Implement a dark mode toggle
- Add lazy loading for images
- Add fade-in animations on scroll
- Add a "Back to top" button
- Optimize images for web (WebP format, responsive images)
