# Fact-Check: Chapter 14 — Partial Derivatives, the Wave Equation, and Fourier Analysis

**Field:** Mathematics / Physics
**Source file:** chapters/14-partial-derivatives-wave-equation-and-fourier.md
**Date checked:** 2026-05-30

## Breakdown

- Assertions classified: 9 (4 historical attributions; 5 on-page math/physics derivations)
- Web-verified (historical): 4 — all CONFIRMED
- AI-verified (math/physics derivations): 5 — all CONFIRMED
- Flagged: 0

## ⚠️ Critical Findings

None found.

## Full Findings

### Historical attributions (web-verified)

1. **d'Alembert (1747) — wave equation and traveling-wave solution f(x−vt) + g(x+vt).** CONFIRMED. MacTutor: d'Alembert's 1747 article on vibrating strings "contains the first appearance of the wave equation in print"; the general solution as a sum of left- and right-traveling shapes is d'Alembert's formula. (Berlin Academy *Mémoires* 1749 is the publication venue.)
   URL: https://mathshistory.st-andrews.ac.uk/Biographies/DAlembert/ ; https://en.wikipedia.org/wiki/D%27Alembert%27s_formula

2. **Euler (1748–1755) — dispute over "arbitrary functions" in the string's solution.** CONFIRMED. The Euler–d'Alembert (and Bernoulli) controversy over what counts as an admissible "function" for the plucked string's initial shape is well documented and ran through the 1750s. Euler defended arbitrary (including non-smooth) shapes against d'Alembert's restriction to single analytic formulas.
   URL: https://mathshistory.st-andrews.ac.uk/Biographies/DAlembert/

3. **Daniel Bernoulli (1753, "Réflexions et éclaircissements sur les nouvelles vibrations des cordes") — every string motion as a superposition of harmonics.** CONFIRMED. Brillouin and standard histories date Bernoulli's statement of the superposition principle to 1753: "The general motion of a vibrating system is given by a superposition of its proper vibrations." (NB: this is the correct date — contrast the erroneous "1730s" attribution flagged in Chapter 11.)
   URL: https://en.wikipedia.org/wiki/Superposition_principle

4. **Fourier, *Théorie analytique de la chaleur* (1822; earlier 1807 memoir, criticized by Lagrange) — any periodic function as a sum of sines and cosines.** CONFIRMED. Fourier presented his heat memoir to the Paris Institute on 21 Dec 1807; a committee (Lagrange, Laplace, Monge, Lacroix) criticized the trigonometric-series expansions on grounds of rigor and generality, the objections led "probably at the insistence of Lagrange." The full treatise appeared in 1822. The chapter's "blocked by Lagrange" is a mild simplification (the 1811 prize was awarded but publication delayed; Lagrange led the criticism), and the "[verify; contested — see pantry]" flag handles it honestly. CONFIRMED with that nuance.
   URL: https://mathshistory.st-andrews.ac.uk/Biographies/Fourier/ ; https://en.wikipedia.org/wiki/Joseph_Fourier

### Math / physics derivations (AI-verified, no web)

5. **Partial derivatives of A sin(kx − ωt): slope, transverse velocity, curvature, acceleration.** CONFIRMED.
6. **Wave equation from F = ma on a string element: ∂²y/∂t² = (F_T/μ)∂²y/∂x², v = √(F_T/μ).** CONFIRMED — small-slope approximation, net force = F_T(∂²y/∂x²)Δx, mass μΔx.
7. **Traveling-wave check: f(x−vt) gives v²f″ = v²f″. Standing wave 2A sin(kx)cos(ωt); fixed ends ⇒ f_n = nv/2L.** CONFIRMED via chain rule and sum-to-product identity.
8. **Square-wave Fourier series (4/π)[sin + (1/3)sin3 + (1/5)sin5 + …]; odd harmonics, 1/n falloff; Gibbs overshoot.** CONFIRMED — standard result.
9. **Decibel β = 10 log₁₀(I/I₀); 0.656 Pa → I ≈ 5.04×10⁻⁴ W/m² → ≈ 87 dB; +3 dB per doubling; guitar v = √(56.4/3.09e−4) ≈ 427 m/s, f₁ ≈ 329 Hz (E4).** CONFIRMED. 10·log₁₀(5.04×10⁸) = 10·8.70 ≈ 87 dB ✓; √(56.4/3.09e−4)=√182524≈427 ✓; 427/1.30≈328.5 Hz ≈ E4 ✓.

## Unverified Assertions

| Assertion | Reason | Disposition |
|-----------|--------|-------------|
| (none) | — | — |

## AI-Pass Flags

None. All on-page derivations and numerical results check out.
