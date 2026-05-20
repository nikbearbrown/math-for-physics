# Bookmap: OpenStax University Physics Chapter 6 (Applications of Newton's Laws)

## What the source teaches and how

The OpenStax *University Physics* Volume 1 Chapter 6 covers three core applications of Newton's second law in situations where resistance forces dominate the physics. The pedagogical strategy in the source is to (1) introduce each force type empirically, (2) give the mathematical formula, (3) show worked examples, (4) list conceptual questions and problems.

The source does not deeply explain *why* these forces behave as they do, and does not derive terminal velocity from first principles for the reader. The Feynman conversion supplies the "why" (mechanical origin of friction, molecular adhesion, air density interaction) and the derivation (solving $mg - bv = m dv/dt$ by separation of variables).

---

## Detailed section breakdown

### OpenStax Section 6.1: Solving Problems with Newton's Laws

**What it teaches:** Problem-solving strategy (identify physical principles, sketch, draw free-body diagram, apply Newton's second law, check). Two examples: lifting a piano and pushing a car.

**How:** Narrative walkthrough of the strategy, then two worked examples showing the steps.

**What the Feynman conversion does:** Reduces this to one implicit principle (all worked examples in the main text follow the strategy without restating it). The strategy is shown in action rather than announced. The piano example is replaced with a crate sliding on a floor (more direct connection to friction, the chapter's first concept).

**Ideas harvest:**
- The piano example has pedagogical value for highlighting tension in strings over pulleys, but doesn't directly support the friction/drag/centripetal theme. Deferred to Chapter 9 (Tension and Pulleys).
- The free-body diagram discipline is essential. Feynman version emphasizes clear notation (which force is static friction, which is kinetic).
- The "check your answer" step is implicit in every worked example (Does this speed make sense for a skydiver? Yes, it matches measured data.).

---

### OpenStax Section 6.2: Friction

**What it teaches:** 
- Definition of static and kinetic friction.
- Formulas: $f_s \leq \mu_s N$ and $f_k = \mu_k N$.
- Table of coefficients for various material pairs.
- Microscopic explanation (adhesion, surface roughness).
- Worked example: determining friction on a pushed crate at three applied-force levels.

**How:** Conceptual narrative, then formulas, then coefficient table, then worked example.

**What the Feynman conversion does:** 
- Emphasizes the *responsive* nature of static friction (it grows to match applied force, not a formula that applies immediately).
- Explains the inequality symbol $\leq$ as the key distinction (static friction is not constant).
- Brings the microscopic explanation to the forefront (why does static > kinetic? Molecular adhesion breaks suddenly.).
- Replaces the simple "block on floor" example with a multi-part worked example that forces the solver to decide *which type of friction applies*.
- Names the trade-off (static is good for preventing slip, bad for smooth motion once moving).

**Ideas harvest:**
- The source includes a figure of rough surfaces at magnification, showing peaks and valleys. Feynman version describes this mechanism in words but defers the figure (it is in the images/bookmaps file for possible inclusion).
- The source mentions joints in the body (knee, hip) and artificial replacements. Feynman version includes this as a real-world application of the friction principles.
- The source discusses friction in everyday life (shoes, tires, tightropes). Feynman version highlights bicycle brakes as a design problem (static = no slip, kinetic = smooth stopping).
- The atomic-scale sidebar in the source (friction causes vibrations, heat generation) is included in the Integration section of the Feynman version.

---

### OpenStax Section 6.3: Drag Force and Terminal Velocity

**What it teaches:**
- Definition of drag and the quadratic drag formula $F_D = \frac{1}{2} C \rho A v^2$.
- Drag coefficient table (cars, spheres, skydivers, bicycles).
- Concept of terminal velocity as the speed where drag = weight.
- Formula $v_T = \sqrt{2mg / (\rho C A)}$.
- Example: 75-kg skydiver head-first reaches ~98 m/s; spread-eagle reaches ~50 m/s.
- Stokes' law for low-Reynolds-number flows: $F_s = 6\pi r \eta v$.
- Bacterial sedimentation and terminal velocity of small particles.

**How:** Narrative definition, formula, coefficient table, example (skydiver), then Stokes' law as a special case.

**What the Feynman conversion does:**
- Introduces terminal velocity *first* via the skydiver hook (acceleration slows, forces balance, constant velocity emerges).
- Derives the terminal-velocity formula from force balance rather than presenting it as a given.
- Solves the differential equation for *linear* drag ($F = bv$, Stokes' regime) in full, showing how velocity approaches the limit exponentially over time.
- Emphasizes the $v^2$ dependence (double speed, quadruple drag) as the key insight behind design (aerodynamic shaping, bodysuits, streamlining).
- Includes the Haldane quote on animal size and terminal velocity (from OpenStax source material).
- Worked example: 85-kg skydiver in spread-eagle, showing the calculation.

**Ideas harvest:**
- The source includes a figure of skydivers and a wind-tunnel photo. Feynman version describes these in words and reserves figure placeholders.
- The source mentions Olympic swimmers in bodysuits. Feynman version uses this as evidence of the $v^2$ effect (small improvements in drag coefficient → measurable time gains).
- The source discusses golf-ball dimples and bike racers shaving. Feynman version connects these to the drag formula ($C$ and $A$ matter, so every design choice pays off).
- The motorboat example in the source (coast against drag when motor fails) is adapted into the Integration section (motorboat as a second application of $m dv/dt = -bv$).

---

### OpenStax Section 6.4: Centripetal Force and Circular Motion

**What it teaches:**
- Centripetal acceleration $a_c = v^2 / r$.
- Centripetal force $F_c = m v^2 / r$ (and $F_c = m r \omega^2$).
- Sources of centripetal force (tension, gravity, friction, normal force).
- Worked example: car on flat curve, friction supplies centripetal force.
- Safe speed on a curve given coefficient of friction.

**How:** Formula, conceptual explanation, worked example, then application to car on curve.

**What the Feynman conversion does:**
- Emphasizes that centripetal force is a *label*, not a new force type.
- Names the specific forces that provide centripetal force in different scenarios (tension for tether ball, gravity for satellite, friction for car on flat road, normal force for car on banked road).
- Uses the Talladega banked turn (real world) as the primary example rather than an abstract "car on a curve."
- Derives the ideal banking angle formula from force balance, showing that friction is *not* needed at the right angle for the right speed.

**Ideas harvest:**
- The source includes a figure of centripetal force direction. Feynman version draws on this (force toward center, perpendicular to velocity).
- The source mentions a ladder leaning against a wall and sliding down (normal force at an angle). Feynman version defers this to the Incline chapter.
- The source discusses noninertial reference frames (feeling pushed outward in a car turning). Feynman version includes this as the Coriolis/centrifugal force section.

---

### OpenStax Section 6.5: Banked Curves

**What it teaches:**
- Banked curves reduce friction dependence.
- Ideal banking angle $\theta = \tan^{-1}(v^2 / rg)$ (no friction needed).
- At ideal angle, normal force alone provides centripetal force.
- Real roads are banked at compromise angles; friction allows operation at speeds above and below ideal.

**How:** Conceptual explanation, force balance on tilted surface, derivation of formula, example (Daytona 31°, ideal speed ~24 m/s).

**What the Feynman conversion does:**
- Opens Concept 3 with this scenario (Talladega).
- Derives the formula step-by-step from free-body diagram and force components.
- Uses the Daytona example but then asks: "Why do race cars go much faster?" Answer: friction. This connects back to Concept 1.
- Emphasizes that banking is not for "safety" but for efficiency at design speed.

**Ideas harvest:**
- The source discusses banking on highways (much less steep, ~3–7°).
- The source mentions aircraft banking (lift has inward component, similar geometry).
- The source notes that bicycle riders lean into turns (same angle formula $\theta = \tan^{-1}(v^2/rg)$ applies).
- Feynman version includes the bicycle example as a note in the Concept 3 hook.

---

### OpenStax Section 6.6 (if included): Inertial Forces and the Coriolis Force

**What it teaches:**
- Noninertial (accelerating) reference frames require fictitious forces to apply Newton's laws.
- Centrifugal force: $m v^2 / r$ outward (not real, artifact of rotating frame).
- Coriolis force: deflects objects moving in rotating frame.
- Examples: merry-go-round, hurricanes, Foucault pendulum.

**How:** Explanation of reference-frame choice, distinction between inertial and noninertial, examples.

**What the Feynman conversion does:**
- Includes this in Concept 3, under "Inertial forces in rotating reference frames."
- Clarifies that centrifugal force is fictitious (no physical source), while centripetal force is real.
- Uses the merry-go-round as the primary analogy (clear, intuitive).
- Mentions Earth's Coriolis effects (weather, ballistics) but notes they are small for everyday problems.

**Ideas harvest:**
- The source discusses noninertial frames as a tool for simplifying calculations in rotating reference frames.
- The source emphasizes the distinction between what is "real" in an inertial frame vs. what is artificial in a rotating frame.
- Feynman version names both clearly and avoids confusion by working primarily in the inertial frame (ground frame) and noting the rotating-frame perspective as a secondary tool.

---

## Ideas harvest — What a Feynman-style rewrite extracts

### Puzzles and hooks
1. **The crate problem:** Push harder and harder, and suddenly it moves. Why the sudden transition?
2. **The skydiver problem:** Falls faster, then stops accelerating. Why?
3. **The NASCAR turn:** How does a car stay on the track at 320 km/h on a 33-degree curve?

Each puzzle is concrete (named place, specific object), specific (temperature, mass, angles), and immediately answerable through force analysis.

### Specification moves
1. Friction is not *a force with a fixed magnitude*. It is a responsive force with an upper bound.
2. Terminal velocity is not *reached instantly*. It is a limit approached asymptotically.
3. Centripetal force is not *a new type of force*. It is a name for whatever forces point inward.

Each specification clarifies a vague term before reasoning about it.

### Mechanisms unpacked from first principles
1. **Friction (static vs. kinetic):** Why is kinetic < static? Molecular adhesion breaks suddenly; once sliding, fewer points of contact.
2. **Drag and terminal velocity:** Solve $mg - bv = m dv/dt$ by separation of variables, showing the exponential approach.
3. **Banked curve:** Decompose normal force into vertical (weight support) and horizontal (centripetal) components; derive angle formula.

Each mechanism is shown working, not asserted.

### Trade-offs named
1. **Friction trade-off:** High static (good for grip) vs. low kinetic (good for smooth motion). Design problem in brakes, shoes, joints.
2. **Drag trade-off:** Streamlining reduces drag but may sacrifice volume or maneuverability. High-speed vehicles pay enormous power penalty.
3. **Banking trade-off:** Steep banking at design speed is efficient; off-design speeds require friction. Too-steep banking is dangerous.

Each trade-off shows why design choices are constrained.

### Analogies and comparisons
- Friction as a "responsive" force (grows to meet your push, up to a limit) makes the inequality $f_s \leq \mu_s N$ intuitive.
- Terminal velocity as a "limit approached" (like exponential decay) connects to later chapters (damping, radioactive decay).
- Banking as reducing "friction dependence" shows why roads are designed the way they are.

No single analogy per chapter, but specification and mechanism comparison throughout.

### Connection points to other chapters
1. **Chapter 5 (Newton's laws):** This chapter applies the laws in real situations where forces are not simple.
2. **Chapter 8 (Work and kinetic energy):** Friction and drag dissipate energy as heat (non-conservative forces).
3. **Chapter 10 (Rotation):** Centripetal force applied to spinning objects.
4. **Chapters 15–16 (Oscillations and waves):** Damping forces (linear drag) cause energy loss.

---

## Counterarguments and gaps

### Gaps the source leaves (Feynman version addresses)
- **Why does friction exist?** Source: "adhesion + surface roughness." Feynman: explains the molecular mechanism and the sudden transition from static to kinetic.
- **How fast does a skydiver really fall?** Source: "use the formula." Feynman: solves the differential equation, showing the exponential approach to terminal velocity.
- **Why is banking used on highways?** Source: "for safety." Feynman: clarifies that banking is for efficiency at design speed; excessive banking is actually dangerous.

### What the Feynman conversion does NOT include (and why)
- **Inclined planes with friction:** Deferred to Chapter 5 (or included as an exercise here).
- **Atwood machines with friction:** Deferred to exercises (synthesis level).
- **Circular motion in vertical planes (loop-the-loop):** Deferred to Chapter 10 (rotation and circular motion on complex paths).
- **Coriolis force in detail:** Mentioned but not derived. Students may push back; the chapter acknowledges that Coriolis is real on Earth but small for everyday problems.

### Where the source and Feynman version diverge in emphasis
| Aspect | OpenStax source | Feynman version |
|--------|-----------------|-----------------|
| Friction introduction | Empirical definition + formula | Hook with crate problem; explain responsive nature first |
| Terminal velocity | Present formula, apply to examples | Derive from force balance; solve differential equation |
| Centripetal force | Name as "center-seeking force," show examples | Emphasize it's a *label*, not a new force |
| Banked curves | Derive angle formula for frictionless case | Use real Talladega data; explain why friction still matters in practice |
| Inertial forces | Introduce as mathematical convenience | Clarify fictional vs. real; use merry-go-round analogy |

---

## What would strengthen this chapter further

1. **Experimental data on friction:** Video of a block sliding at increasing speeds, showing the transition from static to kinetic friction. Could be captured in real time or extracted from existing physics demos.

2. **Wind-tunnel data:** Drag coefficients measured experimentally. Source includes this; Feynman version references it but could include a graph of $C$ vs. Re (Reynolds number) for a sphere.

3. **Satellite orbital mechanics:** Gravity provides centripetal force. Could extend Concept 3 to show that the same force balance works for orbits (foreshadowing Chapter 13, Gravitation).

4. **Heat generated by friction:** Connection to energy dissipation (Chapter 8). A calculation of heat generated in a sliding block, or in a car braking, would anchor the physics to thermodynamics.

5. **Resonance and damping:** Drag with velocity dependence appears again in oscillations (Chapter 15). A brief forward reference would help students recognize the pattern.

---

## Conclusion: Ideas extracted for reuse

**Puzzles:** Crate, skydiver, NASCAR turn.
**Specifications:** Friction as responsive, terminal velocity as limit, centripetal as a label.
**Mechanisms:** Static-kinetic transition (molecular), differential equation solution (exponential), banking angle derivation (force decomposition).
**Trade-offs:** Friction (grip vs. smoothness), drag (speed vs. power), banking (efficiency vs. safety range).
**Connections:** Chapters 5, 8, 10, 13, 15–16.

All of these are tools a textbook author can repurpose in a different voice or context while staying true to the physics.
