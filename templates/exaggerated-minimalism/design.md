---
version: 1.0
name: Exaggerated Minimalism
renderer: feishu-svg-whiteboard
description: >
  Minimalism pushed to the extreme: oversized display typography, vast white space, and a single accent color used at most once. The canvas is pure white; text is black or the accent. Cards are absent or reduced to whisper-thin borders. Everything is about scale contrast — 72px headlines next to 14px body, 80% white space. Feels like a luxury fashion magazine. Good for architecture, fashion, luxury brands, and editorial explainers.

# ── COLOR ────────────────────────────────────────────────────
colors:
  canvas:   "#FFFFFF"   # pure white — the dominant element
  ink:      "#000000"   # pure black — all text
  accent:   "#C41E3A"   # single accent — crimson red, used ONCE per scene
  rule:     "#E0E0E0"   # whisper-thin hairline — barely visible
  # ONE accent only. It appears as a single element — one bar, one numeral, one rule.
  # Everything else is black on white. Vast white space is mandatory.

# ── DEPTH ────────────────────────────────────────────────────
# Absolutely FLAT. The void between elements IS the structural element.

# ── STROKE & CORNERS ─────────────────────────────────────────
stroke:
  structural: "1px solid #E0E0E0"  # barely visible
  rule:       "0.5px solid #E8E8E8"
  radius: 0                           # razor sharp — fashion minimalism is precise
---

# Exaggerated Minimalism — Feishu SVG Whiteboard Design System

Luxury minimalism: pure white, pure black, one crimson accent used once. Oversized type, vast white space. Nothing to hide behind — every element must earn its place.

## Color

Three solids. **Canvas** (`#FFFFFF`) is pure white — it is the dominant element. **Ink** (`#000000`) is all text. **Accent** (`#C41E3A`) is crimson red — used ONCE per scene as a single element (one bar, one numeral). **Rule** (`#E0E0E0`) is nearly invisible.

## Rules

This template is the **palette + mood** only. Every medium constraint (native shapes, opacity ignored, the text-color export caveat, no gradients/filters/shadows, reflow) and the build/verify workflow live in **[`../../RULES.md`](../../RULES.md)** — read it before building.
