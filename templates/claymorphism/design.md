---
version: 1.0
name: Claymorphism
renderer: feishu-svg-whiteboard
description: >
  A chunky, toy-like 3D aesthetic — soft pastel blocks with thick borders and double hard-offset shadows that create a puffy, extruded clay look. Colors stay in a candy-pastel range (blush, mint, lavender, butter). Corners are heavily rounded (rx ≥ 20). Everything feels squeezable and playful. Good for educational boards, children's content, onboarding flows, and casual team explainers.

# ── COLOR ────────────────────────────────────────────────────
colors:
  canvas:   "#FFF8F0"   # warm cream ground
  clay-blush: "#FDBCB4"  # soft pink clay — main card fill
  clay-mint: "#ADE8C8"   # fresh mint clay — accent card
  clay-lavender: "#D8D0F0"  # soft lavender clay — accent card
  clay-butter: "#F8E8A0"  # warm butter clay — highlight
  ink:      "#4A3B32"    # warm dark brown — all text and borders
  shadow1:  "#D8C8B8"    # first offset shadow — medium warm grey
  shadow2:  "#C0B0A0"    # second offset shadow — darker, deeper
  # 2–3 clay colors per scene. Double offset shadows (6px + 12px) on main cards.
  # Dark ink on pastel fills; never light text.

# ── DEPTH ────────────────────────────────────────────────────
# DOUBLE hard offset shadows on major cards (duplicate shape in shadow1 → offset 6px,
# then again in shadow2 → offset 12px). Both shadows match the element shape exactly.
# Small labels can be flat.

# ── STROKE & CORNERS ─────────────────────────────────────────
stroke:
  structural: "3.5px solid #4A3B32"   # chunky brown borders
  rule:       "2px solid #4A3B32"
  radius: 20                            # heavily rounded — the clay signature
---

# Claymorphism — Feishu SVG Whiteboard Design System

A chunky, squeezable clay system: soft pastel blocks, thick warm-brown borders, and double hard-offset shadows creating a puffy 3D look. Feels playful and toy-like.

## Color

Six solids in a candy-pastel range. **Canvas** (`#FFF8F0`) is warm cream. Four clay colors: **blush** (`#FDBCB4`), **mint** (`#ADE8C8`), **lavender** (`#D8D0F0`), **butter** (`#F8E8A0`) — use 2–3 per scene. **Ink** (`#4A3B32`) is warm dark brown for all text and borders. **Shadow1** (`#D8C8B8`) and **shadow2** (`#C0B0A0`) are the double offset-shadow colors.

Double shadows (6px + 12px) on major cards; small labels flat. Dark ink on pastels only.

## Rules

This template is the **palette + mood** only. Every medium constraint (native shapes, opacity ignored, the text-color export caveat, no gradients/filters/shadows, reflow) and the build/verify workflow live in **[`../../RULES.md`](../../RULES.md)** — read it before building.
