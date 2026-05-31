# Fact-Check: Chapter 11 — Differential Equations and Oscillatory Motion

**Field:** Mathematics / Physics
**Source file:** chapters/11-differential-equations-and-oscillatory-motion.md
**Date checked:** 2026-05-30

## Breakdown

- Assertions classified: 8 (4 historical attributions; 4 on-page math derivations)
- Web-verified (historical): 4 — 3 CONFIRMED, 1 CONTRADICTED (date)
- AI-verified (math derivations): 4 — all CONFIRMED
- Flagged: 1 (CONTRADICTED — Bernoulli date)

## ⚠️ Critical Findings

- **Daniel Bernoulli's vibrating-string superposition is dated to the 1730s in the text; the documented date is 1741–43 (published 1751) and, as a formal statement of superposition, 1753.** The "1730s" is too early for the superposition claim. Flagged CONTRADICTED in both the body and the Sources list.

## Full Findings

### Historical attributions (web-verified)

1. **Newton, *Principia* (1687) — second law and fluxion notation; seed of the restoring-force equation.** CONFIRMED. Standard, uncontested attribution; the *Principia* (1687) states the second law. The "[verify]" marker can be resolved as CONFIRMED.

2. **Hooke, *Lectures de Potentia Restitutiva* (1678), "ut tensio sic vis" — linear force law F = −kx.** CONFIRMED. Hooke published the elasticity law in 1678 in *Lectures de Potentia Restitutiva* (originally encoded as the 1660 anagram "ceiiinosssttuv," solved as "Ut tensio, sic vis").
   URL: https://en.wikipedia.org/wiki/Hooke%27s_law

3. **Euler (1743, Euler Archive E62, *De integratione aequationum differentialium altiorum graduum*) — exponential substitution x = e^{rt} reducing a linear ODE to its characteristic equation.** CONFIRMED. E62 was published in *Miscellanea Berolinensia* 7 (1743), pp. 193–242, on integrating higher-order constant-coefficient differential equations — the standard origin of the characteristic-equation method. The chapter's "Euler in the 1740s" is correct.
   URL: https://scholarlycommons.pacific.edu/euler-works/62/

4. **Daniel Bernoulli "already used [superposition] on vibrating strings in the 1730s."** CONTRADICTED (on the date). Daniel Bernoulli's recognition of upper partial tones is a memoir of 1741–43 (published 1751); the explicit superposition statement ("The general motion of a vibrating system is given by a superposition of its proper vibrations") is dated by Brillouin to **1753**, the same year as his "Réflexions et éclaircissements." There is no documented 1730s vibrating-string superposition result. (Daniel Bernoulli did do hanging-chain oscillation work c. 1732–33, but that is not the superposition-of-harmonics claim the sentence makes.) The body text and Sources entry are flagged; the correct date is **1753** (with antecedents 1741–43).
   URL: https://en.wikipedia.org/wiki/Superposition_principle ; https://mathshistory.st-andrews.ac.uk/Biographies/Bernoulli_Daniel/

### Math derivations (AI-verified, no web)

5. **Separable decay: dN/dt = −λN ⇒ N(t) = N₀e^{−λt}; half-life t₁/₂ = ln2/λ.** CONFIRMED.
6. **x = A cos ωt + B sin ωt satisfies ẍ = −ω²x; release-from-rest ⇒ B = 0; T = 2π/ω = 2π√(m/k).** CONFIRMED by double differentiation.
7. **Characteristic equation mr² + br + k = 0; three damping regimes from discriminant b² − 4mk.** CONFIRMED.
8. **Worked numbers: ω = √(32/2) = 4 rad/s, T = 2π/4 ≈ 1.57 s; half-life 0.693/0.10 ≈ 6.93 yr; e^{−2} ≈ 0.135.** CONFIRMED.

## Unverified Assertions

| Assertion | Reason | Disposition |
|-----------|--------|-------------|
| (none) | — | — |

## AI-Pass Flags

None. All on-page derivations and numerical results check out. The only correction is the historical Bernoulli date (see Critical Findings).
