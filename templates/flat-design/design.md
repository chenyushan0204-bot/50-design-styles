---
version: 1.0
name: Flat Design
renderer: feishu-svg-whiteboard
description: >
  Pure 2D clarity — bold saturated fills, no shadows, no borders on cards, and crisp typography. The palette is a restrained but confident set of flat colors: teal, coral, navy, and warm gold on a clean white ground. Icon-heavy, typography-forward, modern and friendly. Good for web/mobile app explainers, startup MVP boards, dashboards, and any board that needs to read as clean and contemporary.

# ── COLOR ────────────────────────────────────────────────────
colors:
  canvas:   "#FFFFFF"   # clean white ground
  panel:    "#F5F7FA"   # barely-there grey panel
  ink:      "#1C2333"   # dark navy — all text
  teal:     "#26A69A"   # flat teal — primary accent
  coral:    "#EF5350"   # flat coral — secondary accent
  navy:     "#3F51B5"   # flat indigo — tertiary accent
  gold:     "#FFB300"   # warm gold — highlight accent
  # 2–3 accents per scene. All fills are solid and borderless.
  # Dark text on white/panel; white text on saturated accents.

# ── DEPTH ────────────────────────────────────────────────────
# Absolutely FLAT — no shadows, no borders on cards. Color blocks carry all the weight.

# ── STROKE & CORNERS ─────────────────────────────────────────
stroke:
  structural: none       # flat design has no card borders
  rule:       "1.5px solid #E0E4E8"  # subtle dividers
  radius: 6                # slightly rounded — friendly, not sharp
---

# Flat Design — Feishu SVG Whiteboard Design System

A clean 2D system: bold flat colors (teal, coral, navy, gold) on white, no shadows, no card borders. Crisp typography does the heavy lifting. Modern and friendly.

## Color

Six solids. **Canvas** (`#FFFFFF`) is clean white. **Panel** (`#F5F7FA`) is barely grey. **Ink** (`#1C2333`) is dark navy. Four flat accents: **teal** (`#26A69A`), **coral** (`#EF5350`), **navy** (`#3F51B5`), **gold** (`#FFB300`). Use 2–3 per scene. No borders on cards. Dark text on light; white text on saturated fills.

## Rules

This template is the **palette + mood** only. Every medium constraint (native shapes, opacity ignored, the text-color export caveat, no gradients/filters/shadows, reflow) and the build/verify workflow live in **[`../../RULES.md`](../../RULES.md)** — read it before building.
