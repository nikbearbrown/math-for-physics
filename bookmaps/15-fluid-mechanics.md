# Bookmap: University Physics (OpenStax) Chapter 14 — Fluid Mechanics

**Source:** OpenStax University Physics, Volume 1, Chapter 14 (Fluid Mechanics)

**Analysis date:** 2026-05-07

**Scope:** Examines the pedagogical structure, conceptual scaffolding, and derivation choices in the OpenStax treatment of fluids. Extracts patterns applicable to the bear-textbooks Attenborough × Feynman voice.

---

## Section-by-Section Breakdown

### Introduction: The Puzzle Opening
**OpenStax approach:** Opens with a hurricane scenario—a small drop in atmospheric pressure (15% below average) causes devastating winds and torrential rain. Asks: "How can such a small drop in pressure lead to such a severe change in the weather?"

**Pedagogical value:** 
- Real consequence (millions in damage)
- Counterintuitive premise (small pressure change → large effect)
- Sets up pressure as the chapter's unifying theme
- Mentions applications (ears popping on airplanes, the bends in scuba diving, buoyancy, hot-air balloons) but defers detail

**Voice insight:** The chapter announces what it will cover rather than pulling the reader into discovery. The puzzle is real and consequential, which works, but the opening could be more kinetic—a *scene* rather than a *scenario*.

**Attenborough × Feynman adjustment:** Replace the hurricane with a concrete cold open (hot-air balloon burner lighting at dawn, a scuba diver at depth, a sinking ship, the moment a balloon releases and rises). Show the physics happening, then ask the question.

---

### Section 1: States of Matter and Density
**OpenStax structure:**
- Defines solid, liquid, gas phases
- Explains molecular bonding and freedom of movement
- Introduces density as $\rho = m/V$
- Provides density table for common substances
- Introduces specific gravity as a dimensionless alternative

**Key pedagogical moves:**
1. Molecular picture (bonding determines behavior)
2. Distinction between liquids and gases (both are fluids, but liquids have definite volume)
3. Density as a sorting mechanism (dense vs. light objects)
4. Table of values (80 substances—provides concrete reference)

**Specification work:** OpenStax defines density operationally ($\rho = m/V$) but doesn't specify until later that *local density* $\rho(x, y, z)$ is the limit of density in an infinitesimal volume. This matters for later when fluids become compressible (atmosphere).

**Strength:** The density table is excellent—students see that mercury is 13.6 times denser than water, which later explains why the barometer isn't 10 meters tall.

**Weakness:** Specific gravity is introduced as a dimensionless ratio but feels unmotivated at this point. It becomes useful in buoyancy, but that connection isn't made immediately.

**Attenborough × Feynman adaptation:** Keep the table and the molecular picture. Introduce density as a question: "Why does wood float and brass sink?" rather than "Density is mass per unit volume." Let the definition emerge from the puzzle.

---

### Section 2: Pressure
**OpenStax structure:**
- Defines pressure as $p = F/A$
- Emphasizes pressure as a scalar (acts perpendicular to surfaces)
- Introduces Pascal as the SI unit
- Derives hydrostatic pressure $p = p_0 + \rho gh$ by force balance on a fluid element
- Explores how pressure varies with depth in compressible (atmosphere) vs. incompressible (water) fluids

**Key derivation:** Force balance on a thin horizontal fluid element at depth $y$:
$$p(y + \Delta y) A - p(y) A - \rho A \Delta y g = 0$$
Leads to differential equation: $\frac{dp}{dy} = \rho g$
Solution for constant density: $p = p_0 + \rho gh$

**Conceptual moves:**
1. Pressure is local (acts on every surface element)
2. Pressure increases linearly with depth for incompressible fluid
3. The integral (calculus step) from differential to explicit formula is shown

**Strength:** The derivation is rigorous and step-by-step. Students see *why* pressure increases with depth, not just the formula.

