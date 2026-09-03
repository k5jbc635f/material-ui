# Accessibility (a11y)

Material UI components are designed to be accessible to all users, including those who rely on assistive technologies.

## Sound foundations

Accessibility is an essential requirement for web interfaces. We follow WAI-ARIA standards and strive to meet WCAG 2.1 AA guidelines across all components.

### Focus management

- All interactive elements are focusable using standard keyboard navigation (`Tab` key).
- Visible focus rings (`:focus-visible`) are preserved by default so sighted keyboard users can easily track focus position.
- Modals, Dialogs, and Drawers trap focus while open and automatically restore focus to the triggering element upon closing.

### Screen readers

- Appropriate ARIA attributes (`aria-expanded`, `aria-controls`, `aria-describedby`, `role`) are automatically managed by component states.
- Color alone is never used to convey state or meaning; visual indicators (icons, text labels) accompany state changes.
- Text contrast ratios meet or exceed the WCAG 4.5:1 minimum threshold for standard text.

### High contrast and forced colors

Material UI components support Windows High Contrast Mode (`forced-colors: active`), ensuring custom borders, outlines, and focus rings remain distinct when forced color themes are enabled.

## Resources

- [W3C WAI-ARIA Authoring Practices Guide (APG)](https://www.w3.org/WAI/ARIA/apg/)
- [Web Content Accessibility Guidelines (WCAG) 2.1](https://www.w3.org/TR/WCAG21/)