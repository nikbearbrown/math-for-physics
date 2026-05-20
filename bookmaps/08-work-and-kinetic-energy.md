# Chapter 8 Bookmap — Work and Kinetic Energy

## Source material analysis: OpenStax University Physics v2 Chapter 7

The source material (five OpenStax files) covers work, kinetic energy, power, and the work-energy theorem in the algebra-based physics tradition. This analysis extracts the structure, tradeoffs, and angles available to the Feynman-based author.

---

## Source sections and their machinery

### Section 1 — Introduction and conceptual overview

**What the source does:** Opens with an abstract paragraph stating that work involves force and change of motion, mentions differential equations, and says energy methods can "provide useful answers" when Newton's laws are intractable.

**The machinery it uses:** Problem-difficulty framing (differential equations are hard, energy is easier). Road-mapping (this chapter will teach work, kinetic energy, power). No hook, no scene, no question.

**Angle for Feynman:** The source identifies the *problem* (force methods are sometimes hard) but does not show the reader a *situation* where this matters. A cold open with a bow, a pile driver, or a car climbing a hill would make the method's utility visceral before the theory appears.

**What Feynman-based writing can take:** The problem-difficulty hierarchy. Energy methods truly do solve things force methods leave intractable. The challenge is to show, not tell.

---

### Section 2 — Work done by constant and variable forces

**What the source does:**
- Defines $dW = \vec{F} \cdot d\vec{r} = |\vec{F}||\,d\vec{r}|\cos\theta$.
- States the line integral: $W_{AB} = \int_A^B \vec{F} \cdot d\vec{r}$.
- Explains the dot product geometrically.
- Works through examples: lawn mower (constant force at angle), gravity (constant force vertical), spring (variable force).
- Notes that work done by constant forces depends on endpoints, not path.
- Discusses normal force (perpendicular, zero work), friction (negative work).

**The machinery it uses:** Mathematical notation, component decomposition, integral setup, numerical examples. The section is heavy on formalism and light on why the formalism matters.

**Angle for Feynman:** The dot product is the right idea but is presented as a notational rule ("multiply magnitude by cosine by angle") rather than as a selection device ("only the component parallel to motion counts"). The distinction is subtle but crucial for intuition.

**What Feynman-based writing can take:** The worked examples (lawn mower, gravity, spring). The insight about path independence for constant forces. The careful distinction between work done *by* and work done *against*.

---

### Section 3 — Kinetic energy

**What the source does:**
- Defines kinetic energy $K = \frac{1}{2}mv^2$ as a "quantity introduced into mechanics" to explain collisions.
- Notes the historical name "energy of motion."
- Extends to systems: $K = \sum_i \frac{1}{2}m_i v_i^2$.
- Mentions alternate form $K = \frac{p^2}{2m}$.
- Discusses units (same as work, joules).
- Gives examples: athlete running (kinetic energy calculation), asteroid impact (very large scale), thermal neutron (very small scale).
- Notes that kinetic energy depends on reference frame (relative motion example: person in moving train).
- Mentions rotational and thermal kinetic energy by name.

**The machinery it uses:** Definition, historical context, scalar quantity (no vectors), dimensional analysis, order-of-magnitude examples across many scales.

**Angle for Feynman:** The source defines kinetic energy but does not *derive* it from Newton's laws. It is presented as a quantity that "works" (appears in collisions) without showing why $\frac{1}{2}mv^2$ specifically. For a calculus-based course, the derivation from $\vec{F} = m d\vec{v}/dt$ is available and enlightening.

**What Feynman-based writing can take:** The observation that kinetic energy is frame-dependent. The scalar nature (no direction information). The multiple scales (from neutrons to asteroids).

---

### Section 4 — Work-energy theorem

**What the source does:**
- States the theorem: $W_{\text{net}} = \Delta K$.
- Derives it (algebra-based) by integrating $\vec{F} = m\vec{a}$ with $a = \frac{dv}{dt}$.
- Explains that "net work" means all forces combined.
- Gives a strategy box (draw free-body diagram, determine which forces do work, add up work, set equal to change in kinetic energy).
- Provides a detailed example: toy car on a loop-the-loop (finding minimum height).
- Provides a second example: bullet penetrating wood (finding stopping force).
- Notes that the theorem applies to systems with multiple forces, curved paths, and variable forces.

