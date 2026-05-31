# Fact-check: 08 — The Integral

**Field:** mathematics / physics
**Source file:** chapters/08-the-integral.md
**Date checked:** 2026-05-30

## Breakdown

- Assertions classified and checked: 9 (4 historical/attribution EVIDENCE-SPECIALIST; 1 SPECIALIST education-research; 4 AI-verifiable derivations)
- CONFIRMED: 4 (web) + 1 (context) + 4 (AI-pass) = 9
- OUTDATED: 0
- CONTRADICTED: 0
- UNVERIFIED: 0
- Credit-split flag carried in-text (correctly): 1 (Cauchy/Riemann integral credit)

## ⚠️ Critical — Requires Immediate Expert Review

None found.

## Full Findings

1. **Riemann, "Über die Darstellbarkeit einer Function durch eine trigonometrische Reihe" (habilitation 1854; pub. 1867) — integral as limit of sums over partitions.** — CONFIRMED. Habilitation 1854; the Riemann integral is introduced in a preliminary section; posthumously published. (Title and 1854 date confirmed. Publication year: chapter says 1867; sources variously give 1867/1868 — Abhandlungen Göttingen vol. 13, dated 1867 on the volume / appearing 1868. Minor date variance only; the work and 1854 habilitation are correct.) https://en.wikipedia.org/wiki/Bernhard_Riemann ; https://www.exhibit.xavier.edu/oresme_2014Feb/2/

2. **Cauchy, *Résumé* (1823) — first rigorous definition of the integral as a limit of sums for continuous functions, and a version of the FTC; Riemann generalized Cauchy's construction.** — CONFIRMED. The *Résumé* (1823) gives the first rigorous treatment of differentiation and integration, including the integral as a limit of sums and the main theorems of calculus; Riemann later generalized it. The chapter's "[credit split summarized from secondary sources — see pantry]" flag is accurate. https://www.researchgate.net/publication/332193677_Cauchy's_Calcul_Infinitesimal ; https://digitalcommons.ursinus.edu/cgi/viewcontent.cgi?article=1011&context=triumphs_analysis

3. **Archimedes, *Quadrature of the Parabola* and *The Method* (3rd c. BCE) — method of exhaustion; area as a limit of approximating polygons.** — CONFIRMED. Archimedes used the method of exhaustion (inscribed/circumscribed polygons, triangles for the parabola) to find curved areas, anticipating the limit concept. https://en.wikipedia.org/wiki/Quadrature_of_the_Parabola ; https://en.wikipedia.org/wiki/Method_of_exhaustion

4. **Leibniz — ∫ symbol (1686) for *summa*; Barrow, *Lectiones Geometricae* (1670) — a geometric form of the FTC.** — CONFIRMED. Leibniz introduced ∫ (from *summa*) in his 1686 *Acta Eruditorum* paper; Barrow's *Lectiones Geometricae* (1670) contains a geometric statement of the inverse relationship between tangent and area problems (a geometric FTC). https://en.wikipedia.org/wiki/Isaac_Barrow ; https://arxiv.org/pdf/1111.6145

## Unverified Assertions

| Assertion | Category | Why unverified | Suggested source |
|---|---|---|---|
| (none) | — | — | — |

## AI-Pass Flags

All on-page derivations verified correct, no web needed:

- **Riemann sum → definite integral:** S_n = Σ f(x_k)Δx → ∫ₐᵇ f dx as n→∞. CONFIRMED.
- **FTC Part 1:** A(x)=∫ₐˣ f(t)dt ⇒ A(x+h)−A(x)≈f(x)h ⇒ A'(x)=f(x). CONFIRMED.
- **FTC Part 2:** A(x)=F(x)+C, A(a)=0 ⇒ C=−F(a) ⇒ ∫ₐᵇ f = F(b)−F(a). CONFIRMED.
- **Example 1:** ∫₀ᵀ at dt = [½at²]₀ᵀ = ½aT² (triangle area ½·T·aT). CONFIRMED.
- **Example 2 (spring):** ∫₀ˣ kx dx = ½kX². CONFIRMED.
- **Example 3 (impulse):** ∫F dt = ∫m dv = mv₂−mv₁ = Δp. CONFIRMED.

Education-research citations Sealey (2014) *J. Math. Behavior* 33:230–245 and Jones (2013, 2015) on the product/accumulation conception of integrals are correctly cited, standard references (context).
