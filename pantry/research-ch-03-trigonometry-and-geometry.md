# Research: Chapter 03 — Trigonometry and Geometry
## Mathematics for Physics
**Chapter one-line:** Angles, the unit circle, sine/cosine/tangent, right-triangle decomposition, the laws of sines/cosines, radians — and the small-angle behavior that calculus and oscillations later depend on.
**Research date:** 2026-05-30

---

## 1. Primary Sources

### Foundational papers and texts
- **Ptolemy, *Almagest* (c. 150 CE), "table of chords."** The earliest surviving systematic trigonometric table (chords in a circle of diameter 120, ½° steps), building on the lost tables of **Hipparchus of Nicaea** (c. 150 BCE), the first to compile such a table. Establishes trigonometry's origin as *the math of relating an angle to a length* — exactly the chapter's job (magnitude-and-angle ↔ components). The chord is the historical ancestor of the sine.
- **Āryabhaṭa, *Āryabhaṭīya* (499 CE) — the first true sine table.** The Indian *Siddhāntas* and Āryabhaṭa redefined the function from *chord* (full) to *half-chord* (jyā/ardha-jyā) — i.e., the modern **sine**. The word "sine" itself is a mistranslation chain: jyā → Arabic *jiba* → misread as *jaib* (bosom/fold) → Latin *sinus*. A genuinely global, undergrad-memorable etymology and a non-Western foundational source.
- **Mādhava of Sangamagrāma (c. 1340–1425) and the Kerala school; *Yuktibhāṣā*.** Derived the infinite power series for sine, cosine, and arctangent (~250 years before Newton/Leibniz) and computed sine tables to ~12 decimals. This is the historical seed of the chapter's **small-angle approximation sin θ ≈ θ** and a direct preview of the Taylor-series chapter (Ch.13). Strongly non-Western.
- **Multinational PER study: "Students' difficulties distinguishing between radians and degrees," arXiv:2503.01525 (Mar 2025), survey of 769 college students.** The key modern empirical anchor: only **26.3%** correctly recognized that the standard derivative formulas (d/dθ sin θ = cos θ) hold *only in radians*; 70.7% wrongly thought either unit works. Direct evidence for why the chapter must teach radians as the *natural, arc-length* angle measure, not a unit to convert to.
- **Roger Cotes (1682–1716) and the limit lim(θ→0) sinθ/θ = 1 (in radians).** The exact statement that makes sin θ ≈ θ true and makes calculus of trig functions work — the "preview of small-angle behavior" the TIKTOC calls for. (Rigorous form via Cauchy, 1822.)

### Key empirical cases
- **Force on an incline (source ch.07):** the weight mg resolved into components along/perpendicular to the slope — mg sin θ down-slope, mg cos θ into the surface. The canonical "components from magnitude-and-angle" worked example; also where students must *decide which is sin and which is cos* (a documented sticking point).
- **Projectile launch angle (source ch.03/05/07):** initial velocity v₀ at angle θ → v₀cosθ (horizontal), v₀sinθ (vertical); range ∝ sin 2θ, maximal at 45°. Connects trig to a result students can check.
- **Pendulum restoring force ≈ −mg θ for small θ (source ch.17):** the small-angle approximation that turns a hard nonlinear problem into solvable SHM — the payoff preview for Ch.11/13.

---

## 2. The Core Concept — State of the Field

### What is settled
- The unit-circle definitions, the Pythagorean identity, laws of sines and cosines, and the radian as arc-length/radius are settled, exact mathematics.
- sin θ ≈ θ, tan θ ≈ θ, cos θ ≈ 1 − θ²/2 for small θ **in radians** — exact as leading terms of the Taylor series.
- Trig-function derivatives take their clean form *only* in radians; this is a mathematical fact, not a convention.

### What is disputed (pedagogy / convention)
- **Right-triangle-first vs. unit-circle-first sequencing.** Long-standing math-ed debate: triangles are concrete but cap angles at <90° and obscure periodicity; the unit circle generalizes but is abstract. Moore/Weber-style research favors building the *quantitative angle measure* (radian as arc length) before either.
- **Whether the radian should be a base SI unit** (the same debate noted in Ch.1) — affects how "dimensionless" the chapter calls angles.

### What has changed recently (last 5 years)
- The 2025 multinational study quantified the radian/degree confusion at a scale not previously documented — a fresh, citable result.
- Continued push (Thompson, Moore, et al.) to teach trig via **quantitative reasoning about angle measure and arc length** rather than mnemonic ("SOH-CAH-TOA") procedure. No change to the math.

---

## 3. Application Domain Examples (mechanics / waves)
1. **Incline decomposition:** mg → (mg sinθ, mg cosθ); derive the sliding condition and acceleration. (Source ch.07.)
2. **Projectile components and range:** R = v₀² sin2θ / g; why 45° is optimal and why 30°/60° give equal range. (Source ch.05/07.)
3. **Resolving a force along a rope at an angle / tension components in static equilibrium** (source ch.13) — law of sines on a force triangle.
4. **Small-angle pendulum:** sinθ ≈ θ linearizes the restoring force; preview of why period is amplitude-independent. (Source ch.17.)
5. **Wave phase and the unit circle:** y = A sin(kx − ωt) — sine as the natural description of oscillation; the unit circle *is* the phasor. (Source ch.18.)

