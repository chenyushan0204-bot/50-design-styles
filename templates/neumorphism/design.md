---
version: 1.0
name: Neumorphism
renderer: feishu-svg-whiteboard
description: >
  A soft, convex UI aesthetic — light-source from top-left creates embossed/debossed panels on a pale grey ground. Monochromatic with subtle depth from hard offset shadows (no blur — the board renders them as solid offset shapes). All corners generously rounded (rx ≥ 16). Colors stay within a tight grey/lavender range. Good for calm explainers, wellness-themed boards, and any diagram that should feel gentle and modern.

# ── COLOR ────────────────────────────────────────────────────
colors:
  canvas:   "#E8ECF1"   # pale grey-lavender ground — the "light source" reference
  panel:    "#EEF1F5"   # raised card fill — slightly lighter than canvas
  shadow:   "#C8D0D8"   # offset-shadow solid — darker, reads as depth
  ink:      "#3B4252"   # body text — soft dark slate, not pure black
  accent:   "#7B9CB5"   # muted steel blue — key numerals, header accents
  # Monochromatic range only. No saturated hues. All fills within 2-3 stops of canvas.

# ── DEPTH ────────────────────────────────────────────────────
# Hard offset shadows required — duplicate the shape in shadow color, offset 6–8px right+down.
# Shadow must match the element's shape exactly (same rx, same dimensions) and sit behind it.
# FLAT is also acceptable for small labels; use depth only on major cards.

# ── STROKE & CORNERS ─────────────────────────────────────────
stroke:
  structural: none       # neumorphism relies on shadow for edge, not borders
  rule:       "1px solid #C8D0D8"
  radius: 16             # generously rounded — the neumorphic signature
---

# Neumorphism — Feishu SVG Whiteboard Design System

A soft-convex monochromatic system: pale grey-lavender ground with embossed cards, hard offset shadows (solid duplicates, never blur), and generously rounded corners. Feels calm, modern, and touchable.

## Color

Three greys and one accent. **Canvas** (`#E8ECF1`) is the ground. **Panel** (`#EEF1F5`) is the raised surface — slightly lighter, creating the convex illusion. **Shadow** (`#C8D0D8`) is the solid offset-shape color. **Ink** (`#3B4252`) is soft dark slate for all text. **Accent** (`#7B9CB5`) is a muted steel blue, used sparingly for numerals and header bands.

Stay within 2–3 stops of canvas. No saturated hues ever.

## Rules

This template is the **palette + mood** only. Every medium constraint (native shapes, opacity ignored, the text-color export caveat, no gradients/filters/shadows, reflow) and the build/verify workflow live in **[`../../RULES.md`](../../RULES.md)** — read it before building.
