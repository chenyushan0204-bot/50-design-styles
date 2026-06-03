---
version: 1.0
name: Bento Grid
renderer: feishu-svg-whiteboard
description: >
  An Apple-inspired modular grid system: asymmetric rounded cards of varying sizes organized in a clean, airy layout on a soft grey ground. Cards are white with subtle grey borders and generous padding. Type is clean and hierarchical — large display numerals in key cards, restrained body text elsewhere. No shadows, no loud colors — the grid does the talking. Good for dashboards, product feature pages, personal sites, and marketing summaries.

# ── COLOR ────────────────────────────────────────────────────
colors:
  canvas:   "#F2F2F7"   # soft grey ground — Apple-style
  card:     "#FFFFFF"   # pure white card fill
  ink:      "#1D1D1F"   # near-black — Apple-style dark text
  ink-dim:  "#86868B"   # secondary grey text
  accent:   "#0071E3"   # Apple blue — sparse, only for key numerals and links
  accent2:  "#E85D2C"   # warm orange — alternative accent
  border:   "#E5E5EA"   # subtle card border
  # ONE accent per scene (blue OR orange). Cards have generous padding.
  # Grid is asymmetric — cards of different sizes (1x, 2x width, 2x height).

# ── DEPTH ────────────────────────────────────────────────────
# FLAT — no shadows. Depth = the asymmetric grid itself and size contrast between cards.

# ── STROKE & CORNERS ─────────────────────────────────────────
stroke:
  structural: "1px solid #E5E5EA"  # whisper-thin card border
  rule:       "1px solid #E5E5EA"
  radius: 16                          # generously rounded — the bento signature
---

# Bento Grid — Feishu SVG Whiteboard Design System

An Apple-style modular grid: white rounded cards of varying sizes on a soft grey ground, organized asymmetrically. Clean, airy, and hierarchical — the grid itself is the design.

## Color

Six solids. **Canvas** (`#F2F2F7`) is soft grey. **Card** (`#FFFFFF`) is pure white. **Ink** (`#1D1D1F`) is near-black; **ink-dim** (`#86868B`) is secondary grey. **Accent** (`#0071E3` blue or `#E85D2C` orange) — one per scene, only for key numerals. **Border** (`#E5E5EA`) is whisper-thin.

## Rules

This template is the **palette + mood** only. Every medium constraint (native shapes, opacity ignored, the text-color export caveat, no gradients/filters/shadows, reflow) and the build/verify workflow live in **[`../../RULES.md`](../../RULES.md)** — read it before building.
