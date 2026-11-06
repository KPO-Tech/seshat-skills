# Design rules for a page

Checkable rules. A page that follows them looks made by one careful hand; one that does not looks like default model output.

## The tells to avoid

1. **Default indigo or purple accent** (`#6366f1`, `#4f46e5`, `#8b5cf6`, `#7c3aed`). Use the accent of `assets/base.html` or one that fits the subject.
2. **A two-colour gradient on the hero** (purple to blue, blue to cyan). A flat surface and a good heading beat it.
3. **Emoji as icons** in headings, buttons, lists. Use the inline SVG icons of `icons.md`.
4. **A rounded card with a coloured stripe on its left edge.** Drop either the radius or the stripe.
5. **Invented figures** ("10x faster", "99.9% uptime", "3x more productive"). Use the user's numbers or label a placeholder as such.
6. **Filler copy** (lorem ipsum, "Feature one", "placeholder text"). Write real content or remove the section.
7. **The same skeleton every time** (hero, three features, pricing, FAQ). Pick the structure from the content.
8. **Linked images** (Unsplash, placeholder services). The preview blocks them. Draw with SVG or CSS.

## Colour

- Colours are CSS variables on `:root`; elements use `var(--name)`. At most about a dozen raw hex values outside `:root`.
- Light background by default. Dark only when the reader asks, by redefining the variables.
- One accent colour, used for the main action and one or two highlights per screen. Green, amber and red mean ok, warning, danger, never decoration.
- Text and background must keep a contrast of 4.5:1 or more (3:1 for large text). Muted text is still readable.

## Type and space

- System fonts only (`--font`, `--mono`): web fonts do not load in the preview.
- Body 15-16px with a line height of 1.5-1.65. Headings differ by size and weight, two or three levels at most. Nothing under 13px.
- Spacing in multiples of 8px (8, 16, 24, 32, 40). One radius for cards and one for controls.
- Text blocks stay under about 70 characters wide (`max-width:60ch`).

## Structure

- One idea per section, a heading for each, and a short lead under the title that says what the page shows.
- A diagram has a title, labelled arrows and a legend if colours carry meaning. Group by layer or stage, not by the order of writing.
- Every control is a real `button`, `input`, `select` or `a`, with a visible focus ring and a label. Show the state of the page when it is empty or in error, not only when it is full.
- Responsive from 360px: use `grid` with `auto-fit`, no fixed widths over the width of the panel. The page is read in a side panel.

## Motion

- Motion explains a change (a value that moves, a panel that opens), it does not decorate. 150-250ms, ease-out. Respect `prefers-reduced-motion`.

## Sources

Adapted from the Open Design craft notes (Apache-2.0) and the refero skill (MIT).