---

## 4. The Book's Thesis Connection
Trigonometry is the bridge between "magnitude and direction" (how the world hands you a vector) and "components" (how the math wants it). The transferable skill is **decomposition**: projecting a quantity onto chosen axes via cosine of the included angle. A solver will compute sin(37°) instantly; it will *not* decide which component is which, choose the axes, or know that the answer only makes sense in radians once you differentiate. The radian/degree finding is a sharp illustration of the thesis: a student who memorized "sin' = cos" without understanding *why it needs radians* has the plug-and-chug, not the math — and will get oscillation problems wrong. Where it generalizes: the unit circle and small-angle linearization recur in every periodic phenomenon (AC circuits, signal processing, orbital mechanics), and "linearize near equilibrium" is one of the most transferable moves in all of applied math.

---

## 5. The AI Wayback Machine — Candidate Figures
Trigonometry is an unusually globally-distributed subject — strong genuine diversity available:
- **Āryabhaṭa** (Indian mathematician-astronomer, 476–550; Wikipedia: "Aryabhata"). Built the first sine table; redefined chord→half-chord (the modern sine). Foundational, non-Western, undergrad-accessible, and carries the wonderful jyā→sinus etymology. **Primary recommendation.** *Anchor prompt:* "Aryabhata (circa 500 CE, Indian mathematician-astronomer) — robed scholar with a sine-table manuscript and astronomical instruments, historically plausible editorial portrait, period-appropriate clothing and workspace, no text, no watermark."
- **Mādhava of Sangamagrāma** (Indian mathematician, c. 1340–1425; Wikipedia: "Madhava of Sangamagrama"). Power series for sine/cosine/arctan centuries before Europe — perfect bridge to the small-angle approximation and Ch.13. Lesser-known, non-Western.
- **Hipparchus** (Greek, c. 190–120 BCE; Wikipedia: "Hipparchus") — first chord table — as a Western/ancient counterpoint if a third is wanted.

**Demographic note:** Āryabhaṭa and Mādhava give two strong non-Western figures; both male. If a woman is wanted, candidates who *worked on* trig specifically are scarcer for this era — be honest rather than forcing one. Recommend leading with Āryabhaṭa (etymology + first table), Mādhava as the series-preview pairing.

---

## 6. Pedagogical Delivery Research
**Prior knowledge:** Pythagorean theorem, similar triangles, coordinates, the idea of a function. **Documented misconceptions:**
- **Radian as a "unit to convert to"** rather than a *measure* (arc length per radius). Some students believe "the whole circle = 1 radian"; only ~3% invoke the radius when defining a radian (Williams; Topçu et al., *epistemological obstacles* studies).
- **Derivatives work in any unit** — held by ~71% of students (arXiv:2503.01525, 2025). The dangerous one for physics.
- **sin/cos confusion in decomposition** — picking the wrong function for a component because the angle's reference side wasn't identified.
- **SOH-CAH-TOA as a black box** — procedural recall with no unit-circle meaning, which collapses for angles >90° and for periodic motion.

**Sequences shown to work:** define the radian *as arc length over radius* first and physically (wrap the radius along the arc); build the unit circle as the home of sine/cosine *before* heavy triangle drilling; tie sin θ ≈ θ to the picture (short arc ≈ chord ≈ vertical drop) so the approximation is *seen*, not asserted. **Failure mode:** teaching degrees and SOH-CAH-TOA as the whole subject, then surprising students with radians in calculus. **Understanding vs. memorizing:** the student who can explain *why* sinθ ≈ θ needs radians understands.

---

## 7. Representation and Display Research
- **The unit circle** — labeled with both degree and radian measure, showing (cosθ, sinθ) as the coordinates of the point and the angle as *arc length*. The central figure.
- **A radian-definition diagram** — an arc of length equal to the radius subtending 1 rad (≈57.3°), to attack the core misconception.
- **A force-on-incline decomposition diagram** — weight vector resolved into mg sinθ and mg cosθ with the tilted axes, explicitly showing which component carries sin and which cos.
- **A small-angle figure** — overlaid sin θ, tan θ, and θ curves near the origin showing they coincide, with cos θ ≈ 1 − θ²/2; the visual case for the approximation. (Bridges to Ch.13.)

## 8. Open Questions and Research Gaps
- The arXiv:2503.01525 (2025) study is a recent preprint; strong and multinational but not yet (as of research date) in a journal — treat the 26.3% figure as a current best estimate, verify against the published version when available.
- Right-triangle-first vs. unit-circle-first remains genuinely contested pedagogy.
- Radian-as-base-unit metrology debate is unresolved (shared with Ch.1).
- No constant-aging risk.

## 9. Sourcing Notes
- Ptolemy/*Almagest*, Āryabhaṭa/*Āryabhaṭīya*, and Mādhava/*Yuktibhāṣā* are primary historical sources; access modern scholarly translations/histories (the Indian-mathematics literature is well documented but the primary texts are Sanskrit — cite via established histories).
- The jyā→jiba→jaib→sinus etymology is well attested in standard histories of mathematics.
- PER claims are from peer-reviewed math-ed journals plus the 2025 multinational preprint; provenance noted above.
