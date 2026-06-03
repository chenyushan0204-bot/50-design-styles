---
version: 1.0
name: Cyberpunk UI
renderer: feishu-svg-whiteboard
description: >
  A neon-noir terminal aesthetic: acid green and electric magenta against true black. Thin phosphor-like lines, HUD-style brackets, and data-dense panels. Type is monospace-flavored (small, all-caps labels). Feels like a hacker terminal meets Blade Runner. Good for gaming platforms, crypto/Web3 apps, developer tools, and sci-fi explainers.

# ── COLOR ────────────────────────────────────────────────────
colors:
  canvas:   "#0D0D0D"   # true near-black — the void
  panel:    "#141414"   # slightly raised dark panel
  neon-green:  "#00FF41"   # matrix green — primary accent
  neon-magenta: "#FF00FF"  # electric magenta — secondary accent
  neon-cyan:    "#00FFFF"  # cyan — tertiary accent
  ink:      "#E0E0E0"   # pale grey text
  ink-dim:  "#666666"   # dim secondary
  border:   "#1F1F1F"   # subtle panel border
  hud-line: "#00FF41"   # thin phosphor lines
  # 2 neons per scene max. Green is the default; magenta for highlights.
  # Thin horizontal rules ("scanlines") and bracket decorations.

# ── DEPTH ────────────────────────────────────────────────────
# FLAT — depth = neon lines cutting through the dark. No shadows.

# ── STROKE & CORNERS ─────────────────────────────────────────
stroke:
  structural: "1px solid #00FF41"   # thin phosphor border
  rule:       "1px solid #1F1F1F"
  radius: 0                           # razor-sharp — terminals aren't rounded
---

# Cyberpunk UI — Feishu SVG Whiteboard Design System

A neon-noir terminal: acid green and electric magenta on true black. HUD brackets, phosphor lines, data-dense panels. The future is dark and glowing.

## Color

Seven solids in a hacker palette. **Canvas** (`#0D0D0D`) is the void. **Panel** (`#141414`) is slightly raised. Three neons: **green** (`#00FF41`), **magenta** (`#FF00FF`), **cyan** (`#00FFFF`). Use 2 max per scene; green leads. **Ink** (`#E0E0E0`) is pale grey; **ink-dim** (`#666666`) is dim. **Hud-line** (`#00FF41`) for thin phosphor rules.

## Rules

This template is the **palette + mood** only. Every medium constraint (native shapes, opacity ignored, the text-color export caveat, no gradients/filters/shadows, reflow) and the build/verify workflow live in **[`../../RULES.md`](../../RULES.md)** — read it before building.
