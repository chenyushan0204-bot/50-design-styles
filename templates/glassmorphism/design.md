---
version: 1.0
name: Glassmorphism
renderer: feishu-svg-whiteboard
description: >
  A layered frosted-glass aesthetic built from translucent-looking solid fills on a vibrant gradient background (simulated with abutting color bands). Cards are semi-transparent white/light panels with thin light borders, floating above the colorful ground. Depth comes from overlapping panels and varied panel opacities (achieved with paler solid tints, never real opacity). Good for modern SaaS explainers, dashboards, and layered system maps.

# ── COLOR ────────────────────────────────────────────────────
colors:
  canvas:   "#1A0533"   # deep violet ground — anchors the vibrant backdrop
  backdrop1: "#3B1F8C"   # rich purple band
  backdrop2: "#6B3FA0"   # mid purple band
  backdrop3: "#C84B8A"   # magenta-pink band — warm punch
  backdrop4: "#F0985C"   # warm orange band — the sunset edge
  glass:    "#FDFBFF"   # "frosted glass" panel fill — near-white solid tint
  glass-alt: "#F2EDF8"   # slightly darker glass panel for depth variation
  ink:      "#1A1A2E"   # dark text on glass panels
  border:   "#E0D8F0"   # thin glass-edge border
  # Glass panels sit ON the backdrop, never directly on canvas.
  # 2–3 backdrop bands per scene; glass panels are the content carriers.

# ── DEPTH ────────────────────────────────────────────────────
# Layered depth — glass panels overlap backdrop bands and each other.
# FLAT within panels. No shadows — depth comes from the backdrop/glass contrast.

# ── STROKE & CORNERS ─────────────────────────────────────────
stroke:
  structural: "1.5px solid #E0D8F0"  # thin glass edge
  rule:       "1px solid #D8D0E8"
  radius: 12                           # softly rounded glass panels
---

# Glassmorphism — Feishu SVG Whiteboard Design System

A layered frosted-glass system: a vibrant purple-to-orange backdrop carries translucent white glass panels with thin light borders. Depth is spatial, not shadow-based.

## Color

The **canvas** (`#1A0533`) is deep violet. 3–4 backdrop bands create the vibrant ground: rich purple (`#3B1F8C`), mid purple (`#6B3FA0`), magenta-pink (`#C84B8A`), and warm orange (`#F0985C`). **Glass** panels (`#FDFBFF` and `#F2EDF8`) sit on top as content carriers. **Ink** (`#1A1A2E`) is dark text. **Border** (`#E0D8F0`) gives the glass edge.

Use 2–3 backdrop bands per scene. Glass panels never sit directly on canvas — always on a backdrop band.

## Rules

This template is the **palette + mood** only. Every medium constraint (native shapes, opacity ignored, the text-color export caveat, no gradients/filters/shadows, reflow) and the build/verify workflow live in **[`../../RULES.md`](../../RULES.md)** — read it before building.
