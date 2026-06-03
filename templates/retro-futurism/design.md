---
version: 1.0
name: Retro-Futurism
renderer: feishu-svg-whiteboard
description: >
  An 80s sci-fi VHS aesthetic: neon cyan, hot pink, and electric purple against a deep navy-black ground. Grid lines, angular blocks, and glitch-inspired offsets. Type is monospace-flavored (via spacing/caps). Everything feels like a synthwave album cover or a Blade Runner terminal. Good for gaming, entertainment, music platforms, and tech brand explainers.

# ── COLOR ────────────────────────────────────────────────────
colors:
  canvas:   "#0A0A1A"   # deep navy-black — the void
  grid:     "#1A1A3E"   # subtle grid line
  neon-cyan:   "#00E5FF"   # electric cyan — primary accent
  neon-pink:   "#FF2D95"   # hot pink — secondary accent
  neon-purple: "#B44CFF"   # electric purple — tertiary accent
  neon-amber:  "#FFB800"   # warm amber — highlight
  panel:    "#111130"   # near-black panel fill
  ink:      "#E8E8FF"   # pale blue-white text
  ink-dim:  "#8888AA"   # dim secondary text
  # 2–3 neon accents per scene. Cyan is the star; pink and purple support.
  # Grid backgrounds (thin horizontal lines) on the canvas.

# ── DEPTH ────────────────────────────────────────────────────
# Flat panels with neon borders. Depth = bright neon lines against the dark void.

# ── STROKE & CORNERS ─────────────────────────────────────────
stroke:
  structural: "2px solid #00E5FF"   # neon cyan borders
  rule:       "1px solid #1A1A3E"   # subtle grid lines
  radius: 0                           # sharp angular — retrowave is orthogonal
---

# Retro-Futurism — Feishu SVG Whiteboard Design System

An 80s synthwave terminal: neon cyan, hot pink, and electric purple against deep navy-black. Grid lines, sharp edges, and glowing borders. The future as imagined in 1985.

## Color

Eight solids in a neon-noir palette. **Canvas** (`#0A0A1A`) is the void. Four neons: **cyan** (`#00E5FF`), **pink** (`#FF2D95`), **purple** (`#B44CFF`), **amber** (`#FFB800`). Use 2–3 per scene; cyan leads. **Panel** (`#111130`) is near-black; **ink** (`#E8E8FF`) is pale blue-white. Grid lines in `#1A1A3E`.

## Rules

This template is the **palette + mood** only. Every medium constraint (native shapes, opacity ignored, the text-color export caveat, no gradients/filters/shadows, reflow) and the build/verify workflow live in **[`../../RULES.md`](../../RULES.md)** — read it before building.
