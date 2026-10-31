# EVE DECK v2 — Rabbit R1 Standalone Cyberdeck Creation

Standalone `240×282` single-Canvas 2D Rabbit R1 Creation built on `r1-creation-kit_2026-10-31` (`shell/app_template.html` + `camera_module.js` + `r1_qr.js` + `build_bundle.py`):
- **Single `<canvas width="240" height="282">`** (ES5 IIFE, zero external `<script src>`, `>=28px` touch targets, serpentine wheel cursor with `45ms` debounce, `"Touch aims, PTT commits"` doctrine, `longPressStart` universal `ACTIONS` menu, `400ms` debounced `creationStorage.plain` Base64 autosave + `visibilitychange`/`pagehide` flush).
- **MIC**: Talk to Sovereign Ani / Jules (`:8094`) with `R1` / `PC` / `Both` speaker playback or universal PC cursor dictation.
- **DECK**: 12-button tactile Cyberdeck Macro Pad (`>=39px` height × `74px` width, serpentine scroll wheel + touch-aim + side PTT commit).
- **EYE**: 360° AI Eye camera (`R1Camera` 3-round `enumerateDevices` + `{ideal:'environment'}` + gesture re-arm) → `meta/muse-glimmer` (`:1234`).
- **SYS & QR SHARE**: Live somatic bridge telemetry, automatic `endpoint.json` (`cache:'no-store'`) tunnel sync, and on-device ISO/IEC 18004 `MCQR` export screen.
- **Verification**: In-browser `selftest.html` (`window.__EVE_DECK_SELFTEST__`), `window.__APP__` test hooks, and SHA-256 byte-identity check on GitHub Pages.

> Authentication uses a 256-bit local Bearer key stored strictly on the paired Rabbit R1 (`creationStorage.plain`) and never committed to this repository.
