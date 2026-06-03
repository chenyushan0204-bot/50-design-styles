---
version: 1.0
name: Neubrutalism
renderer: feishu-svg-whiteboard
description: >
  A confident Gen-Z neo-brutalist system: bright yellow, coral red, and electric blue against clean white, all bound by heavy 4px black borders with hard 45° offset shadows (solid black duplicates). Bold rounded corners and chunky typography. Feels like Figma-meets-Notion — designed but deliberately raw. Good for startups, creative agencies, Gen-Z brands, and tech blogs.

# ── COLOR ────────────────────────────────────────────────────
colors:
  canvas:   "#FFFAF0"   # warm white ground
  ink:      "#000000"   # pure black — all borders, all text
  yellow:   "#FFEB3B"   # bright yellow — hero blocks
  coral:    "#FF5252"   # bold coral-red — accent blocks
  blue:     "#2196F3"   # electric blue — cool accent
  green:    "#00E676"   # acid green — punctuation
  shadow:   "#000000"   # solid black offset shadow (45° diagonal, 8px)
  # 2–3 accents per scene. Every major card gets a black border + black offset shadow.
  # Dark text on light fills; white text on black fills only.

# ── DEPTH ────────────────────────────────────────────────────
# Hard black offset shadows at 45° (translate 8px right, 8px down). Shadow must match shape exactly.
# Every major card has one. Small labels/chips can be flat.

# ── STROKE & CORNERS ─────────────────────────────────────────
stroke:
  structural: "4px solid #000000"   # chunky black borders — the neubrutalist signature
  rule:       "3px solid #000000"
  radius: 12                          # rounded but bold — friendly brutalism
---

# Neubrutalism — Feishu SVG Whiteboard Design System

A Gen-Z neo-brutalist system: bright primaries on warm white, chunky 4px black borders, and hard 45° black offset shadows. Bold, friendly, and unapologetically designed.

## Color

Seven solids. **Canvas** (`#FFFAF0`) is warm white. **Ink** (`#000000`) is everything structural. Four accents: **yellow** (`#FFEB3B`), **coral** (`#FF5252`), **blue** (`#2196F3`), **green** (`#00E676`). Use 2–3 per scene. **Shadow** (`#000000`) is the solid offset shadow, always 8px diagonal. Every major card gets border + shadow.

## Rules

This template is the **palette + mood** only. Every medium constraint (native shapes, opacity ignored, the text-color export caveat, no gradients/filters/shadows, reflow) and the build/verify workflow live in **[`../../RULES.md`](../../RULES.md)** — read it before building.
