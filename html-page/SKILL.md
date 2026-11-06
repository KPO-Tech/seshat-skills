---
name: html-page
description: >
  Only for an HTML artifact: a single page written to be shown in the Seshat
  preview panel (a dashboard, a visual explanation, an interactive demo, a 3D
  scene, a diagram too large for the chat components). Gives a tested base
  page, design rules, ready snippets (charts, diagrams, three.js) and inline SVG
  icons, so the page looks designed and works in the sandboxed preview. Do not
  use it for a real project (a website or an app written as files in a
  workspace): use the other design and frontend skills for that.
user-invocable: true
---

# HTML page for the preview

Use this skill only to write an **HTML artifact**: one page made to be shown in the preview panel. For anything else (a real website or application built as files in a project, a component for an existing codebase, a redesign), do not use it: prefer the other design and frontend skills that are installed.

Use it when you have decided that an HTML page is the right answer. First check that it is: a chart, a table, a form, a diagram, a flow, a formula, a plan or a comparison are answered with the chat components (`seshat-ui`), not with a page. A page is for what the components cannot do (3D, animation, simulation, a free layout) or what the user asked to see as a page.

## Steps

The files of this skill are in `${SESHAT_SKILL_DIR}/html-page/`. Use these full paths: a relative path will not be found.

1. **Read the base**: `${SESHAT_SKILL_DIR}/html-page/assets/base.html`. Write the user's page from it: keep the `:root` tokens, the reset and the spacing, replace the content. Do not ship the base unchanged.
2. **Read the rules** once (they are short): `${SESHAT_SKILL_DIR}/html-page/references/design-rules.md`: light background, one accent, system fonts, no emoji, no invented figures, responsive from 360px.
3. **Only if the page needs it**, read `${SESHAT_SKILL_DIR}/html-page/references/patterns.md` (Chart.js chart, diagram with arrows, three.js scene). Skip it for a plain page.
4. **Icons**: pick the names from the list below, then fetch each icon with Grep on `${SESHAT_SKILL_DIR}/html-page/references/icons.md` (pattern `^### Name$`, with 2 lines after the match) and copy its `<svg>`. Never read `icons.md` whole (it is long), never use an emoji or an icon font.
5. **Write the page in one single call** of the file tool (`index.html` or a name that fits), then tell the user in one or two sentences what it shows. Do not paste the code in the answer.
6. **If a tool refuses the write** (a permission message, a block), do not look for a way around it with other tools or by cutting the file in pieces: say what was refused and ask the user.

Icon names: Plus Minus Close CloseOne Check CheckOne Edit Delete Copy Download Upload Share ShareOne Refresh Search Filter SortThree More SettingTwo Save LinkOne Printer Lock Unlock Star Like Mail SendEmail Attention Help Info Caution Power Up Down Left Right ArrowUp ArrowDown ArrowLeft ArrowRight DoubleRight DoubleLeft Back Return Switch Transfer FullScreen Rotate Redo Undo LoadingOne TrendTwo Trend FileText FileTextOne FileCode FileDoc FileZip Folder FolderOpen DataSheet Table ChartHistogram ChartLine ChartPie ChartGraph ChartProportion Analysis Calendar Time Timer History Bookmark Tag Notebook Paperclip Code CodeBrackets Terminal Computer Cpu Server Wifi Api Branch GithubOne Bug Tool Config Plug PlugOne Robot Magic Cube Layers Key Shield ShieldAdd Fingerprint ApplicationOne Browser Application User Peoples People Home Local Globe Earth Compass Flag Mark Trophy Target Rocket Lightning Fire Sun Moon Water Tree Leaf Brain Book BookOpen Message Comment Phone Camera Video Music Pic Headset VolumeNotice Translate Wallet Currency ShoppingCart Gift Heart

## What works in the preview

- One self-contained file. CSS and JavaScript inline.
- Libraries from `cdn.jsdelivr.net`, `unpkg.com` or `cdnjs.cloudflare.com` with an **exact version** (`chart.js@4.5.1`, `three@0.180.0`, `d3@7`, ECharts, Mermaid, Plotly, p5, GSAP, React, Vue, Tailwind). The app serves them from copies shipped with it.
- **Not available**: web fonts (Google Fonts), remote images, map tiles, any fetch to another site. The "problems on the page" counter may show these blocked requests; they are harmless but avoid them.

## Before you finish

- Read the page as the user: is there a title, a one-line lead, real content in every section, no placeholder?
- Is every colour a variable? Is there an emoji anywhere? Do the text and the background contrast enough?
- Does the layout hold at 360px wide and at 1100px?
