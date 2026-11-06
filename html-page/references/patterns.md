# Patterns

Snippets to adapt inside `assets/base.html`. Libraries load from jsDelivr with an exact version; the preview serves them from copies shipped with the app, so they work offline. Web fonts and remote images do not load.

## Chart (Chart.js)

```html
<div class="card"><canvas id="chart-revenue" height="120"></canvas></div>
<script src="https://cdn.jsdelivr.net/npm/chart.js@4.5.1/dist/chart.umd.min.js"></script>
<script>
const css = getComputedStyle(document.documentElement)
new Chart(document.getElementById('chart-revenue'), {
  type: 'bar',
  data: { labels: ['Q1','Q2','Q3','Q4'], datasets: [{ label: 'Revenue', data: [12,19,14,23],
    backgroundColor: css.getPropertyValue('--accent').trim(), borderRadius: 6 }] },
  options: { plugins: { legend: { display: false } }, scales: { y: { grid: { color: css.getPropertyValue('--border').trim() } }, x: { grid: { display: false } } } }
})
</script>
```

Read the colours from the CSS variables so the chart follows the theme. Use ECharts instead for maps, heatmaps, sankey or hundreds of points.

## Diagram: boxes in a grid, arrows in one SVG layer

```html
<div class="card" style="position:relative" id="diagram">
  <div class="grid" style="grid-template-columns:repeat(3,1fr);gap:80px">
    <div class="card" id="n-client">Client</div>
    <div class="card" id="n-api">API</div>
    <div class="card" id="n-db">Database</div>
  </div>
  <svg style="position:absolute;inset:0;width:100%;height:100%;pointer-events:none" id="lines">
    <defs><marker id="h" viewBox="0 0 10 10" refX="9" refY="5" markerWidth="7" markerHeight="7" orient="auto"><path d="M0 0L10 5L0 10z" fill="var(--muted)"/></marker></defs>
  </svg>
</div>
<script>
function link(from, to, label){
  const box = document.getElementById('diagram').getBoundingClientRect()
  const a = document.getElementById(from).getBoundingClientRect(), b = document.getElementById(to).getBoundingClientRect()
  const x1 = a.right - box.left, y1 = a.top + a.height/2 - box.top, x2 = b.left - box.left, y2 = b.top + b.height/2 - box.top
  const svg = document.getElementById('lines')
  svg.insertAdjacentHTML('beforeend',
    `<line x1="${x1}" y1="${y1}" x2="${x2}" y2="${y2}" stroke="var(--muted)" stroke-width="1.5" marker-end="url(#h)"/>` +
    `<text x="${(x1+x2)/2}" y="${y1-8}" text-anchor="middle" font-size="12" fill="var(--muted)">${label}</text>`)
}
link('n-client','n-api','HTTPS'); link('n-api','n-db','SQL')
</script>
```

Give every box a unique id (`n-...`), never `a` or `c`. Leave 80px between boxes for the arrows and their labels. For a graph with many nodes and free layout, use Mermaid or D3 (`https://cdn.jsdelivr.net/npm/d3@7`).

## 3D scene (three.js)

```html
<div id="stage" style="height:480px;border-radius:var(--radius);overflow:hidden;background:#0b1020"></div>
<script type="importmap">{"imports":{"three":"https://cdn.jsdelivr.net/npm/three@0.180.0/build/three.module.js","three/addons/":"https://cdn.jsdelivr.net/npm/three@0.180.0/examples/jsm/"}}</script>
<script type="module">
import * as THREE from 'three'
import { OrbitControls } from 'three/addons/controls/OrbitControls.js'
const el = document.getElementById('stage')
const scene = new THREE.Scene()
const camera = new THREE.PerspectiveCamera(50, el.clientWidth / el.clientHeight, 0.1, 100)
camera.position.set(0, 2, 6)
const renderer = new THREE.WebGLRenderer({ antialias: true })
renderer.setSize(el.clientWidth, el.clientHeight)
el.appendChild(renderer.domElement)
new OrbitControls(camera, renderer.domElement)
scene.add(new THREE.AmbientLight(0xffffff, 0.6), new THREE.DirectionalLight(0xffffff, 1.2))
const mesh = new THREE.Mesh(new THREE.SphereGeometry(1, 48, 48), new THREE.MeshStandardMaterial({ color: 0xea580c }))
scene.add(mesh)
renderer.setAnimationLoop(() => { mesh.rotation.y += 0.005; renderer.render(scene, camera) })
</script>
```

A 3D or space subject may use a dark stage inside a light page. Draw textures with canvas or colours; do not load image files.

## Map (Leaflet)

Leaflet tiles are remote images and do not load. Draw the map as inline SVG, or show positions on a plain grid, unless the user supplies the data and accepts that the tiles stay blank.

## Table with state

Use a real `table`, a header row, right-aligned numbers, and an empty state row ("No data yet") when the list can be empty.
