# Copilot Instructions for Resto-Delivery

## Project Overview

This is a static HTML/CSS project for a restaurant delivery landing page. The codebase is simple, with no JavaScript or build tooling. All assets are local, and the site is designed for direct browser use.

## Structure

- `index.html`: Main entry point. Contains all markup for the homepage, including navigation, hero section, and customer showcase.
- `css/style.css`: All styles for the site. Uses BEM-like class naming and rem units for scalability.
- `img/`: Contains all images, including hero images, menu items, and customer avatars. Subfolder `img/customers/` holds customer images.

## Key Patterns & Conventions

- **Class Naming**: Uses descriptive, English class names (e.g., `.hero-section`, `.main-hero-section`, `.hero-bouton`).
- **Responsive Units**: Uses `rem` for font sizes and spacing for easy scaling.
- **No JavaScript**: All interactivity is via CSS (e.g., `:hover` effects). No scripts are present or expected.
- **Navigation**: The navigation bar is static. The `.command-bouton` class is used for the primary call-to-action.
- **Image Usage**: All images are referenced with relative paths. Customer images are grouped for easy iteration or replacement.

## Developer Workflows

- **Preview**: Open `index.html` directly in a browser. No build or serve step is required.
- **Add Images**: Place new images in `img/` or `img/customers/` and reference them with relative paths in HTML.
- **Style Changes**: Edit `css/style.css`. Use rem units and follow the existing class structure.

## Examples

- To add a new customer avatar: Place the image in `img/customers/` and add an `<img>` tag in the customer section of `index.html`.
- To add a new section: Add markup to `index.html` and style it in `css/style.css` using a new, descriptive class name.

## What Not To Do

- Do not add JavaScript or external dependencies.
- Do not introduce build tools or preprocessors.
- Do not use inline styles; keep all CSS in `style.css`.

## References

- Key files: `index.html`, `css/style.css`, `img/`, `img/customers/`
- No README or prior agent instructions exist as of this writing.

---

If you add new sections or patterns, update this file to document them for future AI agents and developers.
