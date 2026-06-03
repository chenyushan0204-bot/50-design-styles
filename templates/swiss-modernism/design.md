---
version: 1.0
name: Swiss Modernism 2.0
renderer: feishu-svg-whiteboard
description: >
  A modernized Swiss/International Style with slightly warmer tones and a touch more flexibility. A warm off-white canvas carries black-ink typography structured by an asymmetric grid, with one confident forest-green accent for section markers and key numerals. Borders are thin and precise; corners are sharp. Feels like a contemporary museum catalogue — rational but not cold. Good for corporate sites, architecture, editorial boards, SaaS, and professional services.

# ── COLOR ────────────────────────────────────────────────────
colors:
  canvas:   "#FAF8F5"   # warm off-white — softer than pure white
  panel:    "#F5F2ED"   # slightly warmer panel
  ink:      "#1A1A1A"   # near-black — all text and structure
  accent:   "#1B5E3B"   # forest green — the single accent
  rule:     "#E0DCD5"   # warm hairline divider
  # ONE accent only — forest green. Used for section header bands, key numerals, and rules.
  # Asymmetric grid — columns are not equal width; the layout breathes.

# ── DEPTH ────────────────────────────────────────────────────
# FLAT — Swiss Modernism is about the grid, not depth. No shadows.

# ── STROKE & CORNERS ─────────────────────────────────────────
stroke:
  structural: "1.5px solid #1A1A1A"  # precise thin borders
  rule:       "1px solid #E0DCD5"
  radius: 0                            # sharp — Swiss is orthogonal
---

# Swiss Modernism 2.0 — Feishu SVG Whiteboard Design System

A warmer Swiss International Style: warm off-white canvas, black ink, asymmetric grid, one forest-green accent. Rational, refined, contemporary.

## Color

Four solids. **Canvas** (`#FAF8F5`) is warm off-white. **Panel** (`#F5F2ED`) is a slightly warmer card. **Ink** (`#1A1A1A`) is near-black for all text and structure. **Accent** (`#1B5E3B`) is forest green — the only accent, used for section headers and key numerals. **Rule** (`#E0DCD5`) is a warm hairline.

Asymmetric grid — columns breathe.

## Rules

This template is the **palette + mood** only. Every medium constraint (native shapes, opacity ignored, the text-color export caveat, no gradients/filters/shadows, reflow) and the build/verify workflow live in **[`../../RULES.md`](../../RULES.md)** — read it before building.
