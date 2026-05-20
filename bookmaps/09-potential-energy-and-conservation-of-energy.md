# Bookmap — Chapter 9 — Potential Energy and Conservation of Energy

## What This Is

A bookmap analyzes the chapter in the OpenStax University Physics Vol. 1 textbook on potential energy and conservation of energy. The map identifies the key scenes, puzzles, mechanisms, and ideas that a textbook author can borrow, adapt, or reverse-engineer for their own chapter. The goal is not to summarize — it is to extract what works.

---

## Source Material: OpenStax University Physics, Chapter 8 — Potential Energy and Conservation of Energy

(This bookmap pulls from the six source files read: m58311 through m58661, covering the entire original chapter.)

---

## Cold-Open Scene Analysis

**What the source does:** Opens with an image of George Rhoods' rolling ball sculpture — a real artwork where steel balls roll down curved tracks, gaining and losing speed as they rise and fall through a system designed to showcase energy conservation. The chapter invites the reader to think about "changes in the ball's kinetic energy and relates them to changes and transfers for other types of energy."

**Why it works:** The sculpture is concrete, beautiful, and non-obvious. The reader sees motion and immediately has a question: why does the ball speed up on the way down and slow on the way up? The promise is that the chapter will explain this without needing calculus or complicated forces.

**What a fry-voice author borrows:** The scene-first approach — begin with something a reader can *see* (the sculpture, or more generally, the roller coaster), not with an abstract definition. The cold open is a puzzle you want to understand, not a setup for equations.

**What an author might do differently:** The OpenStax cold open is visual but static (an image). A fry-voice author might make it *narrative* — the moment the chain releases, the car tips, you feel the drop. The goal is the same (establish the puzzle), but the texture is more immersive.

---

## Concept 1: What the Source Teaches

**The progression:**
1. Define potential energy difference as $\Delta U = -W$.
2. Explain the zero-point choice (arbitrary but important).
3. Work through a specific example: $F = -ax^2$ force, calculating $\Delta U$ by integration.
4. Introduce gravitational potential energy: $U(y) = mgy$.
5. Introduce elastic potential energy: $U(x) = \frac{1}{2}kx^2$.
6. Show a combined system: a mass hanging from a spring, where both gravitational and elastic potential energy are present.

**The worked examples:**
- A quartic force: $F = -ax^2$, integrate to find potential energy, use it to find height at different x-positions.
- Great Blue Hill in Milton, MA: a 75 kg hiker climbing 147 m gains $U = 108 \, \text{kJ}$. References real geography (elevation above sea level, Native American naming).
- A spring experiment: pull it back 3 cm, it stores 0.18 J; pull it back 6 cm, it stores 0.72 J. The quadratic scaling is visible in the numbers.
- A mass-spring system: derive the maximum compression when a mass dropped from height 1 m compresses the spring; shows how to set up the equation $mgh = \frac{1}{2}k(y_C)^2$ when there are two types of potential energy at once.

