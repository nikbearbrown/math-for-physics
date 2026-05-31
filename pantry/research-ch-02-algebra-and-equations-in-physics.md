# Research: Chapter 02 — Algebra and Equations in Physics
## Mathematics for Physics
**Chapter one-line:** Rearranging/solving equations, ratios and proportionality, scaling laws, solving symbolically before substituting numbers, and carrying units through algebra.
**Research date:** 2026-05-30

---

## 1. Primary Sources

### Foundational papers and texts
- **Galileo Galilei, *Dialogues Concerning Two New Sciences* (1638) — the square–cube law.** The historical birthplace of *scaling-law reasoning*: for similar shapes, area ∝ L², volume (and weight) ∝ L³, so strength (∝ cross-section ∝ L²) cannot keep up with weight as size grows. Galileo's argument that "Nature cannot produce a giant ten times taller" is the cleanest possible motivation for proportional/scaling reasoning *as algebra*, and it predates calculus — perfect for a Part-I algebra chapter. See M. A. Peterson, "Galileo's Discovery of Scaling Laws," *Am. J. Phys.* (2002) for the careful history.
- **Eugene T. Torigoe & Gary E. Gladding, "Symbols Are Not Numbers: Are You Sure You Know What Numbers Help Students Do?" and related work (e.g., arXiv:1508.00535; arXiv:1112.3229 "How numbers help students solve physics problems," 2011).** The key empirical result for this chapter's thesis: intro-physics students perform **substantially worse on symbolic problems than on numerically identical ones**, and the gap traces to a *misunderstanding of variables*, not arithmetic. Direct evidence that "solve symbolically first" is a hard, teachable skill — and the right thing to teach.
- **Tourniaire & Pulos, "Proportional reasoning: A review of the literature," *Educational Studies in Mathematics* 16 (1985); S. Lamon, "Rational numbers and proportional reasoning" (in NCTM/Lester *Handbook*, 2007).** The foundational and the modern review of how proportional reasoning is learned and mis-learned. Establishes that proportional reasoning is a *developmental milestone*, not automatic, and catalogs the erroneous strategies (esp. additive-instead-of-multiplicative) students bring to ratio problems.
- **D'Arcy Wentworth Thompson, *On Growth and Form* (1917).** Extends Galileo's scaling into biology (allometry). Useful for §6 (where it generalizes) — shows the same algebra of proportionality governing bone thickness, metabolic rate, and beam strength.

### Key empirical cases
- **The additive-strategy error in a recipe/scaling problem (documented PER/math-ed finding).** Students asked "if 3 items cost \$12, what do 5 cost?" frequently *add* (12 + 2) rather than *scale* (×5/3). Canonical worked example for "proportionality is multiplicative." (Tourniaire & Pulos.)
- **Solving the inclined-plane / two-block Newton system symbolically.** From source ch.06/07: a block on an incline, or an Atwood/connected-masses system — set up ΣF = ma for each body, then *solve for a symbolically* before plugging numbers, and check limiting cases (e.g., θ→0, θ→90°). The chapter's central worked example: the symbolic answer *tells you something* the number cannot.
- **Static equilibrium of a beam (source ch.13).** ΣF = 0 and Στ = 0 give two linear equations in two unknown support forces; isolate one variable, back-substitute. A clean "rearrange a multi-term relation" case (and a bridge to Ch.10, linear systems).

---

## 2. The Core Concept — State of the Field

### What is settled
- The algebra is settled mathematics: linear equations have a determined solution structure; an equation is a constraint you may operate on identically on both sides; proportionality y = kx is the simplest non-trivial relation and underlies all power-law scaling y = kxⁿ.
- Scaling laws (area ∝ L², volume ∝ L³, and their consequences) are exact geometric facts.
- The PER finding that **symbolic problems are harder than numeric ones for novices** is well replicated.

### What is disputed (pedagogy)
- **Whether to teach "solve symbolically first" early or let students start numeric.** Some argue numbers scaffold meaning for novices (Kuo, Hull, Gupta, Elby — "blending" research) and symbolic competence should be built gradually; the book's thesis (symbol-first, units-in-the-algebra) takes a side and should defend it.
- **How to teach proportional reasoning** — ratio-table vs. unit-rate vs. cross-multiplication — is an active math-ed debate; cross-multiplication is criticized as a memorized procedure that hides the multiplicative structure.

### What has changed recently (last 5 years)
- Growing PER emphasis on **"blended" symbolic-conceptual reasoning** (treating an equation as a story about the physical situation, e.g., reading 1/(1/a + 1/b) as "smaller than either") rather than pure symbol-pushing. Recent work (2018–2023, Kuo et al. and successors) frames expertise as *opportunistic* blending — a useful frame for the chapter.
- No mathematical change; this is a stable-math chapter. The novelty is pedagogical and AI-driven: solvers (Wolfram Alpha, LLMs) now do the symbol-pushing, which *raises* the value of knowing what to set up and how to read the result.

---

## 3. Application Domain Examples (mechanics / waves)
1. **Inclined-plane acceleration, solved symbolically:** a = g(sinθ − μcosθ); read off the *condition* for sliding (tanθ > μ) directly from symbols. (Source ch.07.)
2. **Connected masses (Atwood):** a = (m₂ − m₁)g/(m₁+m₂); check limits m₁=m₂ (a=0) and m₁=0 (a=g). (Source ch.06.)
3. **Period of a spring, T = 2π√(m/k):** proportional reasoning — quadruple m, period doubles; the *scaling* is the insight, no number needed. (Source ch.17.)
4. **Square–cube / why big animals have thick legs:** strength ∝ L², weight ∝ L³, so stress ∝ L. The algebra of why elephants can't have gazelle-proportioned legs. (Galileo; source ch.13 elasticity.)
5. **Kinetic energy vs. speed:** KE ∝ v², so doubling speed quadruples stopping distance — a proportionality students routinely get wrong by reasoning additively. (Source ch.08.)

