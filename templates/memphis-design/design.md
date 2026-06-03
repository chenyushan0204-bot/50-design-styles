---
version: 1.0
name: Memphis Design
renderer: feishu-svg-whiteboard
description: >
  An 80s postmodern explosion: hot pink, electric yellow, teal, and purple geometric shapes colliding on a white ground. Squiggles (rendered as thin rect lines), triangles (simple polygons), bold patterns of dots and stripes, and clashing colors that somehow harmonize. Everything feels like an 80s MTV ident. Good for creative agencies, music sites, youth brands, and event promotion boards.

# ── COLOR ────────────────────────────────────────────────────
colors:
  canvas:   "#FFFAF8"   # warm white ground
  pink:     "#FF71CE"   # hot memphis pink
  yellow:   "#FFCE5C"   # electric yellow
  teal:     "#86CCCA"   # memphis teal
  purple:   "#B967FF"   # vivid purple
  red:      "#FF6B6B"   # punchy red
  ink:      "#1A1A2E"   # near-black
  # All 4–5 accents can appear in one scene — Memphis is maximalist.
  # Geometric patterns: dot grids (small circles), stripes (thin rects), triangles.

# ── DEPTH ────────────────────────────────────────────────────
# Absolutely FLAT — 2D graphic poster style. Color clash IS the depth.

# ── STROKE & CORNERS ─────────────────────────────────────────
stroke:
  structural: "2.5px solid #1A1A2E"  # bold black outlines on shapes
  rule:       "2px solid #1A1A2E"
  radius: 0                            # sharp geometric — the 80s way
---

# Memphis Design — Feishu SVG Whiteboard Design System

An 80s postmodern geometric explosion: hot pink, electric yellow, teal, and purple shapes — dots, stripes, squiggles, triangles — colliding in joyful chaos on white. Maximalist and unapologetic.

## Color

Seven solids in full Memphis mode. **Canvas** (`#FFFAF8`) is warm white. Five accents: **pink** (`#FF71CE`), **yellow** (`#FFCE5C`), **teal** (`#86CCCA`), **purple** (`#B967FF`), **red** (`#FF6B6B`). All can appear in one scene — Memphis is maximalist. **Ink** (`#1A1A2E`) for bold outlines.

## Rules

This template is the **palette + mood** only. Every medium constraint (native shapes, opacity ignored, the text-color export caveat, no gradients/filters/shadows, reflow) and the build/verify workflow live in **[`../../RULES.md`](../../RULES.md)** — read it before building.
