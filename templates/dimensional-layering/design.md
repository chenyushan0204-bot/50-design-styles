---
version: 1.0
name: Dimensional Layering
renderer: feishu-svg-whiteboard
description: >
  A spatial z-index system: overlapping cards at different elevation levels, each with a hard offset shadow (solid dark duplicate). The palette is restrained — cool grey, slate blue, and white — so the depth illusion reads clearly. Cards cast shadows on cards beneath them. Feels like a material-design upgrade: tactile, organized, and deeply spatial. Good for dashboards, card layouts, modals, and layered system maps.

# ── COLOR ────────────────────────────────────────────────────
colors:
  canvas:   "#E8ECF2"   # cool grey ground
  card:     "#FFFFFF"   # white card — the top layer
  card-mid: "#F5F6F8"   # mid-layer card — slightly grey
  card-low: "#EBEDF0"   # lowest card — more grey
  shadow:   "#C0C6CE"   # offset shadow solid for white cards
  shadow2:  "#A8B0B8"   # darker shadow for deeper cards
  ink:      "#1A1D22"   # near-black text
  accent:   "#4361EE"   # vivid blue — sparse, for key numerals
  border:   "#DDE1E6"   # subtle card edge
  # 3 elevation levels. Shadow offset increases with elevation: 4px, 8px, 12px.
  # Cards overlap each other — layout is spatial, not flat-grid.

# ── DEPTH ────────────────────────────────────────────────────
# Hard offset shadows at 3 levels. Cards overlap — a card can cast shadow on the card below it.
# Shadow must match shape exactly. Higher cards = larger offset.

# ── STROKE & CORNERS ─────────────────────────────────────────
stroke:
  structural: "1px solid #DDE1E6"   # subtle card border
  rule:       "1px solid #E0E4EA"
  radius: 10                           # softly rounded — modern elevation
---

# Dimensional Layering — Feishu SVG Whiteboard Design System

A spatial z-index system: overlapping white/grey cards at 3 elevation levels, each with proportionate hard offset shadows. Cool, organized, and deeply tactile.

## Color

Eight solids. **Canvas** (`#E8ECF2`) is cool grey. Three card levels: **card** (`#FFFFFF`), **card-mid** (`#F5F6F8`), **card-low** (`#EBEDF0`). Two shadow solids: **shadow** (`#C0C6CE`) and **shadow2** (`#A8B0B8`). **Ink** (`#1A1D22`) is near-black. **Accent** (`#4361EE`) is vivid blue. **Border** (`#DDE1E6`) is subtle.

Cards overlap spatially; shadows cascade.

## Rules

This template is the **palette + mood** only. Every medium constraint (native shapes, opacity ignored, the text-color export caveat, no gradients/filters/shadows, reflow) and the build/verify workflow live in **[`../../RULES.md`](../../RULES.md)** — read it before building.
