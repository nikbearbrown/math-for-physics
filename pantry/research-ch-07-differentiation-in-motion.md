# Research: Chapter 07 — Differentiation in Motion: Vector-Valued and Parametric Functions
## Mathematics for Physics
**Chapter one-line:** Differentiating vector-valued and parametric functions componentwise; velocity and acceleration as vector derivatives; related rates — with centripetal acceleration derived by differentiating a rotating unit vector.
**Research date:** 2026-05-30

---

## 1. Primary Sources

### Foundational papers and texts
- **Isaac Newton, *Philosophiæ Naturalis Principia Mathematica* (1687).** The geometric origin of the central result: Newton's analysis of circular motion (the "centripetal force" toward the center) and his limiting argument that an inscribed polygon's deflections approach continuous curvature. The chapter's modern derivative-of-a-rotating-vector derivation is the calculus translation of Newton's geometry. "Centripetal" (centrum + petere, to seek the center) is Newton's coinage.
- **Christiaan Huygens, *Horologium Oscillatorium* (1673) and *De vi centrifuga* (written 1659, published 1703).** Huygens derived the v²/r result for circular motion *before* Newton's *Principia*, by a geometric/limiting argument. The clean primary source for the centripetal-acceleration magnitude that the chapter re-derives by componentwise differentiation.
- **Josiah Willard Gibbs & Edwin Bidwell Wilson, *Vector Analysis* (1901).** The text that standardized the î, ĵ, k̂ component notation and the rules for differentiating vector functions componentwise — the formal apparatus the chapter uses. (The book already pairs Gibbs with ch. 03.)
- **Leonhard Euler, *Mechanica* (1736) and later work on the kinematics of rigid bodies.** Euler recast Newtonian mechanics in analytic (calculus-and-component) form rather than geometry — the move that makes "differentiate each component" the default. Conceptual ancestor of parametric/vector kinematics.

### Key empirical cases
- **Uniform circular motion, r(t) = r cos(ωt) î + r sin(ωt) ĵ (source ch. 05, ch. 11).** Differentiate once for v (tangent, magnitude rω), twice for a = −ω²r (center-pointing, magnitude v²/r). The chapter's signature derivation.
- **Projectile motion as a parametric curve (source ch. 05).** Position (x(t), y(t)) = (v₀cosθ·t, v₀sinθ·t − ½gt²); differentiate each component to get the velocity vector tangent to the parabola. Canonical because the *independence of components* is the whole pedagogical point.
- **Related-rates classic — the falling-ladder / expanding-shadow / filling-cone problems.** The standard calculus-textbook genre; in physics terms, the rate at which one coordinate changes constrains another via a geometric relation differentiated in time.

---

## 2. The Core Concept — State of the Field

### What is settled
Componentwise differentiation of vector-valued functions (r'(t) = x'(t)î + y'(t)ĵ + z'(t)k̂), the product rule for dot and cross products of vector functions, the parametric description of curves, the tangent-vector = velocity / second-derivative = acceleration correspondence, and the centripetal result a_c = v²/r = ω²r are all completely settled. Related rates is settled single-variable calculus (implicit differentiation in time).

### What is disputed
Nothing mathematical. Pedagogical debates only:
- **Whether to teach the unit-vector derivation or the geometric (Δv triangle) derivation of v²/r first.** The vector-calculus route (differentiate r(t)) is rigorous and general; the geometric route (similar triangles of the velocity-change vector) is more intuitive but feels like a trick. Both are standard; sequencing is a genuine choice.
- **Decomposition into tangential/normal components vs. raw Cartesian.** When to introduce the intrinsic (Frenet-style) tangential/normal split for nonuniform circular motion is a sequencing question, not a correctness one. The book's scope deliberately stops short of full Frenet apparatus.

### What has changed recently (last 5 years)
Pure-math content is stable; aging risk near zero. The live edge is again math-ed: research on student difficulty *coordinating* the independence of perpendicular components (a recurring projectile-motion misconception in physics-education research, e.g., the "horizontal velocity must die when vertical motion peaks" error) and difficulty with related rates as a *coordination of two changing quantities* (covariational reasoning, Carlson/Thompson). These frameworks are the current lens.

---

