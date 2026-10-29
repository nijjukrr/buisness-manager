## 2026-10-29 - Accessible Icon Buttons and Search Inputs in Vanilla JS PWA
**Learning:** Icon-only action buttons (`✕`, `✓`, `↺`) and search inputs rendered via JavaScript string templates often miss standard ARIA labels and tooltips, degrading screen reader accessibility and hover feedback.
**Action:** Always include both `aria-label` and `title` attributes when rendering dynamic icon-only action buttons and search inputs.
