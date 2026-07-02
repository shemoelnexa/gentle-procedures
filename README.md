# Gentle Procedures Dubai — Homepage Concepts

Two homepage concept directions for review. Per the signed brief, both share **one design** and differ **only in the hero treatment** ("one site, two front doors"):

- **`concept-a.html` — "The Threshold"** · full-bleed cinematic hero (dark, image-led). The film fills the frame; the words rest quietly over it.
- **`concept-b.html` — "Trust in Silence"** · type-led, asymmetric hero (light, serene). The Canela line sits in open Alabaster space; the film is a contained, off-centre frame with deep margins (Aman restraint, Joali weightlessness).
- **`index.html`** · gallery linking both.

Everything below the hero is identical across the two concepts (sections 2 to 9 are byte-for-byte the same file).

## Status
Shown in **State One** (pre-launch) form: no surgeon name, photo, or narrowing detail anywhere (embargo holds to 00:01, 8 Sep 2026).

- **Type:** the production faces **Canela** (display) and **Söhne** (body), **self-hosted as WOFF2** (no Google Fonts CDN). These are the trial cuts, whose glyph set is letters, digits, and basic punctuation; a matched grotesk (subset Inter) supplies the few punctuation glyphs the trial cut omits. Swap to the full licensed cuts for production.
- **Imagery:** interim, launch-film-grade stand-ins for the launch-film stills. The "Arriving" still is a **sanitised crop of the clinic's own Citadel reception render** (travertine and warm light only; the "Day Surgery Center LLC" signage, reception desk, screens, and props are cropped out per the brand rules).
- **Credential figures** (e.g. `[200,000]`, DHA licence) render as editable placeholder tokens.

## Preview locally
```bash
python -m http.server 8765
# then open http://127.0.0.1:8765/
```

## Notes
This repository contains the **website deliverable only**. Confidential briefs, renders, and internal source documents are intentionally kept out of version control. The raw Citadel render (`assets/img/reception.png`) is git-ignored; only the sanitised crop (`assets/img/clinic-arrival.jpg`) ships.
