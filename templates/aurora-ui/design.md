---
version: 1.0
name: Aurora UI
renderer: feishu-svg-whiteboard
description: >
  A luminous gradient-inspired system — smooth color transitions are simulated with abutting horizontal bands of jewel tones: deep blue, violet, magenta, and cyan. Cards are semi-transparent white panels floating on the aurora backdrop. Type is dark on panels, white on dark bands. Feels atmospheric, premium, and modern. Good for creative SaaS, branding boards, music platforms, and hero-section explainers.

# ── COLOR ────────────────────────────────────────────────────
colors:
  canvas:   "#0A0E27"   # deep night blue ground
  band1:    "#1A237E"   # deep indigo aurora band
  band2:    "#4A148C"   # rich violet aurora band
  band3:    "#880E4F"   # deep magenta aurora band
  band4:    "#006064"   # dark cyan aurora band
  band5:    "#004D40"   # teal aurora band
  panel:    "#F8F6FF"   # near-white card on aurora
  ink:      "#0F0A2E"   # deep indigo text
  accent:   "#7C4DFF"   # vivid violet — numerals and badges
  # 3–5 aurora bands per scene, horizontal. Panels float on top.
  # Light text only on the darkest bands (band1–band3).

# ── DEPTH ────────────────────────────────────────────────────
# Depth = aurora bands create the backdrop; white panels float above. No shadows on panels.

# ── STROKE & CORNERS ─────────────────────────────────────────
stroke:
  structural: "1.5px solid #E0DCF0"  # thin panel edge
  rule:       "1px solid #D0CCE8"
  radius: 10                           # softly rounded panels
---

# Aurora UI — Feishu SVG Whiteboard Design System

A luminous aurora-borealis system: deep jewel-tone bands (indigo → violet → magenta → teal) create a glowing backdrop, with near-white content panels floating on top. Atmospheric and premium.

## Color

Seven solids. **Canvas** (`#0A0E27`) is deep night blue. Five aurora bands: **indigo** (`#1A237E`), **violet** (`#4A148C`), **magenta** (`#880E4F`), **cyan** (`#006064`), **teal** (`#004D40`). Use 3–5 bands. **Panel** (`#F8F6FF`) is the content carrier. **Ink** (`#0F0A2E`) is deep indigo text. **Accent** (`#7C4DFF`) is vivid violet for numerals.

Light text only on the darkest bands.

## Rules

This template is the **palette + mood** only. Every medium constraint (native shapes, opacity ignored, the text-color export caveat, no gradients/filters/shadows, reflow) and the build/verify workflow live in **[`../../RULES.md`](../../RULES.md)** — read it before building.
