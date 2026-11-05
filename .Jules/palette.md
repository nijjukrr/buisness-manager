## 2026-11-05 - Modal keyboard dismissal and icon button accessibility
**Learning:** In single-page vanilla web apps managing modals via CSS class toggling, overlay dismissals often omit keyboard Escape handlers and icon-only table action buttons lack accessible names for screen readers.
**Action:** When working on vanilla/PWA interfaces, inspect table action icons and overlay components to provide explicit `aria-label`, tooltips, global Escape listener, and visible focus rings.
