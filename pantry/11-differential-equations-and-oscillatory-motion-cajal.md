# CAJAL figure report — Chapter 11: Differential Equations and Oscillatory Motion

Two figures. One makes the SHM solution x(t) = A cos(ωt) concrete (amplitude, period);
the other shows how the discriminant of the characteristic equation sorts the damped
oscillator into three named regimes.

## Figure 11.1 — The SHM solution: x(t) = A cos(ωt)
- **Concept:** The solution of ẍ = −ω²x for release-from-rest is a pure cosine; its
  amplitude A is the release displacement and its period T = 2π/ω is the time to repeat.
- **Type:** Single-curve line plot (displacement vs. time).
- **What it shows:** One full-and-a-bit cosine curve x(t) = A cos(ωt) (the red accent curve)
  on time–displacement axes. The amplitude A is marked as a vertical span from the t-axis to
  the peak; the period T is marked as a horizontal span between two successive peaks. A faint
  dashed line at x = +A and x = −A bounds the motion. Matches Example 1 in spirit (released
  from the far point with zero velocity).
- **SCOPE — include:** the cosine curve; amplitude bracket A; period bracket T; the ±A bound
  lines; t and x axes with zero line.
- **SCOPE — exclude:** velocity/acceleration curves; phase shift φ; damping; the spring
  picture itself; numeric values from Example 1 (keep symbolic A, T).

## Figure 11.2 — Three regimes of the damped oscillator
- **Concept:** The sign of the discriminant b² − 4mk sorts the solution of mẍ + bẋ + kx = 0
  into underdamped (decaying oscillation), critically damped (fastest non-overshooting
  return), and overdamped (sluggish return).
- **Type:** Multi-curve line plot (displacement vs. time, three curves on shared axes).
- **What it shows:** Three curves released from the same x₀ > 0: an UNDERDAMPED curve (red)
  that oscillates inside a decaying envelope and crosses zero several times; a CRITICALLY
  DAMPED curve (ink) that returns to zero quickly without crossing; an OVERDAMPED curve
  (brown) that returns more slowly without crossing. The decay envelope ±x₀e^(−bt/2m) is
  drawn faint/dashed around the underdamped curve. Each curve labelled.
- **SCOPE — include:** the three labelled curves; the decay envelope on the underdamped one;
  shared t and x axes with zero line; legend tying each curve to its discriminant case.
- **SCOPE — exclude:** the characteristic-equation algebra; complex-plane root locations
  (that is Chapter 12); driven/resonant response; numeric parameter values.
