# OC4211 Test 2 — Lecture Slide Method (v8 — annotated algebra)

A single-file mobile study workbook for eight OC4211 sample problems and the announced Poincaré derivation. The solution order follows the corresponding **lecture slides** (especially Lecture 15 slides 3–7 and Lecture 16 slides 3–6). No arbitrary step counts or complex-amplitude shortcuts.

## Method

1. Identify starting governing equations (or the supplied dispersion relation).
2. Linearize, where needed, exactly as in the lectures.
3. Count unknown fields and choose the field to keep.
4. Apply the slide's differentiation and elimination operators until **one equation has one unknown**.
5. Only then insert an ideal sinusoid, when the slide does, to obtain the dispersion relation.
6. Convert to the problem's target and substitute numbers.

Every algebraic operation repeats its input equation(s) in the same step. A red diagonal line crosses out terms removed by cancellation or approximations; green highlights the values or equations substituted. The resulting equation follows immediately below.

All derivatives are explicit `∂u/∂t` / `dω/dk`; no subscript derivative notation.

## Deploy updates to GitHub Pages

Open your existing GitHub repository → **Add file → Upload files**. Extract the ZIP and upload its **individual contents**, not the containing folder. Replace `index.html`, `sw.js`, and all companion support files at the repository root; commit directly to `main`. Your Pages URL remains unchanged. If the previous version is still showing on your phone, close the Home Screen web app, open the published site in Safari while online, refresh, and reopen.

## Source alignment

- P1 & P2: Lecture 12 (dispersion relations).
- P3: Lecture 15 slides 3–7 (linearize → pressure eliminated → density eliminated → continuity → PDE for w → sinusoid → ω/N).
- P4: Lecture 16 slides 4–7 (Poincaré amplitudes).
- P5: Lecture 19 slides 6–9 (Rossby group velocity).
- P6: Lecture 18 slides 4–6 & 13 (Kelvin, coast-normal u=0).
- P7: Lecture 17 slides 12–16 (closed-basin standing wave).
- P8: Lecture 21 slide 7 (equatorial Rossby dispersion; illustrative scales explicitly identified).
- Known Question 5: Lecture 16 slides 3–6 (combine the three equations into a PDE for u, then sinusoid).

### Note on P3 angle

Lecture 15 distinguishes the wavevector angle φ, where ω=N cosφ, from the energy/group-velocity angle θ, where ω=N sinθ. The original worked lesson interprets its 30° as φ. The alternative is labeled in the study solution rather than silently conflated.


### Version 9 · Problem 4 correction

Problem 4 now derives the Poincaré dispersion relation from the three linearized rotating shallow-water equations following Lecture 16 slide 5. It cancels v, substitutes continuity to eliminate η, derives ω²=f²+ghk² from the single-field PDE, and only then computes the given wave’s horizontal velocity amplitudes. The cancellations and substitutions are marked red and green, respectively, with all equations repeated in the step where they are used. Other problems are unchanged.
