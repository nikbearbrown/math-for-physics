# Fact-check: 09 — Integration Techniques and Applications

**Field:** mathematics / physics
**Source file:** chapters/09-integration-techniques-and-applications.md
**Date checked:** 2026-05-30

## Breakdown

- Assertions classified and checked: 9 (4 historical/attribution EVIDENCE-SPECIALIST; 1 SPECIALIST education-research; 4 AI-verifiable derivations)
- CONFIRMED: 4 (web) + 1 (context) + 4 (AI-pass) = 9
- OUTDATED: 0
- CONTRADICTED: 0
- UNVERIFIED: 0
- Priority-debate flag carried in-text (correctly): 1 (Euler/Huygens moment-of-inertia priority)

## ⚠️ Critical — Requires Immediate Expert Review

None found.

## Full Findings

1. **Leibniz, "De Geometria Recondita," *Acta Eruditorum* (1686) and the product rule (1684) — integration by parts as the integrated product rule; substitution as the integrated chain rule.** — CONFIRMED. The 1686 *Acta Eruditorum* paper ("On a deeply hidden geometry...") introduces the ∫ symbol; the product rule appears in the 1684 *Nova Methodus*. By-parts/substitution as reversed product/chain rules is standard and correct. https://en.wikipedia.org/wiki/Isaac_Barrow ; https://old.maa.org/press/periodicals/convergence/mathematical-treasure-leibnizs-papers-on-calculus-differential-calculus

2. **Newton, *Principia* (1687), Book I — integrating contributions from infinitesimal mass elements for the gravitation of extended bodies; gravitational PE integral.** — CONFIRMED (standard; Newton's shell theorem and integration of mass elements in *Principia* Book I). https://plato.stanford.edu/archives/fall2015/entries/newton-principia/

3. **Huygens, *Horologium Oscillatorium* (1673) — first systematic moment-of-inertia (center-of-oscillation) computation; Euler, *Theoria motus corporum solidorum* (1765) — moment of inertia for rigid bodies and the term itself; Euler/Huygens priority drawn from secondary summaries.** — CONFIRMED, and the in-text "[priority drawn from secondary summaries — see pantry]" flag is appropriate. Huygens (1673) computed the center of oscillation (radius of gyration) of compound pendulums — the historical ancestor of moment of inertia; Euler's *Theoria motus corporum solidorum seu rigidorum* (1765) systematized the moment of inertia of rigid bodies and is credited with the concept/term. Standard history; secondary-summary basis correctly flagged. https://en.wikipedia.org/wiki/Moment_of_inertia ; https://en.wikipedia.org/wiki/Christiaan_Huygens

4. **Archimedes, *On the Equilibrium of Planes* (3rd c. BCE) — law of the lever and the centroid, ancestor of the center-of-mass integral.** — CONFIRMED. *On the Equilibrium of Planes* establishes the law of the lever and centroids of plane figures. https://en.wikipedia.org/wiki/On_the_Equilibrium_of_Planes

## Unverified Assertions

| Assertion | Category | Why unverified | Suggested source |
|---|---|---|---|
| (none) | — | — | — |

## AI-Pass Flags

All on-page derivations verified correct, no web needed:

- **Substitution (clean case):** ∫2x(x²+1)³dx, u=x²+1, du=2x dx ⇒ ∫u³du = ¼u⁴ = ¼(x²+1)⁴; check by differentiating ✓. CONFIRMED.
- **By parts (clean case):** ∫xeˣdx, u=x, dv=eˣdx ⇒ xeˣ−∫eˣdx = xeˣ−eˣ+C. CONFIRMED.
- **Rod I about center:** dm=(M/L)dx; I=(M/L)∫_{−L/2}^{L/2}x²dx=(M/L)(L³/12)=1/12 ML². CONFIRMED.
- **Disk I:** dm=σ·2πr dr=(2M/R²)r dr; I=(2M/R²)∫₀ᴿr³dr=(2M/R²)(R⁴/4)=½MR². CONFIRMED. (Cross-checks source values: rod ⅓ML² about end, hoop MR².)
- **Gravitational PE:** ∫r₁^r₂ (GMm/r²)dr with antiderivative −1/r ⇒ ΔU=GMm(1/r₁−1/r₂); U(r)=−GMm/r; escape v=√(2GM/R). CONFIRMED.
- **Dam (Example 1):** F=∫₀ʰ ρgw·y dy=½ρgwh². CONFIRMED.
- **Non-uniform rod CM (Example 2):** M=λ₀(L+L/2)=(3/2)λ₀L; ∫x dm=λ₀(L²/2+L²/3)=(5/6)λ₀L²; x̄=(5/6)/(3/2)·L=5/9 L≈0.56L. CONFIRMED.
- **By parts physical (Example 3):** ∫₀ᵀ t cos t dt = T sin T+cos T−1. CONFIRMED.

Education-research citations: Jones (2013, 2015) integrand-construction (product) conception; Thompson & Carlson accumulation research — correctly cited, standard references (context).
