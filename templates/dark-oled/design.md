---
version: 1.0
name: Dark OLED
renderer: feishu-svg-whiteboard
description: >
  A true-dark system for OLED displays. Deep black canvas with near-black panels, illuminated by a single electric accent (cyan or amber) that glows against the void. Text is cool grey-white; borders are subtle dark-grey. Minimal, futuristic, and easy on the eyes in low light. Good for night-mode apps, coding platforms, and sci-fi-flavored technical explainers.

# ── COLOR ────────────────────────────────────────────────────
colors:
  canvas:   "#000000"   # true black — OLED off
  surface:  "#0D1117"   # near-black panel — barely raised
  elevated: "#161B22"   # slightly lighter panel — card fill
  ink:      "#C9D1D9"   # cool grey-white body text
  ink-dim:  "#8B949E"   # subdued secondary text
  accent:   "#58A6FF"   # electric blue — the ONE light in the dark
  accent2:  "#F0883E"   # warm amber — alternative accent, never with blue
  border:   "#30363D"   # subtle dark border
  # ONE accent per scene (blue OR amber, never both). Text stays in the grey range.
  # No pure white — it's too harsh on OLED.

# ── DEPTH ────────────────────────────────────────────────────
# Subtle elevation through panel levels (canvas → surface → elevated), not shadows.

# ── STROKE & CORNERS ─────────────────────────────────────────
stroke:
  structural: "1.5px solid #30363D"  # subtle dark borders
  rule:       "1px solid #21262D"
  radius: 8                            # softly squared — modern and precise
---

# Dark OLED — Feishu SVG Whiteboard Design System

A true-dark OLED-optimized system: deep black canvas, subtle grey elevation levels, and one electric blue accent that glows against the void. Minimal and futuristic.

## Color

Six solids in the dark range. **Canvas** (`#000000`) is true black. **Surface** (`#0D1117`) and **elevated** (`#161B22`) create subtle depth through panel levels. **Ink** (`#C9D1D9`) is cool grey-white text; **ink-dim** (`#8B949E`) is secondary. **Accent** (`#58A6FF`) is electric blue — the only color; alternatively **accent2** (`#F0883E`) warm amber. Never both. **Border** (`#30363D`) is subtle.

One accent per scene. No pure white — too harsh on OLED.

## Rules

This template is the **palette + mood** only. Every medium constraint (native shapes, opacity ignored, the text-color export caveat, no gradients/filters/shadows, reflow) and the build/verify workflow live in **[`../../RULES.md`](../../RULES.md)** — read it before building.
