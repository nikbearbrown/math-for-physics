# Math Coverage Gap Analysis — can *Mathematics for Physics* refresh every physics/quantum book?

**Date:** 2026-05-30
**Question:** If a learner in any of the physics/quantum books needs a math refresher, can they come here and find it?
**Short answer:** **Not yet.** The current 14-chapter plan covers the math of *introductory mechanics and waves*. It is missing the tools that electromagnetism, quantum mechanics, thermodynamics/statistical mechanics, modern physics, and optics actually run on. Below is what the books demand vs. what's planned, and the chapters needed to close the gap.

## Books checked
physics · physics-classical-mechanics · physics-electromagnetism · physics-modern-physics · physics-optics · physics-quantum-mechanics · physics-thermodynamics · physics-astronomy · quantum-mechanics-a-companion-guide

---

## Coverage table

| Math tool | In current MFP plan? | Books that demand it (from chapter scan) |
|---|---|---|
| Units, dimensions, error | ✅ Ch.01 | all |
| Algebra, proportionality, scaling | ✅ Ch.02 | all |
| Trigonometry & geometry | ✅ Ch.03 | all |
| Vectors (dot/cross, 3D) | ✅ Ch.04 | all |
| Functions, graphs, power laws | ✅ Ch.05 | all |
| Limits & derivatives | ✅ Ch.06 | all |
| Vector-valued / parametric diff. | ✅ Ch.07 | mechanics, E&M, optics |
| Integration + techniques | ✅ Ch.08–09 | all |
| Linear systems (2×2/3×3) | ✅ Ch.10 | all |
| ODEs & oscillation | ✅ Ch.11 | all |
| Complex numbers / Euler | ✅ Ch.12 | QM, companion, optics, E&M (phasors) |
| Series / Taylor / approximations | ✅ Ch.13 | all |
| Partial derivatives, wave PDE, **Fourier series** | ✅ Ch.14 (intro level) | waves, QM, optics, thermo |
| **Probability & statistics** | ❌ **absent** | **physics, QM(14), companion(10), thermo(9), modern(8), astronomy, optics** |
| **Eigenvalues/eigenvectors, operators, inner products, Dirac/bra-ket** | ❌ **absent** (Ch.10 stops at solving systems) | **QM(12–15), companion(10), modern, optics, classical normal modes** |
| **Vector calculus: grad/div/curl, Laplacian, Gauss & Stokes, surface/volume integrals** | ❌ **explicitly scoped out** | **E&M (Gauss/Stokes in 14 ch, div/curl in 7), physics(8)** |
| **Fourier transforms** (not just series) | ❌ partial (series only) | QM(5), optics, modern, thermo |
| **Multivariable calculus for thermo** (exact/inexact differentials, Maxwell relations, Jacobians, Legendre transforms) | ❌ absent | **thermodynamics, E&M, QM** |
| **Combinatorics, multiplicity, Stirling's approximation** | ❌ absent | **thermo/stat-mech(5), QM, astronomy** |
| **Special-relativity math: hyperbolic functions, Lorentz transforms, four-vectors, tensors** | ❌ absent | **modern, E&M(3), physics, QM** |
| **Special functions & separation of variables** (Legendre, Hermite, Bessel, spherical harmonics) | ❌ absent | **QM(5), optics, astronomy** |
| **Lagrangian/Hamiltonian, calculus of variations** | ❌ absent | **QM(10), companion(8), advanced classical** |
| **Logarithms & exponentials as a topic** (magnitudes, decibels, decay) | partial (decibel coda only) | astronomy (magnitudes), thermo, optics |

---

## The gaps, ranked by cross-book demand

