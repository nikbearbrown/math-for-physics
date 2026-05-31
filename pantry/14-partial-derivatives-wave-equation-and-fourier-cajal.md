# CAJAL figure report — Chapter 14: Partial Derivatives, the Wave Equation, and Fourier

Two figures. One shows the standing-wave modes of a string fixed at both ends (the
quantized harmonics f_n = nv/2L); the other shows a square wave being built up from summed
Fourier sine terms — the chapter's headline "any periodic signal is a sum of pure tones."

## Figure 14.1 — Standing-wave modes of a fixed string
- **Concept:** A string pinned at both ends supports only standing waves with nodes at the
  ends; the allowed modes have wavelengths λ_n = 2L/n and frequencies f_n = nv/2L. Each mode
  is a sin(nπx/L) shape with n−1 interior nodes.
- **Type:** Stacked multi-panel diagram — three mode shapes, one per row.
- **What it shows:** Three horizontal panels sharing the string length L on the x-axis. Top:
  the FUNDAMENTAL n=1, a single arch (one antinode, nodes only at the ends), labelled
  f₁ = v/2L. Middle: n=2, two arches with one interior node, f₂ = 2f₁. Bottom: n=3, three
  arches with two interior nodes, f₃ = 3f₁. The red accent traces the curve outline; the
  faint mirror-image curve shows the swing envelope. Nodes marked with small dots, antinodes
  noted. Fixed ends drawn as small wall hatches at x = 0 and x = L.
- **SCOPE — include:** three mode shapes (n = 1, 2, 3); the envelope (mirror curve) per mode;
  nodes/antinodes marked; fixed-end hatches; f_n labels tied to f₁.
- **SCOPE — exclude:** the wave-equation derivation; traveling waves; the Fourier sum (that is
  Fig 14.2); numeric guitar-string values; the time axis (these are spatial snapshots).

## Figure 14.2 — A square wave built from summed Fourier sine terms
- **Concept:** A square wave equals (4/π)[sin ω₀t + ⅓ sin 3ω₀t + ⅕ sin 5ω₀t + ···]. Adding
  successive odd harmonics squares up the shape; the partial sums converge toward the square
  wave (with a small persistent overshoot at the jumps — Gibbs).
- **Type:** Multi-curve line plot (y vs. t over one period), partial sums plus target.
- **What it shows:** The target square wave drawn faint (ink, dashed, the ±1 step). Over it,
  three partial sums: 1 term = a lone sine (brown); 2 terms = sin + ⅓ sin3 (the top starts to
  flatten); 3 terms = sin + ⅓ sin3 + ⅕ sin5 (red, the closest, corners sharpening). Each
  partial sum labelled with its term count. A small note flags the Gibbs overshoot near the
  jump. t axis over one period; y axis.
- **SCOPE — include:** the dashed target square wave; the 1-, 2-, 3-term partial sums; curve
  labels; the Gibbs-overshoot note; t and y axes with zero line.
- **SCOPE — exclude:** the Fourier-coefficient integrals; the cosine terms (square wave is
  odd, sines only); standing waves (Fig 14.1); the decibel/log coda; spectrum bar charts.
