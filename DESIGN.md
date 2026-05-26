# THE FELON — Design & Implementation Plan

**Status**: Research complete. Now building the experience on `dev`.

## Core Principles
- **Editorial premium**: Feels like a high-end long-form aviation intelligence feature (think top-tier magazine digital experience).
- **Radical honesty**: Every estimate, unconfirmed claim, or analytical judgment is visually flagged. No hype.
- **Surprise & delight through interaction**: Not gimmicks — tools that help the user *explore* the data (RCS visualizer, live comparator).
- **Single file, zero build**: index.html + Tailwind Play CDN + Chart.js CDN + vanilla JS + Canvas.
- **Performance & access**: Fast, keyboard-navigable, respects reduced motion, excellent on mobile.

## Visual Design System
- **Background**: #050505 (rich near-black) with subtle film grain overlay.
- **Surfaces**: #0a0c10 / #111317 (layered cards with 1px border in #22262e).
- **Accent Gold**: #c5a36e (for headlines, CTAs, "estimated" badges).
- **Data Cyan**: #4aa3e0 (charts, numbers, interactive highlights).
- **Text**: #e8e6e1 primary, #a1a1aa secondary.
- **Typography**: System UI (San Francisco / Inter / Segoe) for clarity + editorial weight. Large display sizes (5xl–7xl) for impact.
- **Motion**: 300–600ms elegant cubic-bezier. Heavy use of `scroll-behavior: smooth`, intersection observers for progressive reveals. Subtle hover lifts and magnetic feel on key buttons.
- **Imagery**: All real Wikimedia direct links. Dark overlays, tasteful captions with license.

## Page Architecture (One Long Scroll)
1. **Fixed Nav** — Logo "THE FELON", section links, "Sources & Caveats" button, Git status note (dev).
2. **Hero** — Massive dramatic photo + overlay typography + scroll prompt + subtle interactive data line.
3. **Intelligence Strip** — 5 key facts in a tight bar (some flagged "est.").
4. **The Program** — Narrative intro + **Interactive Timeline** (Milestone 2).
5. **Anatomy** — 3-view + data grid + "Loadout Explorer" mini interaction.
6. **The Stealth Equation** — Deep dive + **RCS Signature Visualizer** (Canvas + sliders) — the signature surprise (Milestone 4).
7. **Against the Peers** — **Live Rival Comparator** with Chart.js radar + priority sliders (Milestone 3).
8. **Combat Record** — Filterable events + simple deployment map (Milestone 5).
9. **In the Lens** — Masonry gallery + pure-JS elegant lightbox with full attribution (Milestone 6).
10. **Synthesis + Sources** — Final editorial note + exhaustive open-source bibliography.

## Key Interactive Features (Ranked by Impact)
- **RCS Canvas Visualizer** (highest priority "wow"): Top-down silhouette. Slider for azimuth. Dynamic RCS "lobes" drawn in real time. Toggle comparison with F-22 and J-20. Prominent "These are illustrative estimates only" banner + source.
- **Rival Comparator**: Three radar charts (or one grouped). 4–5 weighting sliders that recalculate composite "mission effectiveness" scores live. Every bar/score labeled as open-source synthesis.
- **Timeline**: Clickable milestones that (a) scroll to relevant section, (b) highlight related image in gallery, (c) update a "context" sidebar image.
- **Gallery Lightbox**: Beautiful, fast, keyboard (esc / arrows), shows license + photographer + direct link.
- **Spec Explorer** (light): Toggle "Stealth config" vs "Max payload" and watch key numbers animate.
- **Micro interactions**: Progress bar on scroll, section "focus" states, copy-to-clipboard for key facts, reduced-motion safe.

## Milestone & Commit Strategy (as in todo list)
Each milestone = working, testable slice that already looks good when opened in browser.
- Commit only after manual browser open + basic QA (responsive, no console errors, interactions work, images load).
- Merge to `main` only at the very end after full pass.

## Content Tone
- Precise, slightly literary, never sensationalist.
- "Russia claims..." vs "OSINT has not independently confirmed..."
- Short paragraphs. Generous use of pull-quotes for key caveats.

## Technical Notes
- Tailwind via CDN: `<script src="https://cdn.tailwindcss.com"></script>`
- Chart.js: jsDelivr latest
- No external fonts (system only) for reliability
- All images use `loading="lazy"` + proper `alt` + caption attribution
- One single 100% self-contained file at the end

This plan is grounded directly in the RESEARCH.md dossier.

Ready for Milestone 1 execution.