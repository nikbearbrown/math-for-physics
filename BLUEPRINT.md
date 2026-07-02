# BLUEPRINT.md — Mathematics for Physics
## The Tools, Derived on the Page, Motivated by Mechanics
**Author:** Nik Bear Brown
**Status:** Reorganized from physics-topic to math-topic. Structure locked; ready for drafting.
**Last updated:** 2026-05-30

---

## Thesis
The introductory physics sequence is, underneath, a sequence of mathematical tools. Teach the tools as mathematics — derived, general, transferable — and the physics becomes the place you *use* them rather than the thing you must memorize. This book reorganizes mechanics-and-waves into the math it requires.

## Reader
Calculus-based intro-physics students (often taking calculus concurrently) and self-studiers who want the math behind the physics. High-school physics + algebra assumed; college calculus built where needed.

## Chapter anatomy (every chapter)
1. **Cold open** — one concrete physics problem the chapter's math is required to solve (no math yet).
2. **The tool, named** — plain statement of the mathematical object/method.
3. **Development & derivation** — the math built for its own sake, on the page.
4. **Worked examples** — drawn from the retained physics source chapters.
5. **Return to the cold open** — the problem solved with the tool.
6. **Where it generalizes** — one paragraph: where else this math goes, beyond physics.

Source-chapter material lives in `chapters/_physics-source/`; mine it for examples, derivations, and figures.

---

## PART I — QUANTITIES AND GEOMETRY (the language)

### 01 — Units, Dimensions, and Estimation
**Math:** SI units, dimensional analysis, significant figures, error propagation, order-of-magnitude estimation.
**Cold open / source:** measurement & the redefined kilogram (source ch. 02). 
**Key derivations:** dimensional consistency as an equation constraint; propagation of uncertainty through products and powers.

### 02 — Algebra and Equations in Physics
**Math:** rearranging and solving equations, ratios and proportionality, units inside algebra, solving for an unknown symbolically before substituting.
**Cold open / source:** Newton's-law setups and equilibrium relations (source ch. 06, 07, 13).
**Key derivations:** isolating variables in multi-term relations; proportional reasoning (scaling laws).

### 03 — Trigonometry and Geometry
**Math:** angles, the unit circle, sine/cosine/tangent, right-triangle decomposition, the laws of sines/cosines, radians.
**Cold open / source:** resolving a force on an incline; projectile angle (source ch. 03, 07).
**Key derivations:** components from magnitude-and-angle; small-angle behavior previewed.

### 04 — Vectors and Vector Algebra
**Math:** components, unit vectors, addition/scaling, dot product (projection), cross product (oriented area/rotation), 3D.
**Cold open / source:** the pilot's ground-track vector sum (source ch. 03).
**Key derivations:** dot product ↔ angle; cross product ↔ area and right-hand rule.

---

## PART II — CALCULUS (the engine)

### 05 — Functions, Graphs, and Power Laws
**Math:** functions, linear/quadratic/power/exponential forms, reading and building graphs, log–log lines and scaling exponents.
**Cold open / source:** position-vs-time and the shape of a fall (source ch. 04).
**Key derivations:** slope and area as the two questions calculus will answer; power-law exponents from log–log slope.

### 06 — Limits and the Derivative
**Math:** limits, the derivative as instantaneous rate, rules (power, product, quotient, chain).
**Cold open / source:** instantaneous velocity, v(t) = dx/dt (source ch. 04).
**Key derivations:** derivative from the limit of the difference quotient; v and a as first/second derivatives.

### 07 — Differentiation in Motion: Vector-Valued and Parametric Functions
**Math:** differentiating vector-valued functions, parametric curves, velocity/acceleration vectors, related rates.
**Cold open / source:** projectile and circular motion in 2D/3D (source ch. 05).
**Key derivations:** componentwise differentiation; centripetal acceleration from differentiating a rotating unit vector.

### 08 — The Integral
**Math:** the definite integral as accumulation/area, the Fundamental Theorem, antiderivatives.
**Cold open / source:** work as ∫F·dx; distance as ∫v dt (source ch. 08).
**Key derivations:** integral as the limit of a Riemann sum; FTC linking the two calculus questions.

### 09 — Integration Techniques and Applications
**Math:** substitution, integration by parts, integrating over distributions; line integrals; integrals that compute moment of inertia, center of mass, pressure force.
**Cold open / source:** moment of inertia of a rod/disk; potential energy from a force law; fluid pressure on a wall (source ch. 09, 11, 14, 15).
**Key derivations:** ∫r²dm for simple bodies; gravitational PE from ∫F·dr.

---

## PART III — SYSTEMS AND CHANGE (the hard tools)

### 10 — Linear Systems and Matrices
**Math:** simultaneous equations, substitution/elimination, matrices and determinants, 2×2/3×3 solving.
**Cold open / source:** static equilibrium (ΣF = 0, Στ = 0) and multi-body collisions (source ch. 10, 13).
**Key derivations:** solving an equilibrium system; conservation equations as a linear system.

### 11 — Differential Equations and Oscillatory Motion
**Math:** first/second-order ODEs, separable equations, the harmonic-oscillator equation, exponential growth/decay.
**Cold open / source:** the mass on a spring, x'' = −(k/m)x (source ch. 17, 14).
**Key derivations:** solving ẍ = −ω²x; characteristic-equation method; decay from a separable ODE.

### 12 — Complex Numbers and Exponentials
**Math:** complex arithmetic, the complex plane, Euler's formula, complex exponentials as the natural language of oscillation.
**Cold open / source:** damped/driven oscillation phase (source ch. 17).
**Key derivations:** e^{iθ} = cosθ + i sinθ; oscillation solutions as Re(e^{iωt}).

### 13 — Series, Expansions, and Approximations
**Math:** sequences/series, Taylor/Maclaurin expansion, small-angle and binomial approximations, convergence intuition.
**Cold open / source:** sin θ ≈ θ for the pendulum; binomial approximations (source ch. 17).
**Key derivations:** Taylor series of sin/cos/e^x; why small-angle linearization makes SHM solvable.

### 14 — Partial Derivatives, the Wave Equation, and Fourier Analysis
**Math:** functions of several variables, partial derivatives, the 1D wave equation as a PDE, superposition, Fourier series, logarithms (decibels) as a coda.
**Cold open / source:** a wave on a string; building a complex tone from harmonics (source ch. 18, 19).
**Key derivations:** ∂²y/∂t² = v²∂²y/∂x² and its traveling-wave solution; a periodic signal as a sum of sines (Fourier); the decibel as a log ratio.

---

## Front/back matter
- `00-frontmatter.md`, `00-introduction.md` (rewrite to the math-led frame), `99-back-matter.md` — keep, rewrite intro to state the math-tools thesis.

## Source mapping (physics chapter → math chapter)
02→01 · 06/07/13→02,10 · 03/07→03,04 · 04→05,06 · 05→07 · 08→08 · 09/11/14/15→09 · 10/13→10 · 17/14→11 · 17→12,13 · 18/19→14

## Open decisions
- [ ] Confirm 14-chapter math structure above before drafting.
- [ ] Keep chapter exercises? (physics source has them; decide math-exercise style.)
- [ ] Figures: regenerate from a fresh CAJAL pass on the new math chapters (the 20 existing cajal plans are physics-topic and now stale).
