# CAJAL SVG Generation Log — Mathematics for Physics (Vol. 1)

## Run: 2026-05-30
Full CAJAL figure pass on the 14 math-topic chapters: planned figures per chapter, wrote per-chapter CAJAL reports, generated static SVGs in the series' brutalist house style (EB Garamond / IBM Plex Mono; palette #2a1a0e ink, #C8102E red, #6B3520 brown, #545454, #D4D4D4, #F5EFE8; viewBox 0 0 700 420; shared arrow marker), inserted figure references, and converted SVG→PNG.

The 20 prior cajal reports from the old *physics* chapter structure were archived to `pantry/_stale-physics-cajal/` before this pass (they did not match the reorganized math chapters). PNGs rasterized via Python svglib/reportlab at the house width (2917px) — no node_modules/sharp wired in this book.

| Chapter | Figs | Concepts |
|---|---|---|
| 01 units-dimensions-and-estimation | 3 | dimensional homogeneity; pendulum period by exponent-matching; relative-uncertainty amplification |
| 02 algebra-and-equations-in-physics | 3 | Atwood-machine solution + limits; square–cube law; incline slip criterion |
| 03 trigonometry-and-geometry | 3 | unit circle (sin/cos/tan); weight resolved on an incline; small-angle sinθ≈θ |
| 04 vectors-and-vector-algebra | 3 | tip-to-tail addition (pilot+wind); dot product as projection; cross product as oriented area |
| 05 functions-graphs-and-power-laws | 2 | four function shapes; free-fall power law straightening on log–log (slope 2) |
| 06 limits-and-the-derivative | 2 | secant→tangent (difference quotient); x/v/a as successive slopes |
| 07 differentiation-in-motion | 2 | projectile path with velocity/acceleration vectors; centripetal a=v²/r from a rotating vector |
| 08 the-integral | 2 | Riemann rectangles converging to area; FTC linking slope & area |
| 09 integration-techniques-and-applications | 2 | disk rings for ∫r²dm → ½MR²; hydrostatic dam force ½ρgwh² |
| 10 linear-systems-and-matrices | 2 | 2×2 system as intersecting lines; determinant as area / parallel = no solution |
| 11 differential-equations-and-oscillatory-motion | 2 | SHM x(t)=A cos ωt; the three damping regimes |
| 12 complex-numbers-and-exponentials | 2 | complex plane (rectangular & polar); Euler's formula on the unit circle |
| 13 series-expansions-and-approximations | 2 | sin x with 1/2/3-term Taylor approximations; small-angle error growth |
| 14 partial-derivatives-wave-equation-and-fourier | 2 | standing-wave modes n=1,2,3; square wave from summed Fourier sine terms |

## Summary
Chapters processed: 14 · CAJAL reports: 14 (`pantry/*-cajal.md`) · SVGs: 32 · PNGs: 32 · figure references inserted: 32.
Consistency: every chapter's referenced figure numbers match its PNG files exactly — zero orphans, zero broken references. House brutalist style throughout; one red data category per figure; plain-text math labels (SVG has no LaTeX).
