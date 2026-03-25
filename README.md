# Graphoris

**Mac-native scientific graphing & diagramming for researchers, scientists, and data analysts.**

Graphoris combines publication-quality charting with general-purpose diagramming in a single fast, beautiful macOS app. Think *OmniGraffle meets GraphPad Prism* — modern, AI-powered, with fluid animations.

[![Download Latest](https://img.shields.io/github/v/release/ymkindhearted/graphoris-releases?label=Download&style=for-the-badge)](https://github.com/ymkindhearted/graphoris-releases/releases/latest)
[![macOS](https://img.shields.io/badge/macOS-15.0+-blue?style=for-the-badge&logo=apple)](https://github.com/ymkindhearted/graphoris-releases/releases/latest)
[![Swift](https://img.shields.io/badge/Swift-6.0-orange?style=for-the-badge&logo=swift)](https://swift.org)

---

## Features

### Scientific Charting
- **10+ chart types** — scatter, line, bar (grouped/stacked), area, histogram, box plot, violin, heatmap, error bar
- **3D charts** — scatter, surface, and bar charts rendered via Metal at 120fps
- **Publication presets** — Nature, Science, Minimal, Classic styles with proper figure dimensions
- **Scales** — linear, logarithmic, and category with full customization

### Compute Engine
- Curve fitting · FFT · Peak detection · Baseline correction (airPLS)
- Smoothing (Savitzky-Golay, Gaussian, moving average)
- Statistical tests (t-test, ANOVA, Wilcoxon, Mann-Whitney)
- Numerical calculus (differentiation, Simpson's integration)
- Expression parser for computed columns

### Diagramming
- Infinite canvas with shapes, text, connectors, and groups
- Auto-layout — force-directed and hierarchical algorithms
- Smart guides, snap-to-grid, alignment tools
- Layers, z-ordering, and object library

### AI-Powered
- Built-in AI chat with **62+ tools** for chart creation, styling, and data analysis
- Natural language to publication-ready figures
- Agentic workflow with tool dependency graphs

### Export
- **PDF** — vector, publication quality
- **SVG** — clean, semantic markup
- **PNG** — 1x, 2x, 3x Retina
- **EPS** — PostScript
- Clipboard support (vector + bitmap)

### MCP Server
- JSON-RPC 2.0 server (MCP 2024-11-05 spec)
- 16+ tools for programmatic figure creation
- Compatible with Claude Desktop and other MCP clients

---

## System Requirements

| | |
|---|---|
| **OS** | macOS 15.0 (Sequoia) or later |
| **Architecture** | Apple Silicon optimized (Universal) |

## Install

Download the latest **DMG** or **ZIP** from [Releases](https://github.com/ymkindhearted/graphoris-releases/releases/latest).

Auto-updates are built in via [Sparkle](https://sparkle-project.org/) — you will be notified when new versions are available.

---

## Built With

Swift · SwiftUI · Core Graphics · Metal · SceneKit · Accelerate

---

## Links

- [Website](https://graphoris.com)

---

*Made for scientists who care about their figures.*
