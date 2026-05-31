# Research: Chapter 05 — Functions, Graphs, and Power Laws
## Mathematics for Physics
**Chapter one-line:** Functions and the linear/quadratic/power/exponential forms; reading and building graphs; log–log lines and scaling exponents — slope and area set up as the two questions calculus will answer.
**Research date:** 2026-05-30

---

## 1. Primary Sources

### Foundational papers and texts
- **Galileo Galilei, *Two New Sciences* (Discorsi e dimostrazioni matematiche, 1638).** The original source for two ideas this chapter rests on. First, the time-squared law of fall: distances in free fall grow as the square of elapsed time (the quadratic function the chapter graphs). Second, the "square-cube" scaling argument — Galileo reasons that bones cannot keep the same shape as an animal grows because volume (hence weight) scales as length cubed while bone cross-section scales as length squared. This is the founding instance of a *power-law scaling argument* and the cleanest historical motivation for log–log thinking, even though Galileo had no logarithms-as-graphs.
- **Julian Huxley & Georges Teissier, "Terminology of relative growth" (*Nature*, 1936); Huxley, *Problems of Relative Growth* (1932).** Coined "allometry" and established the convention of plotting one biological measurement against another on log–log axes so that a power law y = ax^b appears as a straight line of slope b. This is the direct ancestor of the chapter's central technique: read the exponent off the slope. Use to anchor "log–log slope = scaling exponent."
- **Max Kleiber, "Body size and metabolism" (*Hilgardia*, 1932); refined 1947.** The empirical discovery that metabolic rate scales as (body mass)^(3/4) across orders of magnitude of animal size — the "mouse-to-elephant curve." The canonical worked case for extracting an exponent (≈0.75) from the slope of a log–log line, and a live example of how the *value* of the exponent (3/4 vs. the naively expected 2/3 surface-area law) is itself a scientific claim. (See West, Brown & Enquist below for the still-disputed mechanism.)
- **René Descartes, *La Géométrie* (1637).** Origin of the coordinate-graph idea — pairing algebra with geometry so a relationship between quantities becomes a curve. The conceptual bedrock for "reading and building graphs."

### Key empirical cases
- **Free fall, x ∝ t² (Galileo's inclined-plane data).** The quadratic graph students will differentiate in Ch. 06. Canonical because the *shape* of the curve (a parabola through the origin) is itself the physics.
- **Kleiber's law, B ∝ M^(3/4) (metabolic rate vs. body mass).** Canonical log–log case; illustrative of exponent-from-slope and of the difference between a fit and an explanation.
- **Galileo's square-cube law (bone strength vs. body size).** Canonical scaling argument; shows a power law derived from geometry rather than fitted to data.

---

## 2. The Core Concept — State of the Field

### What is settled
The function concept (a rule assigning one output to each input), the standard catalog of elementary forms (linear, quadratic/polynomial, power, exponential, logarithmic), the Cartesian graph, and the fact that a power law y = ax^b plots as a straight line of slope b on log–log axes (and an exponential y = ab^x plots straight on semi-log axes) are entirely settled, centuries-old mathematics. Nothing here is mathematically contested.

### What is disputed
Disputes are pedagogical and scientific-interpretive, not mathematical:
- **The function concept's hardest hurdle.** Math-education research (Vinner & Dreyfus; Sfard's *reification*) finds students hold a process view of function (a computation you do) long before an object view (a thing you can graph, transform, differentiate). This precedes calculus and quietly sabotages it.
- **What an exponent *means*.** In the Kleiber case the *empirical* slope (≈0.75) is settled; the *explanation* is not. West, Brown & Enquist (1997, *Science*) derived 3/4 from fractal nutrient-distribution networks; critics (e.g., metabolic-scaling skeptics) argue the exponent varies and the universal-3/4 claim is overstated. Good chapter material: a log–log line is a *measurement*, not a mechanism.
- **Notation/terminology.** "Power law" vs. "scaling law" vs. "allometry" are field-specific names for the same y = ax^b object.

