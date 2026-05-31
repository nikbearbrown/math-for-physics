# Research: Chapter 01 — Units, Dimensions, and Estimation
## Mathematics for Physics
**Chapter one-line:** SI units, dimensional analysis, significant figures, error/uncertainty propagation, order-of-magnitude estimation — the math of *quantity itself*.
**Research date:** 2026-05-30

---

## 1. Primary Sources

### Foundational papers and texts
- **Edgar Buckingham, "On Physically Similar Systems; Illustrations of the Use of Dimensional Equations," *Physical Review* 4, 345 (1914).** The paper that gave the π-theorem its modern, usable form and the name "Π" for the dimensionless groups. Buckingham's central claim is the load-bearing math of this chapter: any physically meaningful equation relating *n* dimensioned variables built from *k* independent base dimensions can be rewritten as a relation among exactly *n − k* dimensionless products. This is the precise statement of "dimensional consistency as an equation constraint." Use the *count* (n − k) as the chapter's punchline, not just "units must match."
- **Lord Rayleigh (J. W. Strutt), *The Theory of Sound* (1877), and his "method of dimensions."** Rayleigh used dimensional reasoning from ~1872 (famously to argue why the sky is blue — scattering ∝ 1/λ⁴) and codified the technique. His method is the elementary "assume a power-law product, solve for the exponents by matching dimensions" approach that an intro reader can actually execute by hand — the right level for this book, with Buckingham as the formal backstop.
- **A. Vaschy (1892), and independently A. Federman / D. Riabouchinsky (1911); the theorem first proved by Joseph Bertrand (1878).** Provenance note worth stating honestly in the book: the "Buckingham" π-theorem predates Buckingham. Bertrand proved special cases (electrodynamics, heat conduction) in 1878; Vaschy gave a general statement in 1892. This is a clean teachable example of how mathematical results get named for the popularizer, not the originator.
- **BIPM, *The International System of Units (SI)*, 9th edition (2019), and NIST Special Publication 330 (2019), the US edition of the same text.** The authoritative, current definition of every base unit. As of 2019 all seven base units are fixed by exact numerical values of defining constants (c, h, e, k, N_A, ΔνCs, K_cd). This is the chapter's modern anchor and its *aging risk* — see §8.
- **B. N. Taylor & C. E. Kuyatt, *Guidelines for Evaluating and Expressing the Uncertainty of NIST Measurement Results*, NIST Technical Note 1297 (1994), and the *GUM* (Guide to the Expression of Uncertainty in Measurement, JCGM 100:2008).** The authoritative source for how uncertainty is actually propagated in metrology — the "law of propagation of uncertainty" (add relative uncertainties in quadrature for products/quotients) that the chapter must derive in its simplified form.

### Key empirical cases
- **Mars Climate Orbiter (1999) — the unit-mismatch loss.** Lockheed Martin's `SM_FORCES` software reported impulse in pound-force-seconds (lbf·s); JPL navigation expected newton-seconds (N·s). The missing factor of 4.448 left the orbiter ~100 km too low; it broke up in the Martian atmosphere. ~$327M mission. The canonical cold open (already in source ch.02) for "units are not decoration." Well documented in the NASA MCO Mishap Investigation Board report (1999).
- **The Grand K mass drift and the 2019 kilogram redefinition.** The international prototype kilogram (IPK, "le Grand K") drifted ~50 µg relative to its sister copies over ~a century — meaning the *definition* of mass was changing. Resolved by the Kibble (watt) balance, which ties mass to Planck's constant h (fixed at exactly 6.62607015 × 10⁻³⁴ J·s). A documented, dramatic case of *why* you anchor units to constants. (Source ch.02 already uses this.)
- **Fermi's atomic-bomb-yield estimate, Trinity test (16 July 1945).** Enrico Fermi dropped scraps of paper as the blast wave passed and estimated the yield from how far they blew — getting ~10 kilotons, the right order of magnitude. The canonical order-of-magnitude / "Fermi problem" anecdote. Documented; widely retold. Good worked-example seed for the estimation section.

---

## 2. The Core Concept — State of the Field

### What is settled
- The π-theorem is a proven, exact theorem of linear algebra: write each variable's dimensions as a vector of exponents over the base dimensions; the dimensionless groups are the null space of the resulting matrix. n − k is the nullity. This is not in dispute.
- SI is defined (since 2019) by exact constants. The numerical values are *fixed by definition*, not measured.
- Propagation of uncertainty to first order: for a quantity *q = A·B/C*, relative uncertainties add in quadrature (independent errors) or linearly (worst-case bound). For *q = Aⁿ*, the relative uncertainty multiplies by |n|. Settled and derivable from the differential dq = (∂q/∂x)dx + ….

