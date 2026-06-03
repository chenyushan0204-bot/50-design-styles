---
version: 1.0
name: Nature Distilled
renderer: feishu-svg-whiteboard
description: >
  An earthy, warm minimalism extracted from natural materials: terracotta clay, warm sand, sun-baked soil, and unbleached linen. Colors are muted and grounding — the palette of handmade pottery and woven textiles. No synthetics, no neons. Shapes are softly rounded; the mood is calm and artisanal. Good for wellness brands, sustainable products, artisan goods, spa/beauty, and home decor boards.

# ── COLOR ────────────────────────────────────────────────────
colors:
  canvas:   "#FBF6F0"   # unbleached linen — warm natural ground
  panel:    "#F5EDE3"   # lighter clay panel
  terracotta: "#C67B5C"  # warm terracotta clay — primary accent
  sand:     "#D4C4A8"   # warm sand — secondary accent
  soil:     "#8B6B4A"   # deep soil brown — tertiary accent
  sage:     "#9BAF8A"   # muted sage green — botanical relief
  ink:      "#3B2F24"   # warm earth-black text
  ink-dim:  "#8B7B6A"   # muted secondary text
  rule:     "#D8CCC0"   # warm clay hairline
  # 2–3 earth accents per scene. Terracotta is the star; sand and sage support.
  # All fills are warm-toned. No cool greys, no pure black, no pure white.

# ── DEPTH ────────────────────────────────────────────────────
# FLAT — like a ceramic tile surface. Texture comes from color warmth, not shadows.

# ── STROKE & CORNERS ─────────────────────────────────────────
stroke:
  structural: "2px solid #C67B5C"    # terracotta border
  rule:       "1.5px solid #D8CCC0"
  radius: 8                            # softly rounded — hand-shaped pottery feel
---

# Nature Distilled — Feishu SVG Whiteboard Design System

An artisanal earth-palette system: warm terracotta, sun-baked sand, deep soil, and muted sage on unbleached linen. The colors of handmade pottery and woven textiles. Calm, grounded, warm.

## Color

Nine solids from the earth. **Canvas** (`#FBF6F0`) is unbleached linen. **Panel** (`#F5EDE3`) is lighter clay. Four earth tones: **terracotta** (`#C67B5C`), **sand** (`#D4C4A8`), **soil** (`#8B6B4A`), **sage** (`#9BAF8A`). Use 2–3 per scene; terracotta leads. **Ink** (`#3B2F24`) is warm earth-black.

No cool greys, no pure black, no pure white. Everything is warm.

## Rules

This template is the **palette + mood** only. Every medium constraint (native shapes, opacity ignored, the text-color export caveat, no gradients/filters/shadows, reflow) and the build/verify workflow live in **[`../../RULES.md`](../../RULES.md)** — read it before building.
