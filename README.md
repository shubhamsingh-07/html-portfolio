# HTML Portfolio Project

[![HTML5](https://img.shields.io/badge/HTML5-Portfolio-orange.svg)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A beginner-level static portfolio website built with HTML. The main page introduces a web developer portfolio and links to two sample projects: a movie-ranking page and a birthday-invitation page.

## Features

- Simple portfolio landing page with project previews.
- Navigation to movie-ranking and birthday-invitation pages.
- About and contact page links.
- A separate `solution.html` reference/example page.
- Local images stored in the `assets/` and `public/` folders.

## Project Structure

```text
html-portfolio/
├── index.html
├── solution.html
├── assets/
│   └── images/
└── public/
    ├── movie ranking page
    ├── birthday invite page
    ├── about page
    └── contact page
```

The exact filenames in `public/` and `assets/images/` include spaces and should be kept in sync with the relative links in the HTML.

## Run Locally

No build tools or package installation are required.

1. Clone or download the repository.
2. Open `index.html` in a modern browser.
3. Use the page links to explore the linked sample pages.

## Concepts Practiced

- HTML document structure and headings.
- Relative links between local HTML files.
- Images with alternate text and fixed preview dimensions.
- A simple multi-page website layout.

## Notes and Improvements

- The main page is static; it has no JavaScript, server, or data layer.
- Update the links if any linked file is renamed.
- Check that all image and linked-page paths work after downloading the repository.
- The repository contains preview images whose original source or redistribution terms may not be documented. Verify asset rights before reuse.

## License

Licensed under the MIT License. See [LICENSE](LICENSE) for details.