## 3. Application Domain Examples (mechanics/waves)
1. **Centripetal acceleration of a barrel-rolling jet (source ch. 05).** a_c = v²/r; at 134 m/s a 1-g turn needs r ≈ 1,833 m, an 8-g turn r ≈ 229 m. Derived by differentiating the rotating position vector twice — the chapter's marquee worked example.
2. **Projectile velocity vector at the top of the arc (source ch. 05).** Differentiating the parametric position shows v_y = 0 but v_x = v₀cosθ ≠ 0 at apex — the direct refutation of the "velocity is zero at the top" misconception, delivered by calculus.
3. **A satellite's displacement and velocity (source ch. 05).** Vector position given parametrically; componentwise differentiation yields the velocity vector; demonstrates 3D vector differentiation.
4. **Related rates — the boat crossing a river / closing-speed problems (source ch. 05 relative motion).** Differentiating a geometric constraint (e.g., distance² = x² + y²) in time relates the rates; the relative-velocity transformation is itself a statement about differentiating a vector sum of positions.
5. **Tangential + centripetal acceleration of a spinning-up disk (source ch. 11).** Nonuniform circular motion: a_tangential = rα and a_centripetal = rω² are perpendicular components, both obtained by differentiating the rotating vector when ω depends on t. Connects vector differentiation to rotational kinematics.

---

## 4. The Book's Thesis Connection
This chapter shows that the derivative, once built (Ch. 06), *scales up* without new ideas: a vector function is just several scalar functions stacked, so you differentiate each one. That single move — "componentwise" — is the transferable tool, and it carries unchanged into electromagnetism, robotics, computer graphics, and orbital mechanics. The centripetal derivation is the showcase: a result that looks like a memorized formula (v²/r) *falls out* of differentiating a unit vector twice, demonstrating the book's core promise that derived-on-the-page beats memorized.

**What the student must supply that a solver cannot:** the *parametrization* and the *geometric setup*. A solver differentiates r(t) instantly — but only after a human has decided to *write position as a function of time at all*, chosen the components (cos ωt, sin ωt) that encode "rotating at constant rate," and recognized that the second derivative pointing along −r *means* "toward the center." In related rates, the solver differentiates the constraint, but the human must *find the constraint* (which geometric relation ties the two quantities?) and *identify which rate is given and which is sought*. The chapter's lesson is that the calculus is mechanical once the motion is modeled as a parametric vector — and the modeling is the irreducibly human step.

---

## 5. The AI Wayback Machine — Candidate Figures
(Existing convention pairs ch. 05 with Caroline Herschel; for the *math* of differentiating motion, candidates who built vector/parametric kinematics:)

- **Christiaan Huygens (1629–1695, Dutch).** Derived v²/r for circular motion before Newton — the chapter's central result, in its original geometric form. *Anchor prompt:* "Christiaan Huygens (circa 1673, Dutch mathematician and physicist) — man in seventeenth-century coat and long hair, pendulum-clock and circular-motion geometry nearby, historically plausible editorial portrait, face-centered, period-appropriate, accurate to known portraits, no text, no watermark." *Skew flag:* heavily portrayed European male; over-canonical.
- **Émilie du Châtelet (1706–1749, French).** Translated and annotated Newton's *Principia* into French (still the standard French edition), engaging directly with the calculus of motion and the vis viva (kinetic energy) debate. Already used by the book for ch. 04 — consider only if not reused. *Anchor prompt:* "Émilie du Châtelet (circa 1745, French natural philosopher) — woman in elegant eighteenth-century dress, *Principia* translation manuscript and motion diagrams nearby, historically plausible editorial portrait, face-centered, period-appropriate, no text, no watermark." *Skew flag:* already in book wayback (ch. 04) — avoid duplication.
- **Mary Lucy Cartwright (1900–1998, British) or Grace Chisholm Young (1868–1944, British/German).** Young co-authored *The First Book of Geometry* and worked on the foundations of calculus of several variables and parametric curves; a strong under-portrayed woman for "differentiating curves." *Anchor prompt:* "Grace Chisholm Young (circa 1910, British mathematician) — woman in early-twentieth-century dress, parametric-curve and derivative diagrams nearby, historically plausible editorial portrait, face-centered, period-appropriate, no text, no watermark." *Skew flag:* under-portrayed (few reference images); strong diversity add.