### What is disputed (pedagogy / convention, not math)
- **Significant figures vs. explicit uncertainty.** Many metrology educators argue sig-figs are a crude proxy for relative uncertainty and that students should be taught explicit ± uncertainty instead; others defend sig-figs as a fast, teachable error-propagation heuristic. The book should present sig-figs as *what they actually are* — a coarse encoding of relative uncertainty — not as a ritual.
- **Whether angle (radian) is dimensionless.** A live convention debate (some metrologists argue the radian should be a base unit). Relevant when the book later links to trig/Ch.3. For Ch.1, note that "dimensionless" groups can still carry meaning.
- **Worst-case (linear) vs. statistical (quadrature) uncertainty combination** — both are taught; the choice depends on whether errors are independent.

### What has changed recently (last 5 years)
- The **2019 SI redefinition** (effective 20 May 2019) is the big recent shift: every base unit now flows from fixed constants. Any text written before 2019 is now wrong on the kilogram, ampere, kelvin, and mole definitions.
- **CODATA 2022 adjustment** (released 2024) updated recommended values of the *non-fixed* constants (e.g., G, electron mass). The defining constants (c, h, e, k, N_A) are exact and will not change; the *measured* ones still get revised — a point worth flagging (§8).

---

## 3. Application Domain Examples (mechanics / waves)
1. **Dimensional check of a kinematic formula.** Given a proposed s = ½at², verify [m] = [m/s²][s²] = [m]. The fast error-catcher; show a *wrong* candidate (e.g., s = ½at) failing the check. (Source ch.04 kinematics.)
2. **Period of a pendulum from dimensions alone.** Variables: T, length L, g, mass m. Base dims give n − k = 4 − 3 = 1 dimensionless group ⇒ T ∝ √(L/g). Dimensional analysis delivers the *form* of the answer (up to the constant 2π) before any calculus. A spectacular preview of the SHM result in Ch.11/13. (Source ch.17.)
3. **Drag / terminal velocity scaling.** Drag force ~ ρv²A gives, by dimensions, how terminal speed scales with size — connects to Fermi estimation of falling objects. (Source ch.07.)
4. **Uncertainty in a density measurement.** ρ = m/V; V from a measured radius (V ∝ r³). Propagate: relative uncertainty in ρ = relative in m + 3×(relative in r). Concrete payoff of the "powers multiply relative error" rule. (Source ch.15 fluids / ch.02.)
5. **Order-of-magnitude: how many air molecules in this room / Fermi-style yield estimate.** Estimation as a first-class mathematical skill. (Source ch.02, ch.15.)

---

## 4. The Book's Thesis Connection
This chapter is where the book earns its thesis most cleanly, because dimensional analysis is *pure transferable math* that happens to be taught in physics. The π-theorem is a linear-algebra fact (null space of an exponent matrix); it applies identically to economics, biology (allometric scaling), and machine learning (non-dimensionalizing a loss). What a solver/AI **cannot** supply: the *choice of relevant variables*. The theorem only tells you n − k groups exist once you've decided which n quantities matter — and choosing them (does mass matter for the pendulum? no) is physical judgment, not computation. That is the irreducible human step. Likewise, a calculator reports 11 digits; deciding the answer is good to 2 sig-figs because your ruler is, is judgment about *what you actually know*. "Learn the math, not the plug-and-chug" holds strongly here: the *rules* (matching exponents, quadrature) are mechanical; the *setup and the reading of the result* are the whole skill.

---

## 5. The AI Wayback Machine — Candidate Figures
Goal: someone who *worked on this math*. The honest difficulty: the named originators of dimensional analysis are all Western men. Candidates:
- **Aimé Vaschy** (French engineer/mathematician, 1857–1899; Wikipedia: "Aimé Vaschy"). The true general originator of the π-theorem (1892), decades before Buckingham. Lesser-known, undergrad-accessible, and a built-in lesson about misattribution. *Anchor prompt:* "Aimé Vaschy (circa 1892, French telegraph engineer and mathematician) — late-nineteenth-century man in formal coat, dimensional equations and telegraph apparatus nearby, historically plausible editorial portrait, period-appropriate clothing and workspace, no text, no watermark."
- **Joseph Bertrand** (French mathematician, 1822–1900; Wikipedia: "Joseph Bertrand"). First proved special cases of the theorem (1878). Connects dimensional analysis to mainstream 19th-c. analysis.
- **Hertha Marks Ayrton** (British engineer-physicist, 1854–1923; Wikipedia: "Hertha Ayrton"). NOT a dimensional-analysis originator, but did genuine *quantitative measurement* work (electric arc, sand ripples) deriving empirical scaling laws — a defensible woman-in-measurement choice if the book wants demographic balance and is honest that her connection is to *measurement and scaling laws* rather than the π-theorem itself. (She is already slated for source ch.17.)

