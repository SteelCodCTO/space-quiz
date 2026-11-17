# Repository guidance

- Keep the quiz as a single, dependency-free `index.html`; change that structure only when an issue explicitly requires it.
- Preserve semantic HTML and keyboard accessibility, including visible focus and sensible focus movement.
- Support the user's `prefers-color-scheme` and `prefers-reduced-motion` settings when changing styles or animations.
- For behavior changes, verify the result in the integrated browser and report what you tested.
