# Palette's Journal - Critical UX & Accessibility Learnings

## 2026-01-11 - Icon Button Accessibility & Modal Dismissal in Single-File PWA
**Learning:** In lightweight vanilla JS PWAs without component libraries, dynamic icon-only buttons (like `✕`, `✓`, `↺`) and custom modal overlays frequently omit ARIA labels, descriptive titles, and standard keyboard dismissal (Escape / overlay click). Screen reader users hear only characters like "cross mark" or "check mark", and keyboard users get trapped inside overlays without an Escape shortcut.
**Action:** Always provide descriptive `aria-label` and `title` attributes on dynamically rendered icon action buttons, ensure `.btn:disabled` has clear visual and cursor states, and attach global Escape key and backdrop click handlers with `role="dialog"` and `aria-modal="true"` to modals.
