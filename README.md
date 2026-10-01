# ui-primitive 

A hyper-minimalist, zero-JavaScript CSS UI library. Built entirely with pure HTML and CSS. No build steps, no NPM packages, and no framework lock-in.

Designed with a **Copy & Paste** philosophy. You don't install this library; you own the code. Grab the CSS files you need, drop them into your project, and style your standard HTML elements directly.

##  Features

*   **100% Zero JavaScript:** Relies purely on the browser's CSS engine. Faster load times and zero parsing overhead.
*   **Native HTML Forms:** Uses standard `<input>`, `<label>`, and `<form>` tags. Perfect for native form submissions (PHP, Laravel, Django, etc.) and out-of-the-box SEO & Accessibility.
*   **Framework Agnostic:** Works perfectly in static HTML files, React, Vue, Svelte, or server-rendered templates.
*   **CSS Variable Theming:** Easily customize colors, borders, and radius globally using `--ui-*` variables.
*   **Dark Mode Ready:** Built-in `prefers-color-scheme` support for automatic dark mode switching.

##  Recommended Structure

Keep the component CSS files organized within your project's public or static assets folder:

```text
components/
        ├── input/    # Styles for input fields
        ├── radio    # Styles for radio buttons
        └── datepicker     # Styles for date pickers
