# Project Instructions

## Architecture

- This is a static page: [index.html](../index.html) contains the markup and [style.css](../style.css) contains its page styles. There is no framework or build pipeline.
- The current page is a login-form UI skeleton; the HTML owns its structure and the stylesheet its presentation.

## Build and Test

- No build, test, or lint commands are configured in this repository.
- Verify UI changes by opening `index.html` in a browser and checking the rendered page.

## Conventions

- Keep the stylesheet linked from the document head and keep styles in `style.css` rather than inline.
- Associate each form label with its input using matching `for` and `id` attributes; preserve the existing `username` and `password` field names and IDs when changing the login form.
