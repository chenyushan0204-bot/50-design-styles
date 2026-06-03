---
version: 1.0
name: Vaporwave
renderer: feishu-svg-whiteboard
description: >
  A nostalgic 80s/90s internet dreamscape: hot pink, neon cyan, mint green, and deep purple on a dark void. Sunset-gradient bands (pink → orange → yellow, simulated with abutting color blocks), chrome/silver accents, and a glitch-inspired aesthetic. Everything feels like a half-remembered GeoCities page dipped in neon. Good for music platforms, gaming, creative portfolios, and entertainment boards.

# ── COLOR ────────────────────────────────────────────────────
colors:
  canvas:   "#0D0221"   # deep void purple-black
  pink:     "#FF71CE"   # vaporwave hot pink
  cyan:     "#01CDFE"   # neon cyan
  mint:     "#05FFA1"   # electric mint
  purple:   "#B967FF"   # synth purple
  sunset1:  "#FF71CE"   # sunset gradient start — pink
  sunset2:  "#FF9671"   # sunset mid — coral
  sunset3:  "#FFCE5C"   # sunset end — gold
  panel:    "#1A1030"   # dark purple panel
  ink:      "#E8E0FF"   # pale lavender text
  silver:   "#C0C0C0"   # chrome accent
  # 3–4 accents per scene. Sunset bands are horizontal blocks.
  # Pale text on dark panels; dark text only on sunset bands.

# ── DEPTH ────────────────────────────────────────────────────
# FLAT — the vaporwave depth is in the color gradients (simulated as bands). No shadows.

# ── STROKE & CORNERS ─────────────────────────────────────────
stroke:
  structural: "1.5px solid #C0C0C0"  # chrome border
  rule:       "1px solid #3A2060"
  radius: 8                            # slightly rounded — retro-tech feel
---

# Vaporwave — Feishu SVG Whiteboard Design System

A nostalgic synthwave dreamscape: hot pink, neon cyan, and mint green on deep purple-black, with chrome accents and sunset-gradient bands. Half-remembered internet, dipped in neon.

## Color

Ten solids in full vaporwave. **Canvas** (`#0D0221`) is deep void. Five accents: **pink** (`#FF71CE`), **cyan** (`#01CDFE`), **mint** (`#05FFA1`), **purple** (`#B967FF`), **silver** (`#C0C0C0`). Three sunset bands: pink → coral (`#FF9671`) → gold (`#FFCE5C`). Use 3–4 accents. **Ink** (`#E8E0FF`) is pale lavender.

## Rules

This template is the **palette + mood** only. Every medium constraint (native shapes, opacity ignored, the text-color export caveat, no gradients/filters/shadows, reflow) and the build/verify workflow live in **[`../../RULES.md`](../../RULES.md)** — read it before building.
