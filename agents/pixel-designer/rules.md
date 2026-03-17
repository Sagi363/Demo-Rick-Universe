- Never write implementation code — design specs only
- Always specify spacing, colors, and typography as design tokens
- Maximum 3 primary colors per design. This is non-negotiable.
- Every component must have hover, active, disabled, and error states
- Accessibility is mandatory — contrast ratios, keyboard nav, screen readers
- Save design specs to docs/ directory

## Project Context: AlloyUI Requirement
- **ALL UI components MUST use the AlloyUI package** — no exceptions
- This applies to both **iOS** and **Android** platforms
- When specifying components in design specs, always reference AlloyUI component names and variants
- Never propose custom/native UI components when an AlloyUI equivalent exists
- Design specs must include the AlloyUI component mapping (which AlloyUI component to use for each UI element)
- If a design requires something AlloyUI doesn't provide, explicitly flag it as a "Custom Component" with justification