**The machinery it uses:** Integration (loosely), work definition, kinetic energy definition, strategy / problem-solving structure, multi-step numerical examples.

**Angle for Feynman:** The derivation in the source is algebraic. A calculus-based treatment can show the vector identity $\vec{v} \cdot d\vec{v} = \frac{1}{2}d(v^2)$, making the result less mysterious. The strategy box is useful but hides the conceptual insight: the theorem works because work and kinetic energy are two languages for the same idea (energy transfer).

**What Feynman-based writing can take:** The loop-the-loop example (elegant, surprising answer: height must exceed $2.5R$). The problem-solving structure. The note that the theorem avoids complicated forces at intermediate points.

---

### Section 5 — Power

**What the source does:**
- Defines average power: $P_{\text{ave}} = \Delta W / \Delta t$.
- Defines instantaneous power: $P = dW/dt$.
- Notes that $W = P\Delta t$ if power is constant, and $W = \int P(t) dt$ if it varies.
- States that power = $\vec{F} \cdot \vec{v}$.
- Gives units: watts, horsepower.
- Provides two examples: athlete doing pull-ups (power from work and time), car climbing a hill (power from force and velocity).

**The machinery it uses:** Rate definition, dot product, unit conversion, real-world applications.

**Angle for Feynman:** Power is presented as a rate (correct) but the examples are computational. Neither shows why power is important (e.g., battery capacity versus peak discharge, fatigue versus total work done). The connection to $P = \vec{F} \cdot \vec{v}$ is stated but not explained: why the dot product? Because only the component of force in the direction of motion contributes to the rate of energy transfer.

**What Feynman-based writing can take:** The athlete example is memorable and measurable. The $P = \vec{F} \cdot \vec{v}$ formula. The distinction between average and instantaneous power.

---

## Ideas harvest — What a Feynman author can build on

### Puzzles and opening hooks

- **The bow:** How does energy stored in bent limbs become arrow speed? (opens concept 1)
- **The pile driver:** A 500-kg hammer falls 5 m. What speed at impact? Newton's laws or energy? (opens concept 2)
- **The power plant:** A 500-MW power plant versus a 5-kW solar panel. Same energy? Different rates? (opens concept 3)
- **The marble on the bumpy track:** The normal force varies at every point, but the final speed depends only on height. How? (concept 2 application)

### Specification moves

- Work is not effort or exertion; it is a number measuring energy transfer, calculated as the dot product of force and displacement.
- Kinetic energy is not momentum; it is a scalar (no direction), depends on the square of speed, and varies with reference frame.
- Power is not energy; it is the rate of energy transfer, measured in joules per second (watts).

### Trade-off territory

**Energy methods bypass complication but lose information:**
- Curved paths? Energy does not care about the shape.
- Variable forces? Energy still works (via path dependence).
- But you lose the velocity *vector* — energy gives only the magnitude.