### What has changed recently (last 5 years)
Pure-math content is stable; aging risk is minimal. The live edge is (a) continued debate over universal metabolic scaling, and (b) growing math-ed emphasis on *covariational reasoning* (Carlson, Thompson) — teaching students to imagine two quantities changing together rather than reading a static graph — as the prerequisite mindset for calculus. This reframes "reading a graph" from a static skill to a dynamic one and is the most current pedagogical lens for this chapter.

---

## 3. Application Domain Examples (mechanics/waves)
1. **Position-vs-time of a fall (source ch. 04, Baumgartner).** y(t) = y₀ + v₀t − ½gt² graphs as a parabola; its shape encodes constant acceleration. Sets up "the slope of this curve is velocity" (Ch. 06) and "the area under v(t) is displacement" (Ch. 08) — the two calculus questions named here.
2. **Stopping distance vs. speed.** Kinematics gives stopping distance ∝ v² (a power law with exponent 2). A log–log plot of braking distance against speed has slope 2 — a power law students can verify and a vivid road-safety hook.
3. **Pendulum period vs. length, T ∝ L^(1/2) (preview of ch. 17).** Period scales as the square root of length; log–log slope ½. Connects the chapter's technique to oscillation, foreshadowing Part III.
4. **Kepler's third law, T² ∝ r³ (preview of ch. 14).** Orbital period vs. orbital radius — exponent 3/2 read off a log–log line; one of history's most famous scaling discoveries.
5. **Drag force vs. speed, F ∝ v² (high-Reynolds regime).** Explains why the constant-acceleration fall model breaks; a power law with exponent 2 that the reader meets again when air resistance is reintroduced.

---

## 4. The Book's Thesis Connection
The thesis is *math as a transferable tool*. This chapter makes the case at its purest: a function is a relationship between quantities, a graph is its picture, and a log–log line turns the question "what is the exponent?" into "what is the slope?" — a tool that works identically for a falling body, a metabolizing mouse, and a galaxy's rotation. The chapter also *seeds* the engine of Part II by naming the two questions calculus answers — slope (rate) and area (accumulation) — before either tool exists, so the reader meets derivative and integral as answers to questions they already feel.

**What the student must supply that a solver cannot:** the *choice of variables and axes*. A computer will fit any line to any data; it cannot decide that metabolic rate "ought to" be plotted against mass on log axes, nor recognize that a straight log–log line is evidence of a power law rather than coincidence, nor judge whether a fitted exponent of 0.74 is "really" 3/4 or "really" 2/3. The judgment — what to plot, what a slope *means* physically, when a fit is an explanation — is the human's. This is the chapter's clearest illustration of the book's claim that the math is the leverage but the modeling decision is yours.

---

## 5. The AI Wayback Machine — Candidate Figures
(Existing book convention pairs ch. 04 with **Émilie du Châtelet**; for this math-led chapter on functions/graphs/scaling, candidates who worked *on the math* of relationships-as-curves:)

- **René Descartes (1596–1650, French).** Co-inventor of coordinate geometry — the very act of turning a relationship into a curve. *Anchor prompt:* "René Descartes (circa 1637, French philosopher and mathematician) — man in seventeenth-century collar and dark coat, coordinate-geometry diagrams and *La Géométrie* manuscript nearby, historically plausible editorial portrait, face-centered, period-appropriate, accurate to known portraits, no text, no watermark." *Skew flag:* heavily portrayed, European, male — over-canonical; balance with the two below.
- **Julian Huxley (1887–1975, British biologist).** Coined "allometry" and popularized the log–log straight-line reading of power laws. *Anchor prompt:* "Julian Huxley (circa 1932, British biologist) — man in 1930s suit, allometric growth graphs on log–log axes nearby, historically plausible editorial portrait, face-centered, period-appropriate, no text, no watermark." *Skew flag:* British scientific establishment, male; eugenics associations warrant a careful caption if used.
- **Mary Lucy Cartwright (1900–1998, British mathematician).** Pioneer of the qualitative study of how functions behave (nonlinear oscillations, what would become dynamical-systems graphing). Adds a woman who worked directly on *reading the shapes of curves*. *Anchor prompt:* "Mary Cartwright (circa 1945, British mathematician) — woman in 1940s dress, hand-drawn graphs of oscillating functions nearby, historically plausible editorial portrait, face-centered, period-appropriate, no text, no watermark." *Skew flag:* mid-century British academy; less heavily portrayed (good for diversity, fewer reference images for fidelity).

