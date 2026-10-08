# ui-primitive 

A hyper-minimalist, zero-JavaScript CSS UI library. Built entirely with pure HTML and CSS. No build steps, no NPM packages, and no framework lock-in.

Designed with a **Copy & Paste** philosophy. You don't install this library; you own the code. Grab the CSS files you need, drop them into your project, and style your standard HTML elements directly.

## Progress

| Category | Status |
|---|---|
| Text Input | 50/50 |
| Radio | 15/50 |
| Datepicker | 50/50 |

## Features

*   **100% Zero JavaScript:** Relies purely on the browser's CSS engine. Faster load times and zero parsing overhead.
*   **Native HTML Forms:** Uses standard `<input>`, `<label>`, and `<form>` tags. Perfect for native form submissions (PHP, Laravel, Django, etc.) and out-of-the-box SEO & Accessibility.
*   **Framework Agnostic:** Works perfectly in static HTML files, React, Vue, Svelte, or server-rendered templates.
*   **CSS Variable Theming:** Each component declares its own CSS custom properties (--accent, --border, --text, ...) on its root class. Edit them directly after copying.
*   **Dark Mode Ready:** Dark mode via prefers-color-scheme is included in newer components (radio-16+, datepicker-01+); older components are being retrofitted.

## Browser support

*   Components using `:has()` require Chrome/Edge 105+, Safari 15.4+, Firefox 121+.

## Datepicker notes
*   Native popups are not themeable (they rely on the OS and browser implementation).
*   Popover calendars do not auto-close and the trigger mirror only covers the demo month(s), so for real data generate the day markup server-side (PHP/Laravel/Django templates) or add your own enhancement.

## Recommended Structure

```text
components/
        ├── text-input/input-NN/      # index.html, style.css
        ├── radio/radio-NN/           # index.html, style.css
        └── datepicker/datepicker-NN/ # index.html, style.css
```
