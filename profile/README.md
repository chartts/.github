<p align="center">
  <img src="https://chartts.com/og.png" alt="Chart.ts" width="600" />
</p>

<h3 align="center">Design-native charting for the modern web.</h3>

<p align="center">
  SVG-first · &lt;15kb gzipped · Tailwind-ready · TypeScript · React, Vue, Svelte, Solid, Vanilla JS
</p>

<p align="center">
  <a href="https://chartts.com">Website</a> · <a href="https://chartts.com/docs">Docs</a> · <a href="https://chartts.com/examples">Examples</a> · <a href="https://chartts.com/blog">Blog</a>
</p>

---

### Why Chart.ts?

Most charting libraries force you to fight their styling. Chart.ts is different. Every element exposes `className`, Tailwind `dark:` variants work out of the box, and your design tokens stay yours.

- **27 chart types** - line, bar, area, pie, scatter, radar, candlestick, heatmap, treemap, and more
- **SVG by default** - crisp at every zoom level, inspectable in devtools, accessible to screen readers
- **Auto-scales** - SVG under 10k points, Canvas at 10k+, WebGL at 100k+. Zero configuration.
- **WCAG 2.1 AA** - keyboard navigation, ARIA roles, pattern fills for color-blind users
- **Truly tiny** - core under 15kb gzipped. No heavy runtime.

### Quick start

```bash
npm install @chartts/react
```

```tsx
import { LineChart } from "@chartts/react"

<LineChart data={data} x="month" y="revenue" />
```

That's it. Labels, axes, tooltips, gradients, responsive scaling, dark mode. All automatic.

### Repos

| Repo | Description |
|------|-------------|
| [chartts](https://github.com/chartts/chartts) | Core library and framework packages |
| [chartts.com](https://github.com/chartts/chartts.com) | Documentation site, demos, and blog |

### Links

- [chartts.com](https://chartts.com) - docs, demos, API reference
- [npm: @chartts/core](https://npmjs.com/package/@chartts/core)
- MIT Licensed
