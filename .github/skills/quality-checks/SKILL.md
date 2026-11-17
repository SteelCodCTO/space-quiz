---
name: quality-checks
description: Run this skill when asked to invoke /quality-checks, validate a space-quiz change, or check behavior, accessibility, or visual updates. Use focused checks and preserve the dependency-free single-file app.
---

# Quality Checks

Use this skill when implementing or reviewing changes in this repository.

## Checks

- Keep the quiz in the dependency-free `index.html` unless the issue explicitly requires changing that structure.
- For behavior changes, add or update focused tests when a test runner exists. Verify the changed user flow in the integrated browser, including relevant boundaries and keyboard focus.
- Preserve semantic HTML, keyboard access, visible focus, and sensible focus movement.
- When changing styles or animations, respect `prefers-color-scheme` and `prefers-reduced-motion`.
- Run the smallest relevant test or check, inspect the final diff, and report only checks that were actually run.
