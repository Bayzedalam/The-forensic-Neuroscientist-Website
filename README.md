# The Forensic Neuroscientist — editable website package

## Files
- `index.html` — homepage and all menu-matched sections.
- `style.css` — organised stylesheet with section headings and responsive breakpoints.
- `logo.svg` — concept logo inspired by the supplied reference; replace with client's official source logo if provided.
- `assets/` — artwork used in the design.
- `internal-page-template.html` — reusable starting point for internal pages.

## Section order
Home → About → Services → Training → Consultation → Videos → Blog → Contact.

## Editing CSS
Start at the top of `style.css` under `01. BRAND TOKENS` to change colours, fonts, sidebar width, content gutters, and section spacing. Each page section has its own labeled CSS group. Responsive rules are collected at the end of the stylesheet.

## Typography
Body text starts at 17px; paragraphs and card text are generally 14–18px. Main headings scale using `clamp()` for desktop and mobile.

## Notes before publishing
- The intro video uses the client's provided YouTube ID `uGySNlWnPRk`.
- Featured video cards other than the intro are design previews and link to the channel until individual video URLs are selected.
- The contact form is front-end only and must be connected to a secure form handler.
- The logo is a concept recreation, not a verified original client logo.
- The package contains HTML/CSS assets, not an editable Figma/XD source project.
