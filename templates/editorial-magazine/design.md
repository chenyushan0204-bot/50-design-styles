---
version: 1.0
name: Editorial Magazine
renderer: feishu-svg-whiteboard
description: >
  A print-inspired editorial grid system: asymmetric column layout, bold serif-flavored headlines (via weight and scale), pull-quote blocks, and confident use of black and white with one warm accent (burnt sienna). Generous margins, drop-cap numerals, and a clear typographic hierarchy. Feels like a Sunday magazine or a design annual. Good for news sites, blogs, long-form editorial content, and publishing explainers.

# ── COLOR ────────────────────────────────────────────────────
colors:
  canvas:   "#FCFAF7"   # warm newsprint off-white
  panel:    "#F7F4EF"   # sidebar/story panel
  ink:      "#111111"   # rich black — headlines and body
  accent:   "#C7512E"   # burnt sienna — section flags, drop caps, rules
  rule:     "#E0DBD2"   # column hairline
  quote-bg: "#F3EFE8"   # pull-quote background
  # ONE accent — burnt sienna. Used for section flags, big numerals, and horizontal rules.
  # Asymmetric columns (e.g. 2/3 + 1/3). Large headlines, generous margins.

# ── DEPTH ────────────────────────────────────────────────────
# FLAT — print is 2D. The grid and typography create structure.

# ── STROKE & CORNERS ─────────────────────────────────────────
stroke:
  structural: "1px solid #111111"    # column rules
  rule:       "1px solid #E0DBD2"
  radius: 0                            # sharp — editorial precision
---

# Editorial Magazine — Feishu SVG Whiteboard Design System

A print editorial system: warm newsprint, rich black ink, burnt sienna accent. Asymmetric columns, bold headlines, pull quotes. The Sunday magazine, on a whiteboard.

## Color

Five solids. **Canvas** (`#FCFAF7`) is warm newsprint. **Panel** (`#F7F4EF`) is a sidebar fill. **Ink** (`#111111`) is rich black. **Accent** (`#C7512E`) is burnt sienna — section flags, drop caps, rules. **Rule** (`#E0DBD2`) and **quote-bg** (`#F3EFE8`) support.

Asymmetric columns, large headlines, generous margins. One accent only.

## Rules

This template is the **palette + mood** only. Every medium constraint (native shapes, opacity ignored, the text-color export caveat, no gradients/filters/shadows, reflow) and the build/verify workflow live in **[`../../RULES.md`](../../RULES.md)** — read it before building.