---

## 4. The Book's Thesis Connection
This is the chapter where the thesis is *most testable*, because the Torigoe result is direct evidence that the plug-and-chug habit is actively harmful: students who can do the numeric version fail the symbolic one, which means they don't actually understand the relation — they understand the arithmetic. The transferable skill is **manipulating relations among quantities and reading the result** — which is exactly what no calculator and (in spirit) no solver does *for* you. A solver will return a = g(m₂−m₁)/(m₁+m₂); it will not *tell you* that the system is stationary when the masses are equal, or that doubling speed quadruples energy. That interpretive reading — taking limits, checking units, seeing the proportionality — is the human skill, and it is general (it works in chemistry kinetics, in finance, anywhere relations among quantities appear). "Learn the math, not the plug-and-chug" is almost the literal moral of the PER literature here.

---

## 5. The AI Wayback Machine — Candidate Figures
Algebra/equation-solving is ancient and global — strong opportunity for genuine non-Western and women figures:
- **Muhammad ibn Musa al-Khwarizmi** (Persian mathematician, c. 780–850; Wikipedia: "Al-Khwarizmi"). Literally gave us *al-jabr* (the word "algebra") and the systematic method of *balancing* and *completing* equations — the exact operation this chapter teaches (do the same thing to both sides). Non-Western, foundational, undergrad-accessible. Strong lead.
- **Diophantus of Alexandria** (Greek, c. 200–284; Wikipedia: "Diophantus"). Early symbolic notation and equation-solving (*Arithmetica*). Good for the "symbols before numbers" theme.
- **Mary Everest Boole** (English mathematician/educator, 1832–1916; Wikipedia: "Mary Everest Boole"). Wrote on *how* algebra is learned and on making symbolic reasoning intuitive — a defensible woman figure tied specifically to the *pedagogy of algebra* (and a lesser-known one). If the book wants a woman who worked on this exact topic, she fits better than forcing a name.

**Demographic note:** al-Khwarizmi gives genuine non-Western representation; Boole gives a woman tied to algebra learning. Recommend al-Khwarizmi as primary (the etymology lesson "algebra = al-jabr = restoring/balancing" is a gift for this chapter), Boole as the diversity pairing. *Anchor prompt:* "Al-Khwarizmi (circa 820, Persian mathematician in Baghdad's House of Wisdom) — robed scholar at a writing desk, geometric equation diagrams and an astrolabe nearby, historically plausible editorial portrait, period-appropriate clothing and workspace, no text, no watermark."

---

## 6. Pedagogical Delivery Research
**Prior knowledge:** arithmetic with fractions, the equals sign as a *balance* (not "compute the answer"), basic exponent rules. **Documented misconceptions:**
- The **additive bug** in proportional reasoning — scaling treated as adding a constant difference (Tourniaire & Pulos; Lamon). The single most-documented error this chapter must confront.
- **Equals-sign-as-operator** misconception (carried from arithmetic): "=" read as "produces" rather than "is equivalent to," which blocks legitimate two-sided manipulation.
- **Symbol-as-label vs. symbol-as-quantity** confusion (Torigoe): students treat letters as object-labels ("m for meters") rather than varying quantities, which is why symbolic problems fail.
- **Power-law intuition failure:** v² relations reasoned about linearly.

**Sequences shown to work:** (1) teach proportionality *multiplicatively* via unit-rate/ratio-table, never cross-multiplication-as-ritual; (2) demand symbolic solution *then* substitution, and explicitly practice *reading* the symbolic result (limits, units, proportionalities) — this is the skill, not a formality; (3) make units travel through every line of algebra so a units-mismatch flags an error. **Failure mode:** letting students substitute numbers immediately, which (per Torigoe) lets them succeed without understanding, then collapse on transfer. **Understanding vs. memorizing:** the student who can take the limit of a symbolic answer understands the relation.

---

## 7. Representation and Display Research
- **A "solve-it-symbolically" worked-derivation block** — the inclined-plane or Atwood solution shown line-by-line with units carried through and limiting cases annotated in the margin.
- **A ratio table / scaling diagram** — e.g., doubling an animal's size, with area (×4) and volume (×8) shown visually (nested cubes) to make the square–cube law concrete.
- **A proportionality vs. additive-bug contrast figure** — two solution paths to the same ratio problem, one correct (×) one wrong (+), to surface the misconception.
- **A units-as-algebra table** — showing units cancelling line by line in a multi-step solve.

## 8. Open Questions and Research Gaps
- The symbol-first-vs-numbers-first pedagogy is genuinely contested; the book takes the symbol-first side and should acknowledge the "numbers scaffold meaning" counter-evidence (Kuo et al.) rather than ignore it.
- Much proportional-reasoning research is on K–12 / pre-service teachers; transfer to the calc-physics population is plausible but the cited reviews aren't specific to that cohort — flag as indicative.
- No aging risk (stable math).

## 9. Sourcing Notes
- Galileo (1638) is primary; rely on Peterson (2002, *Am. J. Phys.*) for the careful modern reading.
- Torigoe/Gladding and Tourniaire & Pulos are peer-reviewed and directly on point; Torigoe's strongest statements appear partly in conference/arXiv form — solid but cite the published versions where possible.
- al-Khwarizmi attribution is uncontroversial; the specific "balancing" reading of *al-jabr* is well established.
