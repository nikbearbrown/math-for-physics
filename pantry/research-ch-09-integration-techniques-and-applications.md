# Research: Chapter 09 — Integration Techniques and Applications
## Mathematics for Physics
**Chapter one-line:** Substitution, integration by parts, integrating over distributions, and line integrals — the machinery that computes moment of inertia (∫r²dm), center of mass, gravitational potential energy, and fluid-pressure force.
**Research date:** 2026-05-30

---

## 1. Primary Sources

### Foundational papers and texts
- **Gottfried Wilhelm Leibniz, "De Geometria Recondita et Analysi Indivisibilium atque Infinitorum" (*Acta Eruditorum*, 1686) and the product rule (1684).** Integration by parts is the integral form of Leibniz's product rule d(uv) = u dv + v du, rearranged and integrated: ∫u dv = uv − ∫v du. Substitution is the integral form of the chain rule. The chapter's two main techniques are the two main differentiation rules read backwards — a clean demonstration of the FTC's inverse-operation logic from Ch. 08.
- **Isaac Newton, *Principia* (1687), Book I.** Newton computed gravitational attraction of an extended body by integrating contributions from infinitesimal mass elements — the prototype of ∫(...)dm over a distribution, and the source of the gravitational-PE integral the chapter derives.
- **Christiaan Huygens, *Horologium Oscillatorium* (1673).** Introduced and computed the moment of inertia and center of oscillation for the compound pendulum — the first systematic ∫r²(...) distribution integral in mechanics. The historical origin of the chapter's ∫r²dm.
- **Leonhard Euler, *Theoria motus corporum solidorum* (1765).** Defined the moment of inertia tensor and computed ∫r²dm for rigid bodies systematically; coined the term "moment of inertia." The direct ancestor of the rod/disk derivations.
- **Archimedes, *On the Equilibrium of Planes* (3rd c. BCE).** The law of the lever and the centroid — the ancient origin of the center-of-mass integral x̄ = (1/M)∫x dm.

### Key empirical cases
- **Moment of inertia of a uniform rod and disk, I = ∫r²dm (source ch. 11).** Rod about its center: I = (1/12)ML²; disk about its axis: I = ½MR². The canonical distribution-integral worked examples; require choosing dm = λ dx (rod) or dm = σ·2πr dr (disk) — the modeling step.
- **Gravitational potential energy, U(r) = −∫F·dr = −GMm/r (source ch. 14).** Integrating the inverse-square force from r to infinity; a substitution/power-rule integral whose *sign and limits* carry all the physics.
- **Force on a dam / submerged wall, F = ∫p dA = ∫ρg·y·(width)dy (source ch. 15).** Pressure increases linearly with depth, so the total force is an integral over depth — a distribution integral where the integrand itself varies with position.

---

## 2. The Core Concept — State of the Field

