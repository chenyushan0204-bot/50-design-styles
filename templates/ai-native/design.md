---
version: 1.0
name: AI-Native UI
renderer: feishu-svg-whiteboard
description: >
  A conversational, ambient AI interface aesthetic: soft indigo-violet gradients simulated with flush color bands, rounded pill shapes for "AI thinking" indicators, and generous white space. The palette is restrained — indigo, soft green, and warm grey on a clean white ground. Type is friendly and approachable. Feels like ChatGPT meets Siri — intelligent but warm. Good for AI product explainers, chatbot interfaces, and copilot-style boards.

# ── COLOR ────────────────────────────────────────────────────
colors:
  canvas:   "#FAFAFC"   # near-white with slight cool undertone
  panel:    "#FFFFFF"   # pure white card
  indigo:   "#6366F1"   # AI indigo — primary accent
  indigo-light: "#A5B4FC"  # soft indigo — secondary
  green:    "#10B981"   # AI green — success/positive indicator
  amber:    "#F59E0B"   # warm amber — thinking/processing
  ink:      "#1E1B2E"   # deep indigo-black text
  ink-dim:  "#8E8CA0"   # muted secondary text
  border:   "#E8E6F0"   # soft lavender border
  # Indigo is the AI brand color. Green and amber are functional indicators.
  # Generous padding; pill shapes (rx ≥ 24) for key elements.

# ── DEPTH ────────────────────────────────────────────────────
# FLAT with subtle layering — cards on canvas. No shadows. Depth = size and color hierarchy.

# ── STROKE & CORNERS ─────────────────────────────────────────
stroke:
  structural: "1.5px solid #E8E6F0"  # soft border
  rule:       "1px solid #F0EEF5"
  radius: 16                           # pill-friendly — soft and conversational
---

# AI-Native UI — Feishu SVG Whiteboard Design System

An ambient AI interface system: soft indigo, emerald green, and warm grey on clean white. Pill shapes, generous padding, and a friendly, intelligent feel. The bot is helpful, not scary.

## Color

Eight solids in a calm AI palette. **Canvas** (`#FAFAFC`) is near-white. **Panel** (`#FFFFFF`) is pure white. **Indigo** (`#6366F1`) is the AI brand color; **indigo-light** (`#A5B4FC`) is support. **Green** (`#10B981`) and **amber** (`#F59E0B`) are functional indicators. **Ink** (`#1E1B2E`) is deep indigo-black. **Border** (`#E8E6F0`) is soft lavender.

## Rules

This template is the **palette + mood** only. Every medium constraint (native shapes, opacity ignored, the text-color export caveat, no gradients/filters/shadows, reflow) and the build/verify workflow live in **[`../../RULES.md`](../../RULES.md)** — read it before building.
