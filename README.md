# One Page Site - SCSS Framework

A one page responsive website built with a small SCSS framework written from scratch. No Bootstrap import, everything is custom.

## What's inside

- A 12-column grid system with responsive breakpoints
- Utility classes for layout and spacing
- Button styles
- SCSS partials for variables, grid, buttons, and utilities

## Files

- `_variables.scss` - colors, breakpoints, and media query mixins
- `_grid.scss` - container, row, and the 12-column grid generated with a loop
- `_buttons.scss` - button styles
- `_utilities.scss` - helper classes for alignment, margins, text
- `style.scss` - main file that imports the partials
- `task2.html` - the one page site

## Grid

The grid generates columns from 1 to 12 using an SCSS loop. Columns stack to full width on mobile and tablet screens. Breakpoints are defined in `_variables.scss`.

## Running it

You need Sass installed to compile the SCSS files. From the task2 folder:

```
sass style.scss style.css
```

Open task2.html in a browser after compiling.

## Notes

The page is designed around three breakpoints: mobile (under 576px), tablet (under 768px), and laptop (under 992px). The navigation switches to a hamburger icon on small screens and the multi-column layout becomes a single column.

Built as practice to understand how frameworks like Bootstrap work.