Demographics: recommend pairing **Huygens** (the geometric origin of v²/r) with **Grace Chisholm Young** (an under-portrayed woman who worked on the calculus of curves) to offset the European-male skew and avoid reusing du Châtelet. Mixed Dutch/British, one male/one female.

---

## 6. Pedagogical Delivery Research
- **Prerequisites:** the derivative and the chain rule (Ch. 06) — *essential*, because differentiating cos(ωt) requires the chain rule; vector components and unit vectors (Ch. 04); parametric thinking; trig.
- **Core misconception 1 — perpendicular components are not independent.** Physics-education research repeatedly documents students believing horizontal velocity decreases as a projectile rises, or that velocity is zero at the apex. The chapter's componentwise differentiation *proves* independence (dx/dt is untouched by the y-equation). This is the central conceptual payoff and the central thing to confront head-on.
- **Core misconception 2 — confusing centripetal acceleration with angular acceleration (source ch. 11 notes this explicitly).** a_c = rω² exists even at constant speed (α = 0); α = dω/dt is a different quantity. Remedy: derive a_c by differentiating r(t) at constant ω, showing acceleration is nonzero even when speed is constant.
- **Core misconception 3 — "constant speed means no acceleration."** Defeated by the very first line of the unit-vector derivation: |v| constant but v rotating ⇒ a ≠ 0. The clock's second hand is the canonical image (source ch. 05).
- **Related-rates failure modes:** plugging in numbers *before* differentiating the constraint (destroys the rate relationship); failing to identify which quantity's rate is given. Remedy: differentiate the symbolic constraint first, substitute last — mirrors the book's "solve symbolically before substituting" rule from ch. 02.
- **Sequence that works:** (1) vector function as stacked scalar functions; (2) componentwise differentiation, demonstrated on a projectile (independence made visible); (3) the rotating unit vector → v then a, deriving v²/r; (4) tangential/normal split for nonuniform motion; (5) related rates as time-differentiation of a geometric constraint. Lead with projectiles (independence) before circular motion (the harder derivation).

---

## 7. Representation and Display Research
No special display required beyond standard figures. Recommended: (a) the rotating position vector with v drawn tangent and a drawn toward center, at several instants around the circle — the geometric content of the derivation; (b) a projectile parabola with the velocity vector drawn at apex (v_x ≠ 0, v_y = 0) to kill the apex misconception visually; (c) the Δv triangle (geometric route) shown beside the component route so the reader sees two derivations of one result agree. The "v tangent, a inward, around the circle" figure is the load-bearing one.

---

## 8. Open Questions and Research Gaps
- Physics-education research on the *independence-of-components* misconception is robust, but the best calculus-based intervention (versus algebra-based) is less settled — a gap the book can address by deriving independence rather than asserting it.
- Whether related rates is best taught here (alongside parametric motion) or deferred to a pure-calculus context is a curricular open question; the book's choice to bind it to motion is defensible but non-standard.
- Aging risk: zero for the mathematics; minimal for the history. Only the math-ed framing (covariational reasoning as the lens for related rates) is evolving.

---

## 9. Sourcing Notes
- **Strongest sources:** Newton's *Principia* (1687) and Huygens' *De vi centrifuga*/*Horologium Oscillatorium* are unimpeachable primaries for the centripetal result; Gibbs & Wilson's *Vector Analysis* (1901) is the primary for component notation. The projectile/independence misconception is well documented in physics-education research literature (Halloun & Hestenes lineage; verify a specific citation before quoting).
- **Weaker/secondary:** the precise priority of Huygens vs. Newton on v²/r and Euler's role in analytic kinematics were reconstructed from standard history-of-mechanics knowledge rather than a fetched primary in this pass — verify Huygens' 1659/1703 dating and the *De vi centrifuga* attribution against a history-of-science source before stating firmly.
- **To verify before drafting:** a specific peer-reviewed citation for the projectile-component misconception (e.g., a physics-education-research paper) to replace the general claim; Grace Chisholm Young's exact contributions to parametric-curve calculus.
- **Confidence:** high on the mathematics and the centripetal derivation; medium on the fine historical priority (Huygens/Newton/Euler) and on a pinpoint citation for the component-independence misconception.