**Weakness:** The atmospheric section (variable-density atmosphere) uses the ideal gas law without fully introducing it first. This creates a "trust me" moment that breaks the derivation-first approach.

**Applied example (worked):** Dam retaining water. Students calculate average pressure, force on dam, and observe that the force is small compared to the total weight of water (because pressure acts only on the surface, not on the entire volume).

**Attenborough × Feynman adaptation:** Keep the derivation visible. Expand the dam example: show how dam thickness increases with depth to balance increasing pressure. This embeds the practical insight that engineers *design for* the pressure gradient.

---

### Section 3: Gauge vs. Absolute Pressure
**OpenStax structure:**
- Distinguishes gauge pressure ($p_g$, measured relative to atmosphere) from absolute pressure ($p_{abs}$)
- Explains with scuba tank example: gauge reads zero when inside pressure equals atmosphere, even though absolute pressure is 1 atm
- Formula: $p_{abs} = p_g + p_{atm}$
- Discusses vacuum chambers (negative gauge pressure)

**Pedagogical value:** Specification work. Students are confused by why a fully-charged scuba tank reads something other than zero. This resolves that confusion.

**Application:** Manometers (U-tubes) and barometers are described as devices that measure pressure by balancing fluid columns. Height of mercury column = pressure.

**Strength:** Clear distinction with real examples (medical blood pressure, tire pressure, scuba gauges all use gauge pressure).

**Weakness:** The barometer section doesn't fully explain *why* there's a vacuum above the mercury. It says Torricelli's experiment created "nearly a pure vacuum," but doesn't explain why the mercury stops rising (air pressure balances the weight of the mercury column). This is a gap.

**Attenborough × Feynman adaptation:** Explain the vacuum: mercury rises until its weight (per unit area) matches the atmospheric pressure. At that height, the upward pressure from the mercury pool exactly balances the downward weight of the column, and the space above is vacuum (because the mercury is no longer in contact with air). This is a key insight.

---

### Section 4: Pascal's Principle
**OpenStax structure:**
- States Pascal's principle: a pressure change applied to an enclosed fluid is transmitted undiminished throughout the fluid
- Derives the hydraulic system amplification: $\frac{F_1}{A_1} = \frac{F_2}{A_2}$
- Applies to hydraulic jacks, brakes, and industrial machines

**Key insight:** A small force on a small piston can lift a large weight on a large piston, because pressure (force per area) is the same everywhere in the fluid.

**Worked example:** Hydraulic brake system. 100 N force on master cylinder (diameter 0.5 cm), transmitted to four wheel cylinders (diameter 2.5 cm each). Output force at each wheel: 1.25 × 10⁴ N.

**Strength:** Practical relevance (every car uses hydraulic brakes). The principle is elegant: one equation ($p_1 = p_2$) explains the entire mechanical advantage.

**Weakness:** The example glosses over the master cylinder being "at greater height" than the wheel cylinders. In real brakes, gravity matters and fluid height differences affect pressure. The idealized example ignores this.

**Attenborough × Feynman adaptation:** Keep the principle and the brake example. Add a note: "In reality, the master cylinder is at the steering wheel (high) and the wheel cylinders are at the wheels (low), separated by several meters vertically. Gravity adds its own pressure contribution, but the pressure transmitted by the hydraulic fluid still multiplies the force via the area ratio."

---

### Section 5: Archimedes' Principle and Buoyancy
**OpenStax structure:**
- Defines buoyant force as the net upward force on an object in a fluid
- States Archimedes' principle: buoyant force = weight of displaced fluid
- Derives it by imagining the object removed, leaving a void that would be filled by fluid
- Applies to floating and sinking (compare object density to fluid density)
- Fraction submerged for floating objects: $\frac{V_{sub}}{V_{obj}} = \frac{\rho_{obj}}{\rho_{fluid}}$

**Key physics moves:**
1. Pressure on bottom > pressure on top → net upward force
2. That force equals the weight of fluid that would occupy the space
3. Object floats if this buoyant force > weight of object

