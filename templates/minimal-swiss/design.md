---
version: 1.0
name: Minimal Swiss
renderer: feishu-svg-whiteboard
description: >
  A pure Swiss/International Style system — white space is the loudest element. Black ink on a white canvas, structured by an invisible grid, with one quiet accent (cool steel blue) for section dividers and key numerals. No ornament, no shadow, no decoration. Type is king: large bold headlines, restrained body text. Good for enterprise explainers, process flows, architecture diagrams, and any board that must read as serious and authoritative.

# ── COLOR ────────────────────────────────────────────────────
colors:
  canvas:   "#FFFFFF"   # pure white ground
  panel:    "#FAFAFA"   # off-white card fill, barely there
  ink:      "#1A1A1A"   # primary text and structure — near-black
  accent:   "#3B6FA0"   # cool steel blue — section bands, numerals, rules (sparingly)
  muted:    "#E8ECF0"   # quiet divider / subtle panel background
  # Rule: 1 accent max per scene. Ink on white/panel; white text on accent fills only when bold ≥ 20px.

# ── DEPTH ────────────────────────────────────────────────────
# FLAT system — no shadows. Depth = scale contrast (big headline vs small body),
# and the single accent against white.

# ── STROKE & CORNERS ─────────────────────────────────────────
stroke:
  structural: "2px solid #1A1A1A"   # thin, precise card borders
  rule:       "1px solid #E0E0E0"   # hairline dividers
  radius: 0                          # sharp corners — Swiss is orthogonal
---

# Minimal Swiss — Feishu SVG Whiteboard Design System

A pure black-white-blue Swiss system: white canvas, black ink, one cool steel-blue accent for structure. Type carries the hierarchy; color stays quiet.

## Color

Four solids. **Canvas** (`#FFFFFF`) is pure white; **panel** (`#FAFAFA`) is a whisper-off-white for card fills. **Ink** (`#1A1A1A`) is the only text/structure color. **Accent** (`#3B6FA0`) is a restrained steel blue used ONLY for section header bands, key numerals, and horizontal rules — never for body text. **Muted** (`#E8ECF0`) is a quiet divider background.

One accent per scene max. Dark text on white/panel; white text on accent fills only when bold and ≥ 20px.

## Rules

This template is the **palette + mood** only. Every medium constraint (native shapes, opacity ignored, the text-color export caveat, no gradients/filters/shadows, reflow) and the build/verify workflow live in **[`../../RULES.md`](../../RULES.md)** — read it before building.
