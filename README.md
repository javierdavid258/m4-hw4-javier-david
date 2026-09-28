# Module 4: CSS Flexbox Portfolio

David Javier's home/about portfolio page for MMC5277.

## Layout

Flexbox controls the page column, header, navigation, main content and sidebar, and social icon row. The only float wraps the About Me text around the profile photo. At smaller screen widths, the sidebar moves below the main content.

The page retains the Module 3 profile photo, placeholder biography, and background pattern. Social icons come from the provided assignment assets. LinkedIn and Stack Overflow currently link to their homepages.

## Links

- Repository: https://github.com/javierdavid258/m4-hw4-javier-david
- Site: https://javierdavid258.github.io/m4-hw4-javier-david/

## Local preview

Run `python3 -m http.server 8000` from this directory, then open http://localhost:8000.

## Implementation notes

The main layout change was replacing the header and column floats with Flexbox while retaining the profile image float for text wrapping. A mobile breakpoint stacks the content to prevent the fixed-width sidebar from crowding the biography.
