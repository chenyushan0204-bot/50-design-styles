---
version: 1.0
name: HUD Sci-Fi
renderer: feishu-svg-whiteboard
description: >
  A futuristic heads-up-display aesthetic: cyan, electric blue, and warning red on a transparent dark field. Thin wireframe lines, corner brackets, data-dense readouts, and a sparse, technical feel. Type is small, all-caps, and monospace-flavored (via letter-spacing). Everything feels like an Iron Man helmet display or a spacecraft dashboard. Good for sci-fi games, space tech, cybersecurity explainers, and immersive dashboards.

# ── COLOR ────────────────────────────────────────────────────
colors:
  canvas:   "#020617"   # deep void blue-black
  panel:    "#0F172A"   # slightly raised panel — transparent feel
  cyan:     "#00FFFF"   # electric cyan — primary HUD element
  blue:     "#38BDF8"   # sky blue — secondary data
  red:      "#FF3333"   # warning red — alerts and highlights
  amber:    "#F59E0B"   # caution amber — secondary indicator
  ink:      "#E2E8F0"   # pale blue-white text
  ink-dim:  "#64748B"   # dimmed secondary text
  hud-line: "#00FFFF"   # thin cyan wireframe lines
  # 2–3 HUD colors per scene. Cyan is the default; red = alert, amber = caution.
  # Corner brackets on panels: small L-shaped lines at card corners.

# ── DEPTH ────────────────────────────────────────────────────
# FLAT — HUD depth through wireframe density and bracket decorations. No shadows.

# ── STROKE & CORNERS ─────────────────────────────────────────
stroke:
  structural: "1px solid #00FFFF"    # thin cyan wireframe
  rule:       "1px solid #1E293B"
  radius: 2                            # nearly sharp — aerospace precision
---

# HUD Sci-Fi — Feishu SVG Whiteboard Design System

An Iron-Man HUD in the board medium: electric cyan wireframes, corner brackets, blue data readouts, and warning red dots on deep void blue-black. Technical, futuristic, sparse.

## Color

Nine solids in aerospace palette. **Canvas** (`#020617`) is deep void. **Panel** (`#0F172A`) is barely raised. Four HUD colors: **cyan** (`#00FFFF` primary), **blue** (`#38BDF8` data), **red** (`#FF3333` alert), **amber** (`#F59E0B` caution). Use 2–3 per scene. **Ink** (`#E2E8F0`) is pale blue-white.

Corner brackets (L-shaped lines) on card corners for the HUD feel.

## Rules

This template is the **palette + mood** only. Every medium constraint (native shapes, opacity ignored, the text-color export caveat, no gradients/filters/shadows, reflow) and the build/verify workflow live in **[`../../RULES.md`](../../RULES.md)** — read it before building.
