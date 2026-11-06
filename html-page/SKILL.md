---
name: html-page
description: >
  Use before writing any HTML page the user will see in the preview panel: a
  dashboard, a visual explanation, an interactive demo, a 3D scene, a landing
  page, a diagram too large for the chat components. Gives a tested base page,
  design rules, ready snippets (charts, diagrams, three.js) and a set of inline
  SVG icons, so the page looks designed and works in the sandboxed preview.
user-invocable: true
---

# HTML page for the preview

Use this skill when you have decided that an HTML page is the right answer. First check that it is: a chart, a table, a form, a diagram, a flow, a formula, a plan or a comparison are answered with the chat components (`seshat-ui`), not with a page. A page is for what the components cannot do (3D, animation, simulation, a free layout) or what the user asked to see as a page.

## Steps

1. **Start from the base.** Read `assets/base.html` and write the user's page from it: keep the `:root` tokens, the reset and the spacing, replace the content. Do not ship the base unchanged.
2. **Apply the rules** of `references/design-rules.md` (read it once, it is short): light background, one accent, system fonts, no emoji, no invented figures, responsive from 360px.
3. **Take what you need** from `references/patterns.md`: a Chart.js chart, a diagram with arrows, a three.js scene.
4. **Icons**: search `references/icons.md` with grep for the name of the icon (`### Search`, `### Download`, ...) and copy its inline `<svg>`. Never use an emoji or an icon font.
5. **Write one file** (`index.html` or a name that fits) with the Write tool, then tell the user in one or two sentences what it shows. Do not paste the code in the answer.

## What works in the preview

- One self-contained file. CSS and JavaScript inline.
- Libraries from `cdn.jsdelivr.net`, `unpkg.com` or `cdnjs.cloudflare.com` with an **exact version** (`chart.js@4.5.1`, `three@0.180.0`, `d3@7`, ECharts, Mermaid, Plotly, p5, GSAP, React, Vue, Tailwind). The app serves them from copies shipped with it.
- **Not available**: web fonts (Google Fonts), remote images, map tiles, any fetch to another site. The "problems on the page" counter may show these blocked requests; they are harmless but avoid them.

## Before you finish

- Read the page as the user: is there a title, a one-line lead, real content in every section, no placeholder?
- Is every colour a variable? Is there an emoji anywhere? Do the text and the background contrast enough?
- Does the layout hold at 360px wide and at 1100px?
