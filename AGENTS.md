# Portfolio Repository Guidelines

## Code and styling
- Keep HTML, CSS, and JavaScript readable and consistently formatted.
- Never use inline CSS or one-line CSS blocks.
- Prefer shared classes and shared styles over duplicated page-specific styling.
- Do not change existing classes or IDs unnecessarily; preserve selectors used by JavaScript and navigation.
- Keep responsive behavior intentional across mobile, tablet, and desktop layouts.
- Respect `prefers-reduced-motion` for non-essential animation.

## Accessibility
- Use semantic HTML elements and a logical heading hierarchy.
- Provide meaningful labels for interactive controls and descriptive link text.
- Preserve visible keyboard focus states.
- Do not rely on color alone to communicate important information.

## Portfolio content
- Use the professional name **Henry D. James**.
- Do not invent employment history, credentials, achievements, metrics, client work, or social profiles.
- Use GitHub and email as the currently verified professional contact links unless the user provides additional active profiles.
- Keep project descriptions factual and based on the actual projects.
- Treat project screenshots, portraits, and other personal assets as placeholders until the user supplies the real assets.

## GitHub Pages
- The deployable site lives under `frontend/`.
- Preserve relative paths when adding pages beneath `frontend/projects/`.
- Changes should remain compatible with the GitHub Pages Actions workflow.