**Worked example:** A woman floating in fresh water with 97% of her volume submerged. Calculate average body density using the fraction-submerged formula.

**Strength:** The principle is derived, not just stated. Students understand *why* buoyancy works.

**Weakness:** The derivation (replacing the object with fluid) is clever but abstract. A diagram showing the pressure forces would help.

**Applied insight:** Oil floats on water, hot-air balloons rise in air, ships float despite being metal. All follow the same principle—average density less than the fluid.

**Attenborough × Feynman adaptation:** Show a diagram of pressure forces on the top and bottom of a submerged object. Derive the buoyant force as the vector sum of pressure forces (which automatically gives $F_B = \rho_{fluid} V_{displaced} g$). This grounds the principle in the pressure gradient, which students have already studied.

---

### Section 6: Fluid Dynamics — Flow Rate and Continuity
**OpenStax structure:**
- Defines flow rate $Q = \frac{dV}{dt}$ as volume per unit time (m³/s)
- Relates to velocity: $Q = Av$ (area times velocity)
- Introduces streamlines and laminar vs. turbulent flow
- Derives continuity equation: $A_1 v_1 = A_2 v_2$ (for incompressible flow)
- Explains with hose-and-nozzle example: water speeds up when hose narrows

**Key conceptual move:** Mass conservation → volume conservation (for incompressible fluids) → continuity equation.

**Worked example:** Garden hose (radius 0.9 cm) with nozzle (radius 0.25 cm), flow rate 0.5 L/s. Calculate velocity in hose and nozzle.

**Pedagogical strength:** The continuity equation is necessary background for Bernoulli. The hose example makes it concrete.

**Specification:** "Ideal fluid" is introduced as having negligible viscosity. This is the assumption that makes Bernoulli work cleanly.

**Attenborough × Feynman adaptation:** Keep the derivation and example. Add an observation: "The continuity equation is pure mathematics—it follows from 'the same mass passes every point per unit time.' No physics assumptions needed, other than incompressibility. This is why it's so robust."

---

### Section 7: Bernoulli's Equation
**OpenStax structure:**
- Derives Bernoulli from work-energy theorem applied to a fluid element
- Shows that work done by pressure = change in kinetic + change in potential energy
- Arrives at: $p_1 + \frac{1}{2}\rho v_1^2 + \rho g h_1 = p_2 + \frac{1}{2}\rho v_2^2 + \rho g h_2$
- Simplifies to special cases (static fluid, constant height)

**Derivation outline:**
1. Work done by pressure on a fluid element moving from region 1 to 2
2. This work goes into kinetic + potential energy
3. Set $W_{net} = \Delta KE + \Delta PE$ and solve

**Key insight:** The three terms (pressure energy, kinetic energy, potential energy) sum to a constant along a streamline.

**Worked example:** Water in a hose flowing into a nozzle. Given nozzle exit pressure (atmospheric) and velocities, calculate pressure in the hose.

**Strength:** The derivation is transparent—every step follows from Newton's laws. Students see that Bernoulli is energy conservation, not magic.

**Weakness:** The assumption of "frictionless" (inviscid) flow is mentioned but not emphasized. Real water has small but nonzero viscosity. Bernoulli predicts higher flow rates than observed.

**Applications section:**
- Entrainment (high-speed fluid pulls nearby fluid along due to low pressure)
- Velocity measurement (Pitot tube using manometer)
- Fire hose example (pressure, velocity, height all change; use full Bernoulli)

**Attenborough × Feynman adaptation:** Emphasize the "frictionless" assumption upfront. Show how small viscosity effects become large in long pipes or high-viscosity fluids. This sets up the transition to Poiseuille's law.

---

