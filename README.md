# Job Tracker (PocketBase)

## Accessibility features included
- Skip link, landmarks, one `h1`, logical heading order
- Every input has a visible label; errors are plain-language, tied to the field via `aria-invalid`, and announced with `role="alert"`
- Status changes (added, updated, deleted, filter changes) are announced through a polite live region
- Native `<dialog>` for add/edit/delete: focus is trapped, Escape closes, focus returns to the button you came from
- Status is shown as text, never by color alone; filter buttons use `aria-pressed`
- Icon-free buttons with unique accessible names ("Edit Designer at Acme")
- Links that open a new tab say so to screen readers
- 44px minimum touch targets, strong visible focus ring, Atkinson Hyperlegible font
- Light/dark theme that follows the OS setting and can be toggled, `prefers-reduced-motion` and forced-colors support, and usable when zoomed to 200%
