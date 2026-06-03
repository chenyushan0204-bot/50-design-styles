---
version: 1.0
name: Y2K Aesthetic
renderer: feishu-svg-whiteboard
description: >
  A bubblegum cyber-pop throwback to 2000s internet aesthetics: hot pink, chrome silver, cyan, and iridescent purple on a glossy white ground. Metallic greys and shiny gradients (simulated with flush color bands). Rounded everything, with a slight "tech-optimism" vibe. Good for fashion brands, music platforms, Gen-Z nostalgia marketing, and entertainment boards.

# ── COLOR ────────────────────────────────────────────────────
colors:
  canvas:   "#FFFAFF"   # glossy near-white with pink undertone
  pink:     "#FF69B4"   # hot bubblegum pink — hero color
  cyan:     "#00FFFF"   # electric cyan — secondary
  purple:   "#BF5FFF"   # iridescent purple — tertiary
  silver:   "#C0C0C0"   # chrome silver — metallic panel
  silver2:  "#E8E8E8"   # light silver — alternate panel
  ink:      "#1A0033"   # deep purple-black text
  white:    "#FFFFFF"   # glossy card fill
  # 3–4 accents per scene. Silver panels create the "chrome" feel.
  # Pink and cyan are the stars; purple is support.

# ── DEPTH ────────────────────────────────────────────────────
# FLAT — the Y2K aesthetic is deliberately 2D and graphic. No shadows.

# ── STROKE & CORNERS ─────────────────────────────────────────
stroke:
  structural: "2px solid #C0C0C0"  # chrome silver border
  rule:       "1.5px solid #E8E8E8"
  radius: 14                          # bubbly rounded — the Y2K signature
---

# Y2K Aesthetic — Feishu SVG Whiteboard Design System

A 2000s bubblegum cyber-pop throwback: hot pink, chrome silver, and iridescent purple on glossy white. Bubbly, metallic, and unapologetically nostalgic.

## Color

Eight solids in a candy-chrome palette. **Canvas** (`#FFFAFF`) is glossy near-white. Four accents: **pink** (`#FF69B4`), **cyan** (`#00FFFF`), **purple** (`#BF5FFF`), and **silver** (`#C0C0C0`). Use 3–4 per scene. **Ink** (`#1A0033`) is deep purple-black. Pink and cyan lead; purple and silver support.

## Rules

This template is the **palette + mood** only. Every medium constraint (native shapes, opacity ignored, the text-color export caveat, no gradients/filters/shadows, reflow) and the build/verify workflow live in **[`../../RULES.md`](../../RULES.md)** — read it before building.