### Section 8: Viscosity and Laminar Flow
**OpenStax structure:**
- Defines viscosity operationally: $\eta = \frac{FL}{vA}$ (force to drag a plate through a fluid)
- Provides viscosity table for common fluids at various temperatures
- Explains laminar flow (layers don't mix) vs. turbulent flow (chaotic mixing)
- Derives Poiseuille's law: $Q = \frac{\pi r^4 \Delta p}{8 \eta L}$ (for laminar flow in a pipe)
- Introduces Reynolds number as a dimensionless criterion for laminar/turbulent transition

**Pedagogical moves:**
1. Viscosity as resistance to shearing (internal friction)
2. Laminar flow is orderly; turbulent flow is chaotic
3. The fourth-power dependence on radius
4. Reynolds number as a predictive tool

**Specification:** Viscosity depends on temperature (decreases for gases when heated, decreases for liquids when heated). Newtonian vs. non-Newtonian fluids mentioned but not deeply explored.

**Worked examples:**
- Air conditioning duct: calculate flow rate using Poiseuille
- Compare laminar vs. turbulent flow rates

**Strength:** Poiseuille's law is derived from first principles (force balance on a cylindrical shell of fluid). The $r^4$ dependence is shown to follow from solving the differential equation.

**Weakness:** The Reynolds number section is brief. When exactly does transition occur? The threshold (Re ≈ 2,300) is presented as empirical fact, without explaining the underlying instability mechanism.

**Applied insights:** Small reduction in artery radius has huge impact on blood flow (example: 10% radius reduction → flow drops to ~66%, approximately, though the exact factor depends on Reynolds number).

**Attenborough × Feynman adaptation:** Expand the fourth-power dependence with concrete numbers. Show the calculation for 25% radius reduction (to 75% of normal): flow becomes $(0.75)^4 = 0.316$ times normal—less than one-third. Emphasize this matters in medicine (stenosis, capillary beds).

---

## Ideas Harvest: Patterns for Attenborough × Feynman

### Cold Opens That Work
- **Hurricane pressure drop** (OpenStax intro): real, catastrophic consequence, but static
- **Better alternatives:** 
  - Hot-air balloon at dawn (burner fires, air heats, balloon rises—action)
  - Scuba diver descending and feeling pressure building (action, body awareness)
  - Mercury in a barometer tube rising as the observer watches (slow, visual)
  - A ship sinking because water is leaking in (drama)

**Principle:** Open with *motion* or *change*, not with a *scenario*.

### Specification Moves That Clarify
- **Gauge vs. absolute pressure:** two different quantities wearing one word "pressure"; the scuba tank reading "zero" is the key insight
- **Density vs. specific gravity:** dimensionless is useful when comparing across units
- **Incompressible fluid:** the assumption that makes Bernoulli work; acknowledge where it fails
- **Frictionless flow:** the assumption that makes energy conserve simply; real fluids dissipate energy

**Principle:** Name the assumption, explain why it's useful, and say what happens when it breaks.

### Derivations Worth Showing Fully
- **Hydrostatic pressure:** force balance on a thin layer → differential equation → integration (shows the method)
- **Bernoulli:** work-energy theorem on a fluid element → three energy terms → conservation along streamline
- **Continuity:** mass conservation → $\rho A v$ is constant → for incompressible fluids, $A v$ is constant
- **Poiseuille:** force balance on a cylindrical shell → differential equation for velocity profile → integrate to find flow rate

**Principle:** Every major formula should be derived, not just stated. The derivation is often more instructive than the formula itself.

### Worked Examples That Stick
- **Hose and nozzle:** continuity equation in action; flow rate constant, velocity changes, pressure changes (Bernoulli)
- **Dam:** pressure increases with depth; force on dam surface; total force is tiny compared to weight of water (surprising)
- **Mercury barometer:** directly connects formula to apparatus; height of 76 cm follows from $h = p_0 / (\rho g)$
- **Hydraulic brake:** one equation ($p_1 = p_2$) predicts output force; elegant mechanical advantage
- **Floating woman:** density comparison determines floating; measure fraction submerged, infer average body density
- **Stenosed artery:** small radius reduction → huge flow reduction; clinically important

**Principle:** Examples should have a "that's why!" moment—where the formula suddenly explains something puzzling.

### Trade-Offs to Name Explicitly
1. **Incompressible vs. compressible models**
   - Incompressible: simple ($\rho$ is constant), applies to liquids and low-speed gases
   - Compressible: complex, needed for high speeds and atmosphere
   
2. **Ideal (frictionless) vs. real fluids**
   - Ideal: Bernoulli is clean, energy conserves
   - Real: Poiseuille enters, energy dissipates as heat
   
3. **Laminar vs. turbulent regimes**
   - Laminar: ordered, predictable (Poiseuille works), low Reynolds number
   - Turbulent: chaotic, dissipative, high Reynolds number, resistance scaling changes

4. **Circular pipes vs. irregular geometry**
   - Circular: Poiseuille has a closed form
   - Irregular: requires numerical simulation or empirical correlations

**Principle:** Every model is a trade-off. State it clearly.

### Scale Shifts That Show Generality
- **Capillary (10 μm):** viscosity dominates, laminar, slow flow, pressure gradient is steep
- **Artery (2–3 mm):** viscosity still important, laminar, faster flow, pressure gradient is gentler
- **River (km scale):** inertia dominates, turbulent, fast flow with eddies, pressure gradient negligible
- **Ocean (100 km scale):** Coriolis force enters, pressure gradients drive currents over vast distances

**Principle:** Same physics (Bernoulli, Poiseuille) applies at all scales, but parameters and dominant effects shift.

### Unsettled Questions to Flag
- **No-slip boundary condition:** Is it a fundamental principle or an empirical observation? Why does the layer touching the wall have zero relative velocity?
- **Turbulent transition:** The Reynolds number threshold (≈2,300) is empirical. What is the theoretical mechanism of the instability that triggers turbulence?
- **Non-Newtonian fluids:** Blood behaves non-Newtonian at low shear rates. How does red-cell deformation affect effective viscosity?

**Principle:** Honesty about what we don't fully understand builds trust and curiosity.

---

## Integration Opportunities

The OpenStax chapter flows well: pressure → buoyancy → flowing fluids → energy conservation (Bernoulli) → viscosity (Poiseuille) → Reynolds number. Each concept builds naturally on the previous.

**Potential enhancement:** Add a final section showing how all three concepts (pressure, buoyancy, viscosity) are unified by the common theme of *how fluids resist and respond to forces*.

- **Static:** pressure increases with depth (hydrostatic)
- **Floating:** buoyant force arises from pressure gradient (Archimedes)
- **Moving & ideal:** energy is conserved; pressure drops when fluid accelerates (Bernoulli)
- **Moving & real:** viscosity resists motion; pressure drop overcomes viscous force (Poiseuille)

This narrative arc—from static to ideal-dynamic to real-dynamic—could be made more explicit.

---

## Verdict

**Strengths of the OpenStax treatment:**
- Rigorous derivations of major results
- Good mix of conceptual explanation and mathematical detail
- Practical applications (hydraulics, blood flow, barometers)
- Worked examples cover a range of complexity
- Tables of properties (density, viscosity) ground abstractions in data

**Gaps for Attenborough × Feynman:**
- Openings are scenarios, not scenes; could be more kinetic
- Assumptions (incompressible, inviscid, laminar) are stated but not foregrounded
- Some technical sections (atmospheric pressure, Reynolds transition) lack intuitive explanation
- The unified theme of "how fluids resist and respond to forces" could be more explicit

**Recommendation:** Use OpenStax as a comprehensive reference and source of worked examples. Restructure around cold opens (scenes, not scenarios), emphasize assumptions and their limits, and tie the three major concepts (pressure, buoyancy, dynamics) to a single unifying narrative about force, energy, and dissipation.
