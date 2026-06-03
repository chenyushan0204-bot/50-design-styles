---
version: 1.0
name: Vintage Analog
renderer: feishu-svg-whiteboard
description: >
  A warm film-photography nostalgic system: faded Kodachrome tones — warm ochre, muted teal, dusty rose, and cream — on a slightly yellowed paper ground. Soft, desaturated colors that feel sun-faded and time-worn. Borders are thin and warm; corners softly rounded. Feels like a 1970s photo album or a vinyl record sleeve. Good for photography portfolios, music/vinyl brands, vintage fashion, and nostalgia marketing boards.

# ── COLOR ────────────────────────────────────────────────────
colors:
  canvas:   "#F8F0E0"   # yellowed paper — time-worn warm white
  ochre:    "#D4A574"   # warm golden ochre — primary accent
  teal:     "#5B8A7A"   # muted vintage teal — secondary
  rose:     "#D4A0A0"   # dusty rose — tertiary accent
  cream:    "#F5E6C8"   # warm cream — panel fill
  ink:      "#3B3024"   # warm brown-black text
  ink-dim:  "#8B7B6A"   # faded secondary text
  rule:     "#D8C8B0"   # warm hairline
  # 2–3 vintage accents per scene. Colors are desaturated — nothing vivid.
  # All fills have a warm undertone. The palette is "sun-bleached."

# ── DEPTH ────────────────────────────────────────────────────
# FLAT — film is a 2D surface. No shadows. Depth through color warmth.

# ── STROKE & CORNERS ─────────────────────────────────────────
stroke:
  structural: "1.5px solid #D4A574"  # warm golden border
  rule:       "1px solid #D8C8B0"
  radius: 6                            # softly rounded — vintage photo corners
---

# Vintage Analog — Feishu SVG Whiteboard Design System

A sun-faded Kodachrome nostalgia system: warm ochre, muted teal, dusty rose on yellowed paper. Everything feels like a 1970s photo album — soft, warm, time-worn.

## Color

Eight solids in a faded film palette. **Canvas** (`#F8F0E0`) is yellowed paper. Three vintage accents: **ochre** (`#D4A574`), **teal** (`#5B8A7A`), **rose** (`#D4A0A0`). Use 2–3 per scene. **Cream** (`#F5E6C8`) is panel fill. **Ink** (`#3B3024`) is warm brown-black. All colors are desaturated — nothing vivid. The palette is "sun-bleached."

## Rules

This template is the **palette + mood** only. Every medium constraint (native shapes, opacity ignored, the text-color export caveat, no gradients/filters/shadows, reflow) and the build/verify workflow live in **[`../../RULES.md`](../../RULES.md)** — read it before building.