**Work at constant force is trivial; variable forces require path information:**
- Gravity is constant near Earth. Work depends only on height.
- A spring force changes with position. The same displacement via different paths can yield different work amounts (actually, no — spring force is conservative, so it's path-independent too; but this is not obvious without calculation).

**Power measures intensity; energy measures total:**
- 100-W bulb for 100 hours = 10 kW heater for 1 hour = same energy, vastly different power.
- Car battery: high capacity, low peak power = long range, no acceleration. Or vice versa.

### Scale shifts and comparisons

- Human power output: 100–1000 W (athlete, ordinary person, sedentary person).
- Car engine: 100–300 kW.
- Power plant: 500 MW.
- Light bulb: 10–100 W.

These anchor the unit "watt" to bodily sensation.

### Mechanism-first explanations

- **Why $K = \frac{1}{2}mv^2$ specifically?** Because integrating $\vec{F} = m d\vec{v}/dt$ with $d\vec{r} = \vec{v} dt$ yields $\vec{v} \cdot d\vec{v} = \frac{1}{2}d(v^2)$. The factor of one-half is not magical; it is the product of the chain rule and the dot product rule.

- **Why is work a dot product?** Because the component of force perpendicular to motion does nothing — it does not move the object in that direction. Only the parallel component transfers energy. The cosine $\theta$ term selects the parallel part.

- **Why does power equal $\vec{F} \cdot \vec{v}$?** Because work is $\vec{F} \cdot d\vec{r}$, and power is the rate: $P = \frac{dW}{dt} = \frac{\vec{F} \cdot d\vec{r}}{dt} = \vec{F} \cdot \frac{d\vec{r}}{dt} = \vec{F} \cdot \vec{v}$.

### Named misconceptions to address directly

- Work is not effort (standing against a wall does zero work despite muscular effort).
- Work can be negative (friction, opposing motion).
- Kinetic energy is not momentum (different dependencies on mass and velocity).
- Path matters for variable forces but not for constant forces (actually needs care — conservative vs. nonconservative).
- Power is not energy (rate versus total).

### Calculation patterns worth teaching

- Constant force at angle: $W = Fd\cos\theta$.
- Spring force: $W = -\frac{1}{2}k(x_B^2 - x_A^2)$.
- Kinetic energy to speed: $v = \sqrt{\frac{2K}{m}}$.
- Power from work: $P = W/t$ (if power is constant) or $P = dW/dt$ (instantaneous).
- Power from force and velocity: $P = Fv\cos\theta$ where $\theta$ is the angle between them.

### Connections to what comes next

- Chapter 9 (Potential Energy) extends work and energy to conservative forces and the principle of conservation of mechanical energy.
- Chapter 10 (Momentum) will show that while kinetic energy depends on $v^2$, momentum depends on $v$ linearly, leading to different conservation laws.
- Chapter 13 (Gravitation) uses energy methods to find escape velocity and orbital mechanics without solving differential equations.

---

## Author's notes — What to preserve and what to depart

### Preserve

- The worked examples (lawn mower, loop-the-loop, bullet penetration). They are concrete and surprising.
- The historical note that kinetic energy was introduced to explain collisions. It motivates why the formula matters.
- The loop-the-loop example in particular: the answer $h > 2.5R$ is non-obvious and shows the power of the method.

### Depart

- The abstract opening. Replace with a scene (archer, pile driver, power plant).
- The separation of kinetic energy from Newton's laws. In a calculus-based course, derive it from $\vec{F} = m d\vec{v}/dt$.
- The strategy box (useful but lifeless). Embed the method in the narrative of a worked example instead.

### Extend

- The derivation of kinetic energy from first principles, using the vector identity $\vec{v} \cdot d\vec{v} = \frac{1}{2}d(v^2)$.
- The connection between work and potential energy (previews Chapter 9).
- The path-dependence of work for variable (non-conservative) forces. The source mentions it but does not explore it deeply.
- The reference-frame dependence of kinetic energy. The source notes it; a Feynman treatment would make it vivid with a careful example.

---

## Pedagogical structure for the Feynman version

**Concept 1: Work as a line integral** — How does a force transfer energy when the path is curved or the force varies?
- Cold open: archer drawing bow, storing energy in the limbs.
- Define work via dot product: only the parallel component matters.
- State the line integral; sketch why it works (summing infinitesimal contributions).
- Trade-off: path-independence for constant forces vs. path-dependence for variable forces.
- Examples: lawn mower, gravity, spring.

**Concept 2: Kinetic energy and the work-energy theorem** — Why does $K = \frac{1}{2}mv^2$ emerge from Newton's laws?
- Cold open: pile driver, hammer falling and striking.
- Derive kinetic energy from $\vec{F} = m d\vec{v}/dt$ and the definition of work.
- State the theorem: $W_{\text{net}} = \Delta K$.
- Trade-off: energy gives magnitude of velocity, not direction.
- Examples: marble on bumpy track, car accelerating with air resistance.

**Concept 3: Power** — How fast is energy being transferred?
- Cold open: power plant (500 MW) vs. solar panel (5 kW) vs. light bulb (100 W).
- Define power as the rate of work: $P = dW/dt$.
- Derive $P = \vec{F} \cdot \vec{v}$ from the work definition.
- Trade-off: power is rate, energy is total; battery design problem.
- Examples: athlete doing pull-ups, car climbing hill, household appliances.

**Integration:** Archer draws and releases. The work she does (power delivered over time) becomes elastic potential energy in the bow, which becomes kinetic energy of the arrow. The arrow flies against gravity and air resistance (negative work by both), losing kinetic energy. The mechanics of how the bow limbs accelerate (complicated force at each point) is hidden; only the energy accounting remains visible.
