

<h1 align="center">Graphoris</h1>

<p align="center">
  <strong>Mac-native scientific plotting, supercharged by AI.</strong><br>
  Free OriginPro alternative for macOS — built with Swift and Metal GPU acceleration.
</p>

<p align="center">
  <a href="https://graphoris.space">Website</a> ·
  <a href="https://github.com/ymkindhearted/graphoris-releases/releases/latest">Download</a> ·
  <a href="https://discord.gg/m22VDa4ZSs">Discord</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/platform-macOS-blue" alt="macOS">
  <img src="https://img.shields.io/badge/price-Free-brightgreen" alt="Free">
  <img src="https://img.shields.io/badge/MCP-supported-orange" alt="MCP">
  <img src="https://img.shields.io/badge/GPU-Metal-purple" alt="Metal">
  <img src="https://img.shields.io/github/v/release/ymkindhearted/graphoris-releases" alt="Latest Release">
</p>

---

## Why Graphoris?

AI tools like Claude can generate great plots — but editing them means re-prompting for every tiny change. And OriginPro still doesn't run on Mac.

Graphoris solves both: AI creates charts inside the app, and you edit everything with your mouse. No more Parallels, no more re-prompting.


## Features

**AI-Powered Plotting**
- MCP server — connect Claude Desktop, Claude Code, Cursor, or any MCP-compatible AI
- Built-in AI assistant (GRAPO) for peak detection, curve fitting, and data analysis
- Natural language commands via ⌘K palette

**Metal GPU Acceleration**
- Smooth 60fps rendering even with 100K+ data points
- 3D scatter, surface, and bar charts — all GPU-accelerated
- Native Apple Silicon optimization
https://github.com/user-attachments/assets/ce4a8ff4-1e9d-4929-bc1e-3925743280c8

**Every Chart You Need**
- Scatter, line, bar, area, histogram, box, violin, heatmap
- 3D scatter, 3D surface, 3D bar
- Error bars, curve fitting overlays, multi-series

**Publication-Ready**
- Export to PDF, SVG, EPS, PNG at vector quality
- Journal presets (Nature, Science, and more)
- Colorblind-safe palettes (Wong/Okabe-Ito)

**Infinite Canvas**
- Arrange multiple plots freely like Figma
- Drag-and-drop CSV import
- Multi-panel figure layouts for papers

## MCP Setup

Connect Graphoris to Claude Code with one command:

```bash
claude mcp add graphoris -- /path/to/graphoris-mcp.sh
```

Or add to Claude Desktop's `claude_desktop_config.json`:

```json
{
  "mcpServers": {
    "graphoris": {
      "command": "/path/to/graphoris-mcp.sh"
    }
  }
}
```

Then just ask Claude:

```
"Plot this CSV as a scatter chart"
"Add error bars to the Y axis"
"Fit a Gaussian to the main peak"
```

Claude creates the chart inside Graphoris → you edit it with your mouse.

## Screenshots

<!-- Replace with actual screenshots -->
<!-- ![Canvas View](screenshots/canvas.png) -->
<!-- ![AI Analysis](screenshots/ai-analysis.png) -->
<!-- ![3D Plot](screenshots/3d-plot.png) -->

Visit [graphoris.space](https://graphoris.space) for demo videos and more screenshots.

## Download

Download the latest release from the [Releases page](https://github.com/ymkindhearted/graphoris-releases/releases/latest).

**Requirements:**
- macOS 13 (Ventura) or later
- Apple Silicon or Intel Mac

## Pricing

| | Free | Entry ($4.99/mo) |
|---|---|---|
| All chart types | ✅ | ✅ |
| Metal GPU rendering | ✅ | ✅ |
| MCP server | ✅ | ✅ |
| Publication export | ✅ | ✅ |
| Built-in AI (GRAPO) | Limited | Claude Sonnet |
| | | 7-day free trial |

The app is fully functional for free. The Entry subscription unlocks the built-in AI assistant powered by Claude Sonnet.

## Feedback & Community

This is the first release — bugs are expected! Your feedback helps make Graphoris better.

- 🐛 [Report a bug](https://github.com/ymkindhearted/graphoris-releases/issues/new?template=bug_report.md)
- 💡 [Request a feature](https://github.com/ymkindhearted/graphoris-releases/issues/new?template=feature_request.md)
- 💬 [Join Discord](https://discord.gg/m22VDa4ZSs) for discussion and support
- 🗳️ [Discussions](https://github.com/ymkindhearted/graphoris-releases/discussions) for Q&A and ideas

## Comparison

| | Graphoris | OriginPro | GraphPad Prism | R/ggplot2 | LabPlot |
|---|---|---|---|---|---|
| macOS native | ✅ | ❌ | ✅ | N/A | ❌ (Qt) |
| GPU acceleration | Metal | ❌ | ❌ | ❌ | ❌ |
| AI integration | MCP + built-in | ❌ | ❌ | ❌ | ❌ |
| Editable AI plots | ✅ | N/A | N/A | ❌ | N/A |
| Free tier | ✅ | ❌ ($1,070/yr) | ❌ ($350/yr) | ✅ | ✅ |
| GUI editing | ✅ | ✅ | ✅ | ❌ (code) | ✅ |
| Infinite canvas | ✅ | ❌ | ❌ | N/A | ❌ |

## Tech Stack

- **Language:** Swift / SwiftUI / AppKit
- **Rendering:** Metal GPU (5K+ points), Core Graphics (< 5K points)
- **AI:** Claude Sonnet (built-in), Gemini Flash (free tier), MCP protocol
- **Backend:** Supabase (auth, AI proxy, credit tracking)
- **Updates:** Sparkle framework

## Star History

If you find Graphoris useful, a ⭐ helps others discover it!

---

<p align="center">
  <a href="https://graphoris.space">graphoris.space</a> · Made with ❤️ and Claude Code
</p>