**Demographic-skew flag:** the genuine originators here are uniformly white European men. The book's existing ch.02 wayback uses **Henrietta Swan Leavitt** (period–luminosity law — a measured scaling relation), which is a strong, honest woman-in-measurement pick and may be the better choice for diversity than forcing a dimensional-analysis name. Recommend: lead with **Vaschy** for the misattribution lesson, keep **Leavitt** as the diversity anchor, note the skew explicitly.

---

## 6. Pedagogical Delivery Research
**Prior knowledge required:** scientific notation, powers of 10, basic algebra, unit cancellation as algebra. **Documented misconceptions (PER):**
- Students believe measurements are *exact* and that "error" is a personal mistake to be eliminated by care, rather than an intrinsic feature of measurement (Phys. Rev. PER 20.020105 (2024); UNC Deardorff findings).
- Students apply sig-fig *rules* mechanically without knowing they encode relative uncertainty; most textbooks never explain the rationale (arXiv:2412.15382, 2024).
- Students drop uncertainties when averaging, and fail to identify the *dominant* error source.
- First-year students cannot do Fermi/order-of-magnitude problems on arrival; the skill must be *explicitly taught* (sub-divide, estimate each factor, recombine). Once taught, strong students transfer it well (Phys. Educ. 2008, "Don't just stand there — teach Fermi problems!").

**Sequences shown to work:** teach uncertainty *as relative uncertainty first*, then reveal sig-figs as its shorthand; teach dimensional analysis by deriving a *form* (pendulum) so students see it produce a result, not just check one. **Failure mode:** presenting sig-figs and units as bureaucratic ritual divorced from meaning. **Understanding vs. memorizing:** the student who *derives* T ∝ √(L/g) understands; the one who memorizes "round to 3 figures" does not.

---

## 7. Representation and Display Research
This chapter needs:
- **A dimensional-analysis table** — rows = quantities (T, L, g, m), columns = base dimensions (M, L, T), entries = exponents; show the exponent matrix and how solving it yields the dimensionless group. This *is* the π-theorem made visible.
- **An SI base-unit table** — seven base units, each with its defining constant and exact value (post-2019), flagged as the current-definition snapshot.
- **A sig-figs / relative-uncertainty correspondence diagram** — a number line or bar showing how "3 sig figs" maps to ~±0.5% relative uncertainty; makes the encoding explicit.
- **An error-propagation flow** for a product (ρ = m/V): boxes for input relative uncertainties combining (in quadrature) into the output.

---

## 8. Open Questions and Research Gaps
- **Aging risk (high).** The exact constant values (h = 6.62607015×10⁻³⁴ J·s, etc.) are *fixed* and safe. But any *measured* constant (G, particle masses) updates with each CODATA cycle (CODATA 2022 released 2024; next ~2026–2027). The book should cite the SI brochure 9th ed. and note "current as of CODATA 2022."
- **Sig-fig pedagogy is genuinely contested** — present it as a convention with a rationale, not law.
- **Radian-as-base-unit debate** is unresolved in metrology; touch lightly, defer to Ch.3.
- The Fermi-Trinity yield anecdote is well attested but the *exact* paper-strip number Fermi cited varies across retellings — label the precise figure as approximate.

## 9. Sourcing Notes
- BIPM SI brochure and NIST SP 330 are primary and authoritative; use the 9th ed. (2019) directly.
- Buckingham 1914 is the primary paper; the Vaschy/Bertrand priority is well documented (Wikipedia + history-of-DA reviews) but original Vaschy 1892 text is French and harder to access — cite via secondary history if the original isn't reached.
- PER claims drawn from peer-reviewed Phys. Rev. PER and arXiv preprints (2024) plus an established UNC findings page — solid for pedagogy, but the arXiv item is a preprint (single-institution, Canadian); treat as indicative, not definitive.
- MCO and Grand-K cases are well documented in primary investigation/standards reports.
