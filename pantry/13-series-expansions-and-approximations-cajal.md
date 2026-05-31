# CAJAL figure report — Chapter 13: Series, Expansions, and Approximations

Two figures. One shows successive Taylor truncations of sin x hugging the true curve and
peeling away — convergence made visible; the other isolates the small-angle approximation
sin θ ≈ θ and shows its error growing like θ³.

## Figure 13.1 — Taylor approximations of sin x converging
- **Concept:** The Maclaurin series sin x = x − x³/3! + x⁵/5! − ··· truncated to 1, 2, and 3
  terms gives polynomials that hug sin x near 0 and peel away farther out; each added term
  widens the region of good agreement.
- **Type:** Multi-curve line plot (y vs. x), one true curve plus three approximations.
- **What it shows:** The true sin x curve (ink, solid) over roughly x ∈ [−π, π... actually
  0 to ~5] alongside three truncations: the 1-term line y = x (brown, peels off fast), the
  2-term y = x − x³/6, and the 3-term y = x − x³/6 + x⁵/120 (red, the best, tracks sin x
  furthest). Each curve labelled; a faint marker shows where each approximation noticeably
  departs from sin x. Axes x and y with the origin centred.
- **SCOPE — include:** true sin x; the 1-, 2-, 3-term Taylor curves; curve labels; x and y
  axes with zero lines; visual point that more terms = wider agreement.
- **SCOPE — exclude:** the coefficient-derivation algebra; cosine and exponential series;
  radius-of-convergence formalism; the small-angle error number (that is Fig 13.2).

## Figure 13.2 — The small-angle approximation sin θ ≈ θ and its shrinking error
- **Concept:** Near θ = 0 the line y = θ and the curve y = sin θ are nearly indistinguishable;
  the gap between them is the dropped term ≈ θ³/6, so the relative error ≈ θ²/6 grows with
  angle — about 1% at 15°, 0.1% at 5°.
- **Type:** Line plot with an error inset/annotation (y vs. θ, small θ range).
- **What it shows:** Over a small angle range (0 to ~0.6 rad ≈ 0..35°) the straight line
  y = θ (red) and the curve y = sin θ (ink) drawn together; they coincide at the origin and
  the vertical gap between them widens to the right. The gap at a sample angle is bracketed
  and labelled "error ≈ θ³/6". A small text block gives the relative-error rule θ²/6 with the
  1%-at-15° / 0.1%-at-5° figures. θ axis in radians (with a degree note); y axis.
- **SCOPE — include:** the y = θ line and y = sin θ curve; the widening gap with an error
  bracket; the θ²/6 relative-error note with the 15°/5° numbers; radians label.
- **SCOPE — exclude:** the full sine series beyond the cubic term; cosine approximation;
  the pendulum picture; convergence over large x (that is Fig 13.1).
