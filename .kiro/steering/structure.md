# Project Structure

```
├── index.html              # Main portfolio page
├── images/                 # Project screenshots and assets
│   └── favicon_io/         # Favicon variants
└── assets/
    ├── css/                # Compiled CSS
    │   ├── main.css        # Primary stylesheet
    │   ├── noscript.css    # Fallback for JS-disabled browsers
    │   └── fontawesome-all.min.css
    ├── js/                 # JavaScript files
    │   ├── main.js         # Custom site logic (parallax, nav panel, scroll effects)
    │   ├── util.js         # Utility functions
    │   └── *.min.js        # Third-party libraries (jQuery, scrollex, etc.)
    ├── sass/               # SCSS source files
    │   ├── main.scss       # Entry point - imports all partials
    │   ├── libs/           # Variables, mixins, functions, breakpoints
    │   ├── base/           # Reset, page, typography
    │   ├── components/     # Reusable UI components (buttons, forms, icons, etc.)
    │   └── layout/         # Page sections (wrapper, intro, header, nav, main, footer)
    └── webfonts/           # Font Awesome font files
```

## Key Files
- `index.html` - All content lives here; edit to add/modify portfolio items
- `assets/sass/libs/_vars.scss` - Color palette, fonts, sizing variables
- `assets/js/main.js` - Parallax, nav panel toggle, scroll-based animations

## Conventions
- Portfolio items are `<article>` elements within `<section class="posts">`
- Featured project uses `<article class="post featured">`
- External links should include `target="_blank"`
- Images stored in `/images/` with descriptive filenames
