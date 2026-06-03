---
version: 1.0
name: E-Ink Paper
renderer: feishu-svg-whiteboard
description: >
  A paper-like monochrome system that mimics the calm, matte surface of an e-reader. Warm off-white canvas with charcoal-grey text — no pure black, no pure white, no color. The entire palette stays within 3–4 stops of warm grey. Borders are thin and quiet. Feels like a Kindle screen or a letterpress print. Good for reading apps, digital newspapers, minimal journals, and distraction-free explainers.

# ── COLOR ────────────────────────────────────────────────────
colors:
  canvas:   "#F5F0E8"   # warm paper — like an aged paperback
  panel:    "#EDE8E0"   # slightly darker paper panel
  ink:      "#3B362F"   # charcoal text — never pure black
  ink-dim:  "#8B857A"   # muted secondary text
  ink-light: "#BFB8AD"   # faint text / rules — barely there
  rule:     "#D8D2C8"   # subtle warm divider
  # NO pure black and NO pure white. Everything in the warm-grey range.
  # Type is the only hierarchy tool — size, weight, spacing. No color accents.

# ── DEPTH ────────────────────────────────────────────────────
# FLAT — e-ink has no depth. The paper surface is everything.

# ── STROKE & CORNERS ─────────────────────────────────────────
stroke:
  structural: "1px solid #D8D2C8"   # subtle paper-edge border
  rule:       "1px solid #E0DAD0"
  radius: 2                            # nearly sharp — book-page precision
---

# E-Ink Paper — Feishu SVG Whiteboard Design System

A monochrome e-reader surface: warm paper tones, charcoal text, zero color. The entire palette lives within 4 stops of warm grey. Calm, quiet, and distraction-free.

## Color

Six solids — all warm grey. **Canvas** (`#F5F0E8`) is warm paper. **Panel** (`#EDE8E0`) is slightly darker. **Ink** (`#3B362F`) is charcoal — never pure black. **Ink-dim** (`#8B857A`) and **ink-light** (`#BFB8AD`) are diminishing greys. **Rule** (`#D8D2C8`) is subtle.

No pure black, no pure white, no color accents ever. Type hierarchy does all the work.

## Rules

This template is the **palette + mood** only. Every medium constraint (native shapes, opacity ignored, the text-color export caveat, no gradients/filters/shadows, reflow) and the build/verify workflow live in **[`../../RULES.md`](../../RULES.md)** — read it before building.
