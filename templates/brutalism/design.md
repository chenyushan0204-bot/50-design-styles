---
version: 1.0
name: Brutalism
renderer: feishu-svg-whiteboard
description: >
  Raw, unpolished, stark. A deliberately "ugly" anti-design system: pure primaries (red, blue, yellow) against bare white, with heavy black borders, default-looking text, and asymmetric blocks. No rounded corners, no subtlety, no decoration. Type is bold and oversized or plain and small — no middle ground. Good for artistic portfolios, counter-culture brands, and any board that wants to feel rebellious and un-designed.

# ── COLOR ────────────────────────────────────────────────────
colors:
  canvas:   "#FFFFFF"   # bare white — no tint, no warmth
  ink:      "#000000"   # pure black — all text, all borders
  red:      "#FF0000"   # primary accent — big blocks, loud headers
  blue:     "#0000FF"   # secondary accent — big blocks, loud headers
  yellow:   "#FFFF00"   # tertiary accent — highlight blocks
  # Pure primaries only. No pastels, no tints. 2 accents max per scene.
  # Black text on white/red/yellow; white text on blue.

# ── DEPTH ────────────────────────────────────────────────────
# Absolutely FLAT — no shadows, no depth tricks. The visual tension IS the design.

# ── STROKE & CORNERS ─────────────────────────────────────────
stroke:
  structural: "4px solid #000000"  # heavy black borders on everything
  rule:       "3px solid #000000"
  radius: 0                         # razor-sharp — no rounding ever
---

# Brutalism — Feishu SVG Whiteboard Design System

Raw anti-design: pure primaries, heavy black borders, zero curves, zero shadows. It looks like a protest poster — deliberately "broken" and confrontational.

## Color

Five colors, used loud. **Canvas** (`#FFFFFF`) is bare white. **Ink** (`#000000`) is all borders and body text. Three pure primaries never used together: **red** (`#FF0000`), **blue** (`#0000FF`), **yellow** (`#FFFF00`) — max 2 per scene. Black text on white/red/yellow; white text on blue.

## Rules

This template is the **palette + mood** only. Every medium constraint (native shapes, opacity ignored, the text-color export caveat, no gradients/filters/shadows, reflow) and the build/verify workflow live in **[`../../RULES.md`](../../RULES.md)** — read it before building.