### What is settled
Substitution (∫f(g(x))g'(x)dx = ∫f(u)du), integration by parts (∫u dv = uv − ∫v du), the setup of distribution integrals (∫(...)dm, ∫(...)dA, ∫(...)dV with the appropriate density), the line integral ∫F·dr, and the standard results (I_rod = ML²/12, I_disk = MR²/2, U_grav = −GMm/r, F = ρgh̄A for a flat submerged plate) are all completely settled. None is mathematically contested at this level.

### What is disputed
Pedagogy and heuristics only:
- **How to teach the *choice* in integration by parts.** The LIATE rule (Logarithmic, Inverse-trig, Algebraic, Trig, Exponential — pick u in that priority order) is a widely taught heuristic, but it is a rule of thumb, not a theorem, and over-reliance on it is debated; some argue it short-circuits the understanding of *why* one choice simplifies and another worsens the integral.
- **Setting up dm: the genuine difficulty.** Physics-education and math-ed researchers agree the hard part of distribution integrals is *not* the integration but expressing dm in terms of the integration variable (dm = λ dx, dm = σ dA, dm = ρ dV) and choosing the right coordinate/slice. This is a modeling skill the technique itself doesn't supply.
- **When the path matters (line integrals).** For conservative forces ∫F·dr is path-independent (Ch. 09 source establishes this for gravity/springs); for non-conservative forces it is not. Whether to teach path-independence here or defer is a sequencing choice.

### What has changed recently (last 5 years)
Mathematics is fixed; aging risk near zero. The live edge is the same product/accumulation research from Ch. 08 (Jones; Thompson & Carlson; the 2025 "modeling with quantities" framework): the dominant finding is that students can execute substitution and parts mechanically but fail at *constructing the integrand* (the r²dm, the ρg·y·width·dy) — the setup, not the technique, is where learning breaks. This is the most current and most relevant lens for an applications chapter.

---

## 3. Application Domain Examples (mechanics/waves)
1. **Moment of inertia of a thin rod about its center (source ch. 11).** dm = (M/L)dx; I = ∫_{−L/2}^{L/2} x²(M/L)dx = ML²/12. The cleanest distribution-integral, showcasing the dm-setup step and a symmetric limit.
2. **Moment of inertia of a uniform disk (source ch. 11).** Slice into rings: dm = σ·2πr dr with σ = M/(πR²); I = ∫₀ᴿ r²σ·2πr dr = ½MR². Demonstrates choosing the *right slice* (ring, not strip) — the modeling judgment.
3. **Gravitational potential energy from the inverse-square law (source ch. 14).** U(r) = −∫_∞^r (−GMm/r'²)dr' = −GMm/r; a power-rule integral whose limits (from infinity) and sign encode "bound system, negative energy." Leads to escape velocity v_esc = √(2GM/R).
4. **Hydrostatic force on a dam (source ch. 15).** p = ρgy; F = ∫₀ʰ ρgy·w dy = ½ρgwh² for a rectangular wall — total force as the integral of a depth-varying pressure. Pure accumulation of a varying integrand.
5. **Center of mass of a non-uniform rod (source ch. 09/11).** x̄ = (1/M)∫x dm with variable density λ(x); the integral as a weighted average. A natural substitution example when λ is, say, λ₀(1 + x/L).

---

## 4. The Book's Thesis Connection
This is the chapter where the "math as transferable tool" thesis pays off most concretely: *one* setup move — "slice the object into infinitesimal pieces, write what each piece contributes, integrate" — computes a spinning body's inertia, a planet's binding energy, a dam's load, and a beam's center of mass. The techniques (substitution = chain rule backwards, parts = product rule backwards) are revealed as the inverse of the derivative rules from Ch. 06, closing the calculus arc. The reader leaves able to set up *any* "sum over a continuous distribution" — in statistics (expected value), in economics (consumer surplus), in EM (charge distributions) — with the same move.

**What the student must supply that a solver cannot:** the *integrand and the limits* — i.e., the entire physical model. A symbolic engine computes ∫r²σ·2πr dr or ∫u dv flawlessly. It cannot decide to slice the disk into *rings* rather than strips, write dm = σ·2πr dr, recognize that gravitational PE integrates from infinity with a sign convention, or that pressure force needs the *width as a function of depth* for a non-rectangular dam. Even the technique *choice* — substitution here, parts there, LIATE as a hint — is a pattern-recognition judgment the solver can imitate but the student must own to set the problem up at all. The chapter's lesson: integration is mechanical; *deciding what the integral is* is the physics, and that is the human's. This is the book's thesis at its sharpest — the solver finishes the problem the student must first construct.

---

## 5. The AI Wayback Machine — Candidate Figures
(Existing convention pairs the source chapters with Emmy Noether (ch.09), Sofya Kovalevskaya (ch.11), Chandrasekhar (ch.14), Marie Tharp (ch.15); for the *math* of integration techniques and distribution integrals:)

- **Leonhard Euler (1707–1783, Swiss).** Systematized the moment of inertia and integral mechanics; arguably history's most prolific user of these techniques. *Anchor prompt:* "Leonhard Euler (circa 1760, Swiss mathematician) — man in eighteenth-century coat and cap, moment-of-inertia and integral notation nearby, historically plausible editorial portrait, face-centered, period-appropriate, accurate to known portraits, no text, no watermark." *Skew flag:* heavily portrayed European male; over-canonical.
- **Maria Gaetana Agnesi (1718–1799, Italian).** Author of the first textbook to treat integral calculus systematically (*Instituzioni analitiche*, 1748); an early woman teaching exactly these techniques. (Also a candidate for Ch. 06 — use in whichever chapter she is not placed.) *Anchor prompt:* "Maria Gaetana Agnesi (circa 1748, Italian mathematician) — woman in mid-eighteenth-century dress, integral-calculus textbook and area diagrams nearby, historically plausible editorial portrait, face-centered, period-appropriate, no text, no watermark." *Skew flag:* under-portrayed; strong diversity add.
- **Mary Cartwright (1900–1998, British) or Mary L. Boas (1917–2010, American).** Boas wrote *Mathematical Methods in the Physical Sciences* — the canonical "integration techniques for physicists" text — making her uniquely apt for an *applications* chapter and a modern under-portrayed woman who taught exactly this material. *Anchor prompt:* "Mary L. Boas (circa 1965, American physicist and author) — woman in mid-twentieth-century attire, mathematical-methods-for-physics notes and integral applications nearby, historically plausible editorial portrait, face-centered, period-appropriate, no text, no watermark." *Skew flag:* under-portrayed; American; mid-20th-c. — excellent fit and diversity, fewer reference images.

Demographics: recommend **Euler** (the systematizer) + **Mary L. Boas** (the modern physics-methods author, under-portrayed woman, uniquely on-topic for *applications*). Swiss/American, one male/one female; reserve Agnesi for Ch. 06 to avoid duplication. Lead the chapter image with Boas to offset the Euler over-canonical skew.

---

## 6. Pedagogical Delivery Research
- **Prerequisites:** the definite integral and FTC (Ch. 08); the differentiation rules — *especially* chain and product (Ch. 06), since substitution and parts are their inverses; the dot product and line-integral idea (Ch. 04, source ch. 08); density/distribution concepts.
- **Core misconception 1 — the setup (dm, dA, dV) is the hard part, not the integral.** The dominant finding across math-ed and physics-ed (Jones; the 2025 quantities framework): students execute techniques but cannot *construct the integrand*. For ∫r²dm they don't know how to express dm in terms of dr or dx. *Strongest understand-vs-memorize lever:* drill the slicing-and-dm step explicitly and separately from the integration arithmetic.
- **Core misconception 2 — choosing u and dv in integration by parts.** Documented student difficulty; LIATE helps but masks understanding. *Failure mode:* a poor choice (dv = the harder factor) makes the remaining integral *worse*, and students don't recognize they should restart. Remedy: derive parts from the product rule so the goal ("trade an integral you can't do for one you can") is visible, and treat LIATE as a hint, not a law.
- **Core misconception 3 — substitution mishandling limits.** Students change variables but forget to change the limits of integration (or forget to back-substitute). Remedy: show both methods (change-the-limits vs. back-substitute) and the bookkeeping each requires.
- **Core misconception 4 — sign and reference in PE integrals.** U = −∫F·dr; the negative sign and the choice of reference (U=0 at infinity for gravity, at equilibrium for springs) trip students. Source ch. 09/14 stress that only *differences* in PE matter. Remedy: derive the sign from the definition each time.
- **Sequence that works:** (1) substitution as chain-rule-backwards, on a clean example; (2) parts as product-rule-backwards, with LIATE as a hint; (3) the distribution-integral *setup* (slice → dm/dA/dV → integrand) as its own skill, on the rod; (4) harder slices (disk rings); (5) line integral and PE with sign/reference; (6) pressure-force integral. Lead with the setup skill, not the techniques, since that is where students fail.

---

## 7. Representation and Display Research
No special display required beyond standard figures, but slicing diagrams are essential. Recommended: (a) a rod with a single shaded slice dx at position x, labeled dm = λ dx and r = x — making the integrand construction visible; (b) a disk with a shaded *ring* dr at radius r, labeled dm = σ·2πr dr — showing why the slice is a ring, not a strip; (c) a dam cross-section with a horizontal strip at depth y, labeled dF = ρgy·w dy; (d) a force–displacement path for the line integral / PE. Every one of these figures targets the *setup* misconception by drawing the infinitesimal element explicitly.

---

## 8. Open Questions and Research Gaps
- Math-ed: the most effective way to teach the *integrand-construction* (dm/dA/dV) step — the documented failure point — is still being formalized; the 2025 "modeling with quantities" framework is recent and not broadly validated. The clearest live edge for this chapter.
- Whether LIATE helps or hinders deep understanding of integration by parts is genuinely contested.
- Aging risk: zero for the mathematics and the classical results; the only evolving element is the math-ed framing of integrand-construction difficulty.

---

## 9. Sourcing Notes
- **Strongest sources:** Leibniz's 1684/1686 *Acta Eruditorum* papers (techniques as inverse rules), Newton's *Principia* (distribution integration for gravity), Huygens' *Horologium* and Euler's *Theoria motus* (moment of inertia) are unimpeachable primaries. Jones's product-conception work and the Thompson/Carlson accumulation research are peer-reviewed math-ed primaries. The standard results (I_rod, I_disk, U_grav, dam force) are verified against the book's own source chapters 11, 14, 15.
- **Weaker/secondary:** LIATE's origin and status as heuristic, and the historical attributions for "moment of inertia" (Euler) and the centroid (Archimedes), were drawn from secondary/encyclopedic and pedagogical sources (Wikipedia "Integration by parts," tutorial sites, MAA materials) — verify Euler's coinage and Huygens' priority on moment of inertia against history-of-mechanics scholarship before stating firmly.
- **To verify before drafting:** Mary L. Boas's biographical details and dates for the wayback figure; the exact Jones citations (2013/2015) and the 2025 "modeling with quantities" paper before quoting; the precise dam-force result for non-rectangular geometries if used as an example.
- **Confidence:** high on the mathematics, the standard physics results, and the integrand-construction misconception research; medium on the fine historical attributions (Euler/Huygens/Archimedes) and on LIATE's pedagogical-debate framing.
