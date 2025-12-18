# Tech Stack

## Template Base
HTML5 UP "Massively" template (CCA 3.0 license)

## Frontend
- HTML5 semantic markup
- CSS3 with SCSS preprocessing
- jQuery 3.x for DOM manipulation and animations

## Styling
- SCSS with modular architecture (libs, base, components, layout)
- Font Awesome 5 for icons (via CDN and local webfonts)
- Google Fonts: Merriweather (body), Source Sans Pro (headings)
- Responsive breakpoints: xxsmall (360px) to default (1681px+)

## JavaScript Libraries
- jquery.scrollex.min.js - Scroll event handling
- jquery.scrolly.min.js - Smooth scrolling
- breakpoints.min.js - Responsive breakpoint management
- browser.min.js - Browser detection

## Build System
No build tooling configured. SCSS must be compiled manually if modified.

### SCSS Compilation
If editing SCSS files, compile with:
```bash
sass assets/sass/main.scss assets/css/main.css
```

## Deployment
Static site - can be deployed to any web server or static hosting (GitHub Pages, Netlify, Firebase Hosting, etc.)