**What works:**
- The use of *real* examples (a named hill, a named sculptor's work) anchors the abstract concept.
- The progression from definition → worked example → mixed systems → real scenario is methodical.
- The trade-off between "potential energy depends on your zero choice" and "differences are absolute" is explicitly taught.

**What an author might question:**
- Is the quartic force the best first example, or would gravitational PE first make the concept clearer?
- The "Systems of Several Particles" section (brief) could be expanded to show why potential energy belongs to the *system*, not to one object.
- The spring potential energy is taught correctly but somewhat abstractly; grounding it in "you do work on the spring, and that work gets stored" might help.

---

## Concept 2: Conservative Forces

**The source's approach:**
- Define: "The work done by a conservative force is independent of the path."
- Give the mathematical condition for 2D: $\frac{\partial F_x}{\partial y} = \frac{\partial F_y}{\partial x}$.
- Work through a non-conservative example: $F_x = 5y$, $F_y = 10x$. The mixed partials don't match, so the force is non-conservative.
- Introduce the gradient relationship: $\vec{F} = -\nabla U$, so in 1D, $F_x = -\frac{\partial U}{\partial x}$.

**What works:**
- The explicit check (partial derivatives) is practical and teachable.
- The link between non-conservative forces and "path depends on the path taken" is clear.
- The recognition that friction "takes energy away from the system that can't be recovered" is honest.

**What an author might add:**
- A physical *intuition* for why path independence matters: if you could go from A to B two ways and get different amounts of work out of a conservative force, you could extract infinite energy by cycling. Contradiction.
- A table contrasting conservative and non-conservative forces side-by-side (gravity, springs vs. friction, air drag, drag).

---

## Concept 3: Conservation of Mechanical Energy

**The source's structure:**
1. Define mechanical energy: $E = K + U$.
2. State the conservation law: in a closed system with only conservative forces, $E$ is constant.
3. Give the problem-solving strategy (5 steps: identify the system, identify forces, check conservation, choose reference points, apply the principle).
4. Work through three detailed examples:
   - A simple pendulum released from rest at 30° angle, find speed at bottom.
   - A helicopter panel falling through air, calculate energy dissipated.
   - A projectile motion problem solved via energy.

**What works:**
- The problem-solving strategy is explicit and repeatable.
- The pendulum example avoids differential equations and complex kinematics — just geometry ($h = L(1 - \cos\theta)$), potential energy, and kinetic energy.
- The air-resistance example (panel falling) shows how to account for non-conservative work: $W_{\text{nc}} = \Delta(K + U)$.

**What a fry-voice author might emphasize differently:**
- The *why* behind the problem-solving steps: why do you choose reference points before solving? Because the absolute value of $U$ is arbitrary, but the problem is easier if you plant your zero somewhere smart.
- The *moment* when energy methods become powerful: it's when the force is complicated or the path is messy, but the start and end points are clear.

---

## Concept 4: Potential Energy Diagrams

**The source's treatment:**
1. Plot $U(x)$ vs. position.
2. Draw the total energy line at height $E$.
3. Identify turning points (where $U = E$, so $K = 0$).
4. Interpret stability: minimum → stable, maximum → unstable.
5. Worked example: $U(x) = 2(x^4 - x^2)$ with $E = -0.25 \, \text{J}$. Find allowed regions and equilibrium types. Calculate turning points algebraically.
6. Advanced: use energy conservation to find $x(t)$ by integration: $t = \int \frac{dx}{\sqrt{2(E - U(x))/m}}$.

**What works:**
- The visual (curve + energy line) immediately shows what's possible and what's not.
- Stability is defined both mathematically ($d^2U/dx^2 > 0$ vs. $< 0$) and physically ("force pushes back vs. pushes away").
- The progression from qualitative reading (where can the particle move?) to quantitative (finding turning points) is logical.
- The final leap (integrating to get $x(t)$) shows that energy is not just an accounting tool but a foundation for deriving motion.

**What an author might improve:**
- More examples of reading the diagram without calculating: "can you tell from the picture alone whether a particle with energy $E$ in this potential is oscillating or roaming?"
- A connection to quantum mechanics, where potential wells directly determine allowed states and energy levels.

---

## Ideas Harvest — For a Textbook Author

### Structural Moves

1. **Scene before abstraction.** The rolling ball sculpture, the roller coaster, the swinging pendulum — these appear before or alongside the equations. The equations explain what you already saw.

2. **The zero-point puzzle.** Many students trip on "potential energy depends on where I put zero." Teaching this head-on (showing two different zero choices for the same physical situation, then proving the energy *difference* is the same) is worth a paragraph.

3. **Real coordinates in real places.** "Great Blue Hill in Milton, MA" is a small touch, but it says "this isn't just a problem; it's a place." Grounding one example per concept in a real location makes the physics less abstract.

4. **From definition to worked example to real scenario.** For each new potential (gravitational, elastic, quartic), the source shows the definition, a calculation, and a physical application. The pattern is consistent enough that a reader can predict what's coming.

5. **The non-conservative force as an interruption, not a failure.** The chapter doesn't treat friction as "we can't solve this now." Instead: "friction introduces a new term in the energy balance — this is how we account for it."

### Puzzle-First Moves

1. **The quartic force example** (which opens Concept 1) is unfamiliar and requires integration. It's harder than necessary for a cold open, but it signals "you now have tools to solve forces you've never seen before." The puzzle is: given a weird force, can you find its potential energy?

2. **The helicopter panel** is the most grounded puzzle: a real falling object, measurable quantities (15 kg, 1000 m, 45 m/s), a real question (where did the energy go?). It shows that energy methods don't require idealized scenarios.

3. **The double-well potential** ($U(x) = 2(x^4 - x^2)$) is a puzzle about possibility: low energy traps you in one well, high energy sets you free. This is conceptually rich.

### Technical Contributions

1. **The partial derivative test for conservative forces** is elegant: $\frac{\partial F_x}{\partial y} = \frac{\partial F_y}{\partial x}$ is a practical check that doesn't require integration.

2. **The relationship $F = -\frac{dU}{dx}$ is shown in both directions**: integrating from force to potential (starting from $F = -ax^2$, integrate to get $U = \frac{1}{4}ax^4$), and differentiating from potential to force (given $U(x)$, find $F = -dU/dx$). Both directions are practiced.

3. **The table of energies** (Big Bang to mosquito, from $10^{68}$ to $10^{-6}$ joules) is memorable. It says: energy is a universal language. Everything from the cosmos to insects is measured in the same units.

---

## Where Fry-Voice Differs from This Source

**The source** (OpenStax) is comprehensive, systematic, and reliable. It covers the material thoroughly and provides ample worked examples. It is a reference textbook.

**A fry-voice rewrite** would:
- Begin with a *narrative* cold open (the chain releases, the car drops, you feel the moment when potential turns to kinetic).
- Emphasize the *mechanism* (where does the work go when you lift something?) before the formula.
- Prioritize the *puzzle* (why does the pendulum return to the same height?) before the solution method.
- Use the diagram not just as a visual aid but as a *thinking tool* — "what can you learn by looking, before calculating?"
- Ground more examples in real human experience: not "a block of mass $m$" but "you, jumping on a bed, storing energy in the springs with each bounce."
- Acknowledge the *limits* of energy methods explicitly: "this method works beautifully when you have only start and end points, but if you need to know how long it takes, you'll need calculus again."

---

## Specific Angles for Reuse

### For the Cold Open

**Roller coaster first drop** is a strong choice. The moment the chain releases, the car tips, gravity takes over. The reader feels the commitment to motion. This is better than a static image — it's a *moment*.

### For Concept 1

**The sequence: definition → quartic force → gravity → spring → combined system** works well. A fry-voice author might insert a moment of surprise after the spring PE: "notice that elastic PE grows as $x^2$, while gravitational PE grows as $y$ (linear). Same system, completely different curves. Why? The force law is different. A spring's force grows stronger the more you stretch it; gravity stays constant near Earth's surface."

### For Concept 2

**The partial derivative test** is good but abstract. A fry-voice author would add an intuitive picture: "if you could follow two paths from A to B and get different amounts of work from a force, you could build a perpetual motion machine. Contradiction. So real forces can't be path-dependent."

### For Concept 3

**The problem-solving strategy is valuable, but the numbering obscures the conceptual flow.** A fry-voice author might reorganize:
1. "First, decide what your universe is — the object alone, or the object plus the Earth, or object plus spring plus Earth?"
2. "Second, count your energy types. Gravitational? Elastic? Kinetic?"
3. "Third, pick where you're measuring from. Where is 'zero potential'?"
4. "Fourth, write the energy balance: initial = final (or initial = final + dissipated if there's friction)."
5. "Fifth, solve."

The logic is the same, but the narrative flows better.

### For Concept 4

**Diagrams are the pedagogical heart of this concept.** A fry-voice author would spend more time *reading* diagrams before making them. "If I show you a curve and an energy line, can you tell me: Is the motion bounded? Where are the fast parts? Where is the equilibrium? Is it a trap or a launching pad?"

---

## Remaining Puzzles and Gaps

**What the source doesn't fully explain:**
- Why do we *choose* the zero of potential energy rather than just accepting it as absolute? (The answer: because it's arbitrary — only differences matter — but this could be more explicit.)
- What does it mean physically that a force and a potential are related by a derivative? (The source shows the math; a fry-voice author might show the intuition: "the slope of the PE curve tells you how strong the force is.")
- When does energy conservation fail to help? (The chapter acknowledges non-conservative forces but doesn't emphasize the limitation sharply enough.)

---

## Adjacent Topics Worth Grafting In

1. **Power**: Work per unit time. Energy methods give you speed, but if the question is "how fast can we do this?", you need power. This is a natural bridge to the next chapter.

2. **Efficiency**: Real machines dissipate energy. A dam is 85% efficient; the rest becomes heat. This connects energy conservation to real engineering.

3. **Energy transformation across scales**: From joules to kilowatt-hours, from a battery to the Sun. The same conservation law applies to all scales.

---

## Final Assessment

The OpenStax chapter is well-structured, comprehensive, and grounded in worked examples. A fry-voice rewrite would preserve the structure and examples but invest more in:
- Narrative cold opens and scene-first teaching.
- Explicit puzzles that drive the concept (not just "here's the definition").
- More commentary on *why* energy methods are powerful (and when they're not).
- More grounding in human experience and real engineering.

The mathematical content doesn't need to change. The *voice* and *entry point* do.

---

**Tags:** #bookmap, #openstack-university-physics, #energy-conservation, #potential-energy, #pedagogy, #fry-voice

---

**Bookmap Created:** 2026-05-07

**Source Version:** OpenStax University Physics Vol. 1, Chapter 8 (Potential Energy and Conservation of Energy), sourced from six module files aggregating ~18,000 words of content, definitions, worked examples, and problem sets.

**Next Step:** Use this harvest to draft a fry-voice chapter that honors the source's rigor while adopting a more narrative, scene-first, puzzle-driven pedagogical voice.
