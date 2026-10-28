# Palette's Journal - ANNAI STORE

## 2026-10-28 - Icon-only buttons and keyboard focus states
**Learning:** Single-file vanilla JS apps using tables for records often miss explicit ARIA labels on dynamic table row actions (e.g. `✓`, `↺`, `✕`), leaving screen readers unable to convey button intent. Adding `aria-label` and `title` tooltips along with CSS `:focus-visible` ring outlines significantly enhances accessibility without layout shifts or extra dependencies.
**Action:** When adding or updating dynamically generated table actions, always include `aria-label` and `title` attributes matching the intended action.
