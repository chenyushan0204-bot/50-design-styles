---
version: 1.0
name: Organic Biophilic
renderer: feishu-svg-whiteboard
description: >
  A warm, nature-inspired system: moss green, bark brown, sky blue, and warm cream. Shapes are rounded and flowing — circles and rounded rectangles dominate. No sharp corners, no harsh contrasts. Feels calm, grounded, and restorative. Good for wellness apps, sustainability brands, eco products, and meditation/health explainers.

# ── COLOR ────────────────────────────────────────────────────
colors:
  canvas:   "#F5F0E8"   # warm cream — like unbleached paper
  moss:     "#4A7C59"   # deep moss green — primary accent
  leaf:     "#7BA05B"   # fresh leaf green — secondary accent
  bark:     "#8B6914"   # warm bark brown — tertiary accent
  sky:      "#87CEEB"   # soft sky blue — highlight
  panel:    "#FFFAF2"   # warm cream card
  ink:      "#2C2416"   # warm dark brown — all text
  # 2–3 nature accents per scene. Moss green is the anchor.
  # Dark ink on cream/panel; light cream text on moss/bark.

# ── DEPTH ────────────────────────────────────────────────────
# FLAT — organic depth through overlapping circles and varied panel sizes. No shadows.

# ── STROKE & CORNERS ─────────────────────────────────────────
stroke:
  structural: "2px solid #4A7C59"   # moss green border
  rule:       "1.5px solid #C4B89A" # subtle warm rule
  radius: 14                           # soft and rounded — organic feel
---

# Organic Biophilic — Feishu SVG Whiteboard Design System

A grounded nature system: moss green, fresh leaf, warm bark, and sky blue on warm cream. Soft rounded shapes, no sharp edges. Calm and restorative.

## Color

Seven solids from the forest floor. **Canvas** (`#F5F0E8`) is warm cream. Four nature tones: **moss** (`#4A7C59`), **leaf** (`#7BA05B`), **bark** (`#8B6914`), **sky** (`#87CEEB`). Use 2–3 per scene. **Panel** (`#FFFAF2`) is warm card fill. **Ink** (`#2C2416`) is warm dark brown.

## Rules

This template is the **palette + mood** only. Every medium constraint (native shapes, opacity ignored, the text-color export caveat, no gradients/filters/shadows, reflow) and the build/verify workflow live in **[`../../RULES.md`](../../RULES.md)** — read it before building.