Demographics across the three: two male/one female; all European; one philosopher-mathematician, one biologist, one mathematician. Recommend leading with Cartwright or Huxley to reduce the Descartes over-canonical skew.

---

## 6. Pedagogical Delivery Research
- **Prerequisites:** algebraic fluency with exponents and the rules log(ab)=log a+log b, log(a^b)=b·log a (the engine that linearizes a power law); comfort reading a graph; high-school sense of slope.
- **Core misconception 1 — process vs. object view of function (Sfard, *reification*, 1991; Vinner & Dreyfus, 1989).** Students treat f(x) as "plug in and compute," not as an object with a graph and a rate. Until the object view forms, "the slope of f" (Ch. 06) is meaningless. *Remedy:* graph-first, build the function as a curve before manipulating its symbols.
- **Core misconception 2 — confusing exponential and power forms.** Students conflate x² (power) with 2^x (exponential). The chapter's log/semi-log distinction is the fix: power → straight on log–log; exponential → straight on semi-log.
- **Core misconception 3 — reading log axes.** Students misread the nonlinear spacing and miscompute slope on log–log paper (e.g., treating the slope as a rise-over-run in raw units). *Failure mode:* extracting the wrong exponent. *Remedy:* derive slope = Δ(log y)/Δ(log x) explicitly and check against a known case (free fall, slope 2).
- **Covariational reasoning (Carlson, Jacobs, Coe, Larsen & Hsu, 2002; Thompson).** The current research consensus: graph comprehension improves when students imagine the two quantities co-varying, not when they memorize curve shapes. Strongest "understand-vs-memorize" lever for this chapter — present every graph as a story of two quantities changing together.
- **Sequence that works:** (1) function as relationship between two physical quantities; (2) the four forms by their *graph shape* and *physical fingerprint*; (3) logs as the tool that straightens power/exponential curves; (4) slope-of-log–log = exponent, verified on free fall; (5) name the two calculus questions (slope, area) without answering them.

---

## 7. Representation and Display Research
No special display required beyond standard graph figures. Recommended figures: (a) a side-by-side of linear/quadratic/power/exponential curves with their physical fingerprints; (b) the *same* power-law data shown on linear axes (curved) and log–log axes (straight) to make the linearization visceral; (c) Kleiber's mouse-to-elephant log–log line with the slope-triangle drawn in. A small-multiples panel showing free fall (slope 2), pendulum (slope ½), Kepler (slope 3/2) on log–log axes would tie the chapter's technique to three later chapters at a glance.

---

## 8. Open Questions and Research Gaps
- The metabolic-scaling exponent (3/4 vs. 2/3 vs. "no universal value") remains scientifically open; useful as an honest example that a fitted slope is a measurement, not a proof of mechanism — but the book should *label* this as live science, not settled fact.
- Math-ed gap: less is known about how concurrent-calculus physics students specifically build the function-object view under time pressure; covariational-reasoning interventions are well studied in math classrooms but under-tested in physics-first contexts.
- Aging risk: minimal for the mathematics; the only datable claims are the metabolic-scaling debate (flag as ongoing) and which covariational-reasoning framing is current.

---

## 9. Sourcing Notes
- **Strongest sources:** Galileo (*Two New Sciences*) and Huxley/Kleiber are unimpeachable primaries for the scaling material; Sfard, Vinner & Dreyfus, and Carlson et al. are peer-reviewed math-ed primaries for the function-object and covariational-reasoning claims.
- **Weaker/secondary:** Kleiber's exact 1932 vs. 1947 refinement and the West–Brown–Enquist mechanism were drawn from encyclopedic/secondary summaries (Wikipedia "Kleiber's law," "Allometry"; Physics Today feature) — verify the 3/4-vs-2/3 history against Kleiber's *Hilgardia* paper and WBE's 1997 *Science* paper before quoting specifics.
- **To verify before drafting:** the precise slope values for the pendulum/Kepler/drag previews are standard but should be checked against the book's own later chapters (17, 14) for notation consistency.
- **Confidence:** high on the mathematics and the historical scaling lineage; medium on the exact attributions/dates in the metabolic-scaling debate (secondary-sourced).
