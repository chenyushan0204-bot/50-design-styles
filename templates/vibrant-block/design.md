---
version: 1.0
name: Vibrant Block
renderer: feishu-svg-whiteboard
description: >
  Energetic, bold, and playfully maximalist. A neon-bright system of large geometric color blocks — hot pink, electric cyan, acid green, and vivid orange — abutting flush on a dark or white ground. Heavy borders and oversized numerals. Everything feels like a music festival poster. Good for startups, creative agencies, gaming, and any board that needs to feel exciting and youthful.

# ── COLOR ────────────────────────────────────────────────────
colors:
  canvas:   "#FAFAFA"   # near-white ground — lets colors pop
  ink:      "#0D0D0D"   # near-black — all text
  pink:     "#FF1493"   # hot pink — hero blocks
  cyan:     "#00E5FF"   # electric cyan — accent blocks
  green:    "#39FF14"   # acid green — highlights
  orange:   "#FF6B00"   # vivid orange — warmth accent
  purple:   "#BF00FF"   # electric purple — depth accent
  # 3–4 accents per scene. Blocks abut flush — no gaps, or heavy black borders between them.

# ── DEPTH ────────────────────────────────────────────────────
# FLAT — color contrast IS the depth. Big blocks of different hues create figure-ground tension.

# ── STROKE & CORNERS ─────────────────────────────────────────
stroke:
  structural: "3px solid #0D0D0D"  # bold borders between blocks
  rule:       "2px solid #0D0D0D"
  radius: 0                          # sharp edges for maximum energy; 8px allowed on badges
---

# Vibrant Block — Feishu SVG Whiteboard Design System

A neon block-party system: hot pink, electric cyan, acid green, vivid orange — large geometric color blocks, bold borders, and oversized type on a near-white ground.

## Color

Six solids. **Canvas** (`#FAFAFA`) is near-white, the quiet stage. **Ink** (`#0D0D0D`) is all text and borders. Four neons: **pink** (`#FF1493`), **cyan** (`#00E5FF`), **green** (`#39FF14`), **orange** (`#FF6B00`), and **purple** (`#BF00FF`). Use 3–4 accents per scene. Blocks abut flush or with heavy borders between.

## Rules

This template is the **palette + mood** only. Every medium constraint (native shapes, opacity ignored, the text-color export caveat, no gradients/filters/shadows, reflow) and the build/verify workflow live in **[`../../RULES.md`](../../RULES.md)** — read it before building.
