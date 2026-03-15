# Images

This directory contains image assets used by the **Smell-AI** project (e.g., screenshots for documentation, diagrams, and other static visuals).

## Contents

- **Documentation screenshots**: UI flows, model outputs, or application examples used in READMEs and wiki pages.
- **Diagrams**: architecture, data pipeline, and system design visuals.
- **Branding assets**: logos or icons (if applicable).

## Conventions

To keep assets easy to find and maintain:

- Use **descriptive, kebab-case filenames** (e.g., `model-output-example.png`, `ui-home-screen.png`).
- Prefer **PNG** for screenshots and diagrams; use **SVG** for vector graphics when appropriate.
- Keep images **optimized** (reasonable dimensions and compressed) to reduce repository size.
- Avoid committing sensitive data in screenshots (API keys, personal information, internal URLs).

## Recommended structure (optional)

If this folder grows, consider organizing it as:

- `images/screenshots/`
- `images/diagrams/`
- `images/icons/`

## Notes

If you reference images from Markdown, use relative paths such as:

```md
![Example](./screenshots/example.png)
```

---

Maintained by the Smell-AI contributors.