1. **Probability & statistics — highest priority.** Appears in *every* book scanned. Needed: random variables, probability distributions, mean/variance/standard deviation, the Gaussian/normal, Poisson, Boltzmann distribution, and propagation of error (beyond Ch.01's basics). QM (expectation values, Born rule), thermo/stat-mech (ensembles), modern (decay statistics), astronomy (measurement), and lab error analysis all require it.

2. **Linear algebra for quantum mechanics.** Ch.10 stops at solving small systems; QM and the companion guide need **eigenvalues/eigenvectors, Hermitian operators, inner products, orthonormal bases, diagonalization, and Dirac (bra-ket) notation / Hilbert space**. This is the single largest gap for the quantum books (12–15 chapters touch it).

3. **Vector calculus & field theorems — for E&M.** Gradient, divergence, curl, the Laplacian, line/surface/volume integrals, and the Gauss & Stokes theorems. Electromagnetism is built on these (Gauss/Stokes flagged in 14 of its chapters); `book.md` currently scopes them *out*.

4. **Multivariable calculus for thermodynamics.** Exact vs. inexact differentials, partial-derivative manipulation, Maxwell relations, Jacobians, Legendre transforms. Ch.14 only introduces partial derivatives; thermo needs the working machinery.

5. **Combinatorics & Stirling's approximation.** Counting microstates, multiplicity, factorials/binomials, Stirling — the backbone of statistical mechanics (thermo) and parts of QM/astronomy.

6. **Fourier transforms** (continuous, momentum space) — QM and optics need the transform, not just the series in Ch.14.

7. **Special-relativity math** — hyperbolic functions, rapidity, Lorentz transformations as matrices, four-vectors, light-cone geometry. Needed by modern physics and parts of E&M.

8. **Special functions & separation of variables** — Legendre/Hermite/Bessel polynomials, spherical harmonics, solving PDEs by separation in spherical/cylindrical coordinates. Needed by QM (hydrogen atom, angular momentum) and optics (diffraction).

9. **Lagrangian/Hamiltonian mechanics & calculus of variations** — the Euler–Lagrange equation, action, generalized coordinates. Needed by advanced classical mechanics and the QM formalism.

10. **Logarithms & exponentials as a first-class topic** — magnitudes (astronomy), decibels (optics/sound), exponential decay (modern). Currently only a decibel coda.

---

## Recommended expansion

Keep the current 14 chapters as **Part I–III (the introductory core)**, and add three more parts so the book becomes the universal refresher:

**Part IV — Fields and Multivariable Calculus** (for E&M, thermo)
- 15. Logarithms, Exponentials, and Scales (magnitudes, decibels, decay) — *or* fold into Ch.05
- 16. Multivariable & Partial Derivatives in Depth (gradients, exact/inexact differentials, Maxwell relations)
- 17. Vector Calculus: Divergence, Curl, and the Field Theorems (Gauss & Stokes) — the E&M chapter

**Part V — Linear Algebra and the Mathematics of Quantum Mechanics** (for QM, modern, optics)
- 18. Vector Spaces, Eigenvalues, and Diagonalization
- 19. Operators, Inner Products, and Dirac Notation
- 20. Fourier Transforms and Special Functions / Separation of Variables

**Part VI — Probability, Counting, and Relativity** (for thermo, QM, modern, astronomy)
- 21. Probability and Statistics for Physics (distributions, expectation/variance, error analysis)
- 22. Combinatorics, Multiplicity, and Stirling's Approximation (statistical mechanics)
- 23. The Mathematics of Special Relativity (hyperbolic functions, Lorentz transforms, four-vectors)

*(Optional, advanced)* 24. Calculus of Variations and the Lagrangian/Hamiltonian Formalism — for advanced classical mechanics and QM formalism; could be deferred to a second volume.

This takes the book from 14 → ~23 chapters and makes it genuinely sufficient as the refresher behind every physics/quantum book in the series.

---

## Per-book "where would the learner come up short today"
- **electromagnetism:** no Gauss/Stokes, no div/curl/grad — the core mathematical language of the book is missing.
- **quantum-mechanics / companion:** no eigenvalues, operators, inner products, Dirac notation, Fourier transform, or special functions — most of the math the book runs on.
- **thermodynamics:** no exact/inexact differentials, Maxwell relations, combinatorics, or Stirling — the stat-mech toolkit is missing.
- **modern-physics:** no relativity math (hyperbolic/Lorentz) and no probability/statistics.
- **optics:** no Fourier transform, limited special functions — diffraction math under-served.
- **astronomy:** logs/magnitudes and probability/statistics under-served.
- **classical-mechanics (intro) & physics (intro):** **well covered** by the current 14 chapters — these are the books the book already serves.

## Decision (resolved 2026-05-30)
**Spin the advanced tools into a separate book — `math-for-physics-vol-2` ("Mathematics for Physics, Vol. 2: Advanced Tools").** Vol. 1 stays as the intro-mechanics-and-waves volume (14 chapters). Vol. 2 (11 chapters) covers the gap list above: logs/scales, multivariable & partial derivatives in depth, vector calculus + field theorems, linear algebra/eigenvalues, operators & Dirac notation, Fourier transforms, special functions & separation of variables, probability & statistics, combinatorics & Stirling, special-relativity math, and a calculus-of-variations capstone. Vol. 2's `book.md` and `TIKTOC.md` are written; research pass pending.
