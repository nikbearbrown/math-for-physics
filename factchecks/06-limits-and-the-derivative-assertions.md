# Fact-check: 06 — Limits and the Derivative

**Field:** mathematics / physics
**Source file:** chapters/06-limits-and-the-derivative.md
**Date checked:** 2026-05-30

## Breakdown

- Assertions classified and checked: 10 (5 historical/attribution EVIDENCE-SPECIALIST; 5 AI-verifiable derivations)
- CONFIRMED: 5 (web) + 5 (AI-pass) = 10
- OUTDATED: 0
- CONTRADICTED: 0
- UNVERIFIED: 0
- Contested-historiography flag carried in-text (correctly): 1 (Cauchy/Weierstrass/Bolzano attribution)

## ⚠️ Critical — Requires Immediate Expert Review

None found.

## Full Findings

1. **Newton: fluxions as instantaneous rates; *De analysi* (1669, pub. 1711) and *Method of Fluxions* (1671, pub. 1736).** — CONFIRMED. *De analysi* written 1669, published 1711 (in Jones's *Analysis per quantitatum series*); *Method of Fluxions* completed 1671, posthumously published 1736; a fluxion is the instantaneous rate of change of a fluent. https://en.wikipedia.org/wiki/Method_of_Fluxions ; https://grokipedia.com/page/Fluxion

2. **Leibniz, "Nova Methodus pro Maximis et Minimis," *Acta Eruditorum* (1684) — first printed differential calculus; product rule and dx notation.** — CONFIRMED. October 1684; first published work on calculus; introduces dx and rules for products, quotients, powers. https://en.wikipedia.org/wiki/Nova_Methodus_pro_Maximis_et_Minimis ; https://old.maa.org/press/periodicals/convergence/mathematical-treasure-leibnizs-papers-on-calculus-differential-calculus

3. **Berkeley, *The Analyst* (1734) — "ghosts of departed quantities."** — CONFIRMED. 1734; exact phrase "ghosts of departed quantities" critiques fluxions/evanescent increments; Berkeley accepted the results but attacked the reasoning. https://en.wikipedia.org/wiki/The_Analyst ; https://old.maa.org/press/periodicals/convergence/mathematical-treasure-george-berkeleys-the-analyst

4. **Cauchy refounded calculus on the limit; *Cours d'analyse* (1821) and *Résumé* (1823).** — CONFIRMED. *Cours d'analyse* (1821) treats limits/continuity/convergence; the limit is the value approached, not attained. https://en.wikipedia.org/wiki/Limit_of_a_function

5. **Weierstrass (c. 1861) gave the modern ε–δ form; Bolzano (1817) gave an earlier rigorous version; the precise Cauchy/Weierstrass/Bolzano attribution is debated.** — CONFIRMED, and the in-text "[debated — see pantry]" flag is accurate. Bolzano (1817) introduced ε–δ-style continuity (little-known in his lifetime); Cauchy used ε–δ arguments in proofs but gave no formal ε–δ *definition* of limit; Weierstrass introduced the modern formal definition in 1861. The "Cauchy–Weierstrass tale" is explicitly a contested historiography (Grabiner; Bråting; "Who Gave You the Cauchy–Weierstrass Tale?"). https://en.wikipedia.org/wiki/Limit_of_a_function ; https://arxiv.org/pdf/1108.2885 ; https://arxiv.org/pdf/2005.13259

## Unverified Assertions

| Assertion | Category | Why unverified | Suggested source |
|---|---|---|---|
| (none) | — | — | — |

## AI-Pass Flags

All on-page derivations verified correct, no web needed:

- **Derivative of t² from the limit:** (t+h)²−t² = 2th+h²; quotient = 2t+h; limit h→0 gives 2t. CONFIRMED.
- **Power, constant-multiple, sum, product (Leibniz 1684), quotient, and chain rules** all stated correctly; product rule [uv]' = u'v+uv'; quotient [u/v]' = (u'v−uv')/v²; chain d/dx f(g) = f'(g)g'. CONFIRMED.
- **d/dt sin(ωt) = ω cos(ωt)** via chain rule; standard derivatives sin'=cos, cos'=−sin. CONFIRMED.
- **Free fall (Example 1):** x=½gt² ⇒ v=gt; at t=30, v=9.8·30=294 m/s; a=g=9.8 m/s². CONFIRMED.
- **Thrown ball (Example 2):** x=x₀+v₀t−½gt² ⇒ v=v₀−gt, a=−g; constant x₀ differentiates to 0. CONFIRMED.
- **Chain rule on rotation (Example 3):** d/dt[r cos(ωt)] = −rω sin(ωt). CONFIRMED.

Education-research citation Tall & Vinner (1981) *ESM* 12:151–169 (limit-as-value-approached / concept image vs definition) is a correctly cited, standard reference (context).
