# Figures and Images for Chapter 15: Fluid Mechanics

## Figure Inventory

All figures referenced in the chapter text use the placeholder format `[FIGURE: ...]` for integration with the publishing pipeline.

---

### Figure 1: Hot-Air Balloon at Dawn
**Context:** Opening scene for Concept 1 (Pressure and Buoyancy)

**Description:** A hot-air balloon envelope (the large fabric sphere) is shown at dawn with the burner firing. Inside the envelope, air is visibly hotter (indicated by shimmering or color gradient). Outside, cooler ambient air surrounds the balloon. The envelope is tethered to a basket below. A thermometer or temperature indicator would show ~100°C inside, ~15°C outside.

**Teaching purpose:** Illustrate density difference as the root cause of buoyancy. Visual reinforcement that the balloon rises because the air inside is less dense (same mass, larger volume).

**Caption:** "At dawn, the balloon operator ignites the burner. The air inside heats to 100°C while outside air is 15°C. Heated air is less dense—the same mass occupies more volume. The balloon displaces a larger volume of cooler air, creating a buoyant force that exceeds its weight."

**Dimensions:** Full-width illustration, ~600 pixels wide.

---

### Figure 2: Pressure Increasing with Depth
**Context:** Hydrostatic pressure derivation (Concept 1)

**Description:** A vertical column of water or fluid is shown with depth marked on the left axis (0, h, 2h, 3h, ...). At each depth, horizontal arrows pointing inward from all sides represent pressure forces acting on a small element. The arrows are drawn longer at greater depths, visually showing that pressure increases. The element at the bottom experiences significantly larger inward arrows than the element at the top.

**Teaching purpose:** Show that pressure acts in all directions and increases with depth. Prepare students for the force balance calculation.

**Caption:** "Pressure in a fluid acts perpendicular to any surface and increases with depth. The arrows represent pressure forces on a small element at different depths. Deeper elements experience larger pressure forces, driving the hydrostatic pressure increase."

**Dimensions:** Tall, narrow diagram, ~350 pixels wide, ~500 pixels tall.

---

### Figure 3: Force Balance on a Fluid Element
**Context:** Derivation of dp/dy = ρg (Concept 1)

**Description:** A thin horizontal slice of fluid at depth y is shown as a cylinder with:
- Top surface at pressure p(y), with downward arrow labeled "p(y)·A"
- Bottom surface at pressure p(y+Δy), with upward arrow labeled "p(y+Δy)·A"
- A weight arrow pointing down from the center, labeled "ΔmG = ρAΔyg"
- Annotations showing the slice dimensions (area A, thickness Δy)

**Teaching purpose:** Visualize the force balance that leads to the differential equation for pressure.

**Caption:** "A thin horizontal element of fluid experiences three vertical forces: pressure from above, pressure from below, and its own weight. Force balance gives the differential equation for hydrostatic pressure."

**Dimensions:** Diagram with clear labeling, ~400 pixels wide.

---

### Figure 4: Mercury Barometer
**Context:** Worked example in Concept 1

**Description:** A vertical glass tube closed at the top, inverted into a pool of mercury. The tube is drawn with:
- A vacuum (or near-vacuum) at the top, shown as empty space
- Mercury filling the tube to a height h ≈ 76 cm above the surface of the mercury pool
- The mercury pool surrounding the base of the tube
- A ruler or scale on the left side showing the 76 cm height
- Atmospheric pressure arrows pointing down on the surface of the mercury pool
- A label "h = 760 mm Hg at sea level"

**Teaching purpose:** Concrete example of hydrostatic pressure; connect the formula to a historical, measurable device.

**Caption:** "Torricelli's barometer (1643). Atmospheric pressure supports a column of mercury 760 mm high. This height directly follows from p = ρgh, rearranged to h = p₀/(ρ·g)."

**Dimensions:** Tall, narrow diagram, ~250 pixels wide, ~450 pixels tall.

---

### Figure 5: Buoyant Force on a Submerged Object
**Context:** Archimedes' principle (Concept 1)

**Description:** A sphere (or cube) is shown submerged in water. Pressure arrows are drawn on all surfaces:
- Top of object: small downward arrows (lower pressure, shallower depth)
- Bottom of object: large upward arrows (higher pressure, deeper depth)
- Sides: arrows pointing inward (pressure from all sides)
- A net upward arrow labeled "F_B (buoyant force)" shows the vector sum

**Teaching purpose:** Show why buoyant force is upward (pressure is higher at the bottom than the top) and connect to Archimedes' principle.

**Caption:** "Pressure is higher at the bottom of a submerged object than at the top. This pressure difference creates an upward net force—the buoyant force. Its magnitude equals the weight of the fluid displaced."

**Dimensions:** Diagram, ~400 pixels wide.

---

### Figure 6: Floating vs. Sinking Based on Density
**Context:** Density and Archimedes' principle (Concept 1)

**Description:** Two side-by-side panels:
- **Left panel:** An object less dense than water (e.g., wood block) partially submerged, with upward buoyant force arrow and downward weight arrow of similar magnitude. Text: "ρ_obj < ρ_fluid → floats"
- **Right panel:** An object more dense than water (e.g., lead weight) fully submerged and sinking, with buoyant force smaller than weight. Text: "ρ_obj > ρ_fluid → sinks"
- A third possibility (not shown) could indicate neutral buoyancy.

**Teaching purpose:** Emphasize that floating/sinking is determined solely by the density comparison.

**Caption:** "Whether an object floats or sinks depends only on whether its average density is less than or greater than the fluid's density. Shape matters for how deep it sits in the water, but not for whether it floats at all."

**Dimensions:** Two-panel figure, ~600 pixels wide total.

---

### Figure 7: Pipe Narrowing and Flow Acceleration
**Context:** Continuity equation and Bernoulli (Concept 2)

**Description:** A horizontal pipe is shown narrowing from a wider section (left) to a narrower section (right). Streamlines (curved lines) are drawn through the fluid:
- In the wider section, streamlines are spread out and loosely spaced (low velocity, lower speed arrows)
- In the narrower section, streamlines are bunched closely together (high velocity, longer speed arrows at the constriction)
- Labels show A₁ > A₂, v₁ < v₂, and Q₁ = Q₂ (flow rate is conserved)

**Teaching purpose:** Visualize the continuity equation: as area decreases, velocity must increase to conserve flow rate.

**Caption:** "As a pipe narrows, the same volume of fluid must pass any cross-section per unit time (continuity). Area decreases, so velocity increases. The closely-spaced streamlines in the narrow section indicate higher speed."

**Dimensions:** Horizontal diagram, ~550 pixels wide.

---

### Figure 8: Pressure Drop in Narrowing Pipe
**Context:** Bernoulli's principle (Concept 2)

**Description:** The same narrowing pipe as Figure 7, but now with pressure indicated:
- Manometer tubes (U-tubes with liquid) are attached at the wide section and narrow section
- The liquid in the manometer at the wide section is higher (higher pressure)
- The liquid in the manometer at the narrow section is lower (lower pressure)
- Annotations: "p₁ (high)" at wide section, "p₂ (low)" at narrow section, and the height difference in the manometers visually represents the pressure difference

**Teaching purpose:** Show that fast-moving fluid has lower pressure—Bernoulli's principle in action.

**Caption:** "Where the pipe narrows and water speeds up, the pressure drops. The manometers show this directly: the liquid rises higher on the wide-section side (higher pressure) and lower on the narrow-section side (lower pressure)."

**Dimensions:** Horizontal diagram with manometers, ~600 pixels wide.

---

### Figure 9: Shower Curtain Bulging Inward
**Context:** Application of Bernoulli (Concept 2)

**Description:** A bathroom scene (simplified) with a shower stall. Inside the stall, water from the showerhead creates a fast-moving airstream. The shower curtain is shown bulging inward (toward the stall), with an arrow labeled "atmospheric pressure" pushing it inward from outside, and an arrow labeled "low pressure region" inside where the fast air is. A small cross-section showing velocity profiles inside (fast air, low pressure) and outside (still air, atmospheric pressure) could be included.

**Teaching purpose:** Concrete, relatable example of Bernoulli's principle in daily life.

**Caption:** "When shower water runs, it drags air along, creating a fast-moving stream inside the stall. Fast-moving air has low pressure (Bernoulli). Atmospheric pressure outside the curtain pushes it inward. This is not a suction effect; it's a pressure difference."

**Dimensions:** Sketch, ~400 pixels wide.

---

### Figure 10: Laminar vs. Turbulent Flow
**Context:** Viscosity and flow regimes (Concept 3)

**Description:** Two side-by-side pipes:
- **Left (Laminar):** Straight, smooth streamlines running parallel to the pipe axis. Velocity profile shown as a parabola (fastest at center, zero at wall). Text: "Low Re: Laminar"
- **Right (Turbulent):** Irregular, chaotic streamlines with swirls and eddies. No clear velocity profile. Text: "High Re: Turbulent"

**Teaching purpose:** Visualize the difference between orderly laminar flow and chaotic turbulent flow.

**Caption:** "Laminar flow is smooth and orderly, with distinct layers. Turbulent flow is chaotic, with eddies and mixing. The Reynolds number determines which regime applies: Re < 2,300 is typically laminar, Re > 4,000 is turbulent."

**Dimensions:** Two-panel diagram, ~600 pixels wide.

---

### Figure 11: Velocity Profile in a Pipe (Poiseuille Flow)
**Context:** Viscosity and laminar flow (Concept 3)

**Description:** A horizontal pipe in cross-section (circular). Inside, the velocity is shown as a parabolic profile:
- Center: maximum velocity v_max
- Moving outward radially: velocity decreases smoothly
- At the wall (r = R): velocity = 0 (no-slip boundary condition)
- A few velocity vectors (arrows) at different radial positions show the variation

**Teaching purpose:** Show that viscous drag from the wall creates a velocity gradient. This sets up the understanding of Poiseuille's law.

**Caption:** "In viscous laminar flow through a pipe, the fluid at the wall is stationary (no-slip boundary condition). Moving outward toward the center, velocity increases parabolically. The velocity gradient creates shear stress."

**Dimensions:** Cross-sectional diagram, ~350 pixels wide (circular).

---

### Figure 12: Poiseuille Resistance: Effect of Radius
**Context:** Poiseuille's law and the r⁴ dependence (Concept 3)

**Description:** Three pipes in a row, each with different radius:
- **Left pipe:** largest radius, labeled "r", with large flow rate Q_ref
- **Center pipe:** radius r/√2, with medium flow rate ~Q_ref/4
- **Right pipe:** smallest radius r/2, with tiny flow rate ~Q_ref/16
- A graph below shows the relationship: x-axis is "Radius (arbitrary units)", y-axis is "Flow Rate", and a steep curve (r⁴) is drawn

**Teaching purpose:** Quantify the r⁴ dependence; show why small narrowing has huge effects on flow.

**Caption:** "Flow rate is proportional to r⁴. Halving the radius reduces flow to 1/16. Doubling the radius increases flow 16-fold. Small changes in vessel diameter have enormous effects on flow rate."

**Dimensions:** Three-pipe diagram with graph, ~600 pixels wide.

---

### Figure 13: Coronary Artery Stenosis
**Context:** Application of Poiseuille (Concept 3)

**Description:** Two side-by-side arteries:
- **Left (Normal):** Cross-section of a coronary artery with normal radius, showing red blood cells flowing through at reasonable density. Label: "Normal: r = 2 mm, Q = Q₀"
- **Right (Stenosed):** Same artery but with a narrowing (plaque buildup shown as thickening of the vessel wall), reducing the lumen radius to ~1.5 mm. Red blood cells are much more sparsely distributed, indicating reduced flow. Label: "Stenosed: r = 1.5 mm, Q ≈ 0.3 Q₀"

**Teaching purpose:** Show the clinical relevance of Poiseuille's law; explain why even modest narrowing is dangerous.

**Caption:** "Arterial stenosis (narrowing) dramatically reduces blood flow. A 25% reduction in radius cuts flow to about 31.6% of normal, starving heart muscle of oxygen. This is why angioplasty or stents are used to restore vessel diameter."

**Dimensions:** Two-panel cross-section diagram, ~500 pixels wide.

---

### Figure 14: Airplane Wing and Lift
**Context:** Application of Bernoulli (Concept 2)

**Description:** Side view of an airplane wing (airfoil shape):
- The curved upper surface and flatter lower surface are clearly shown
- Streamlines are drawn above and below the wing
- Upper surface streamlines are closer together and have "fast" labeled near them (higher velocity)
- Lower surface streamlines are more spread out with "slow" labeled (lower velocity)
- Pressure contours or arrows indicate lower pressure on top, higher pressure on bottom
- A large upward arrow labeled "Lift" shows the net force

**Teaching purpose:** Show how Bernoulli explains lift; connect theory to a practical, important application.

**Caption:** "An aircraft wing is shaped so that air moves faster over the upper surface than the lower surface. Fast-moving air has lower pressure (Bernoulli), creating a pressure difference that lifts the wing. This is lift."

**Dimensions:** Side-view diagram, ~600 pixels wide.

---

### Figure 15: Scale Shifts in Fluid Systems
**Context:** Integration and summary (end of chapter)

**Description:** A composite figure showing fluid systems at different scales:
- **Top:** Capillary (10 μm), with individual red blood cells shown, laminar flow, low Reynolds number
- **Middle-left:** Coronary artery (3 mm), blood flowing smoothly, laminar
- **Middle-right:** Aorta (25 mm), larger, faster flow
- **Bottom-left:** River (km scale), with visible eddies and turbulent structure
- **Bottom-right:** Ocean current (100 km scale), vast horizontal extent

Each is labeled with typical velocity, Reynolds number, and flow regime. Simple arrows show the direction and relative magnitude of flow.

**Teaching purpose:** Emphasize that the same physics (Bernoulli, Poiseuille, continuity) applies across vastly different scales, but parameter values and dominant effects change.

**Caption:** "Fluid mechanics applies from capillaries to oceans. At small scales (capillaries), viscosity dominates and flow is laminar. At large scales (rivers, oceans), inertia dominates and flow is turbulent. The same equations describe all, but their solutions differ."

**Dimensions:** Composite vertical layout, ~600 pixels wide, ~800 pixels tall.

---

## Figure Integration Notes

- All figures use the placeholder format `[FIGURE: Title]` in the chapter text.
- Figures are ordered sequentially as they appear in the narrative.
- Each figure has a clear purpose: introduce a concept, show a derivation step, or illustrate an application.
- Captions are written to be readable independently of the surrounding text (self-contained).
- Diagrams should use consistent color schemes: blue for water/fluids, arrows for forces/velocity, and consistent fonts for labels.

## Specification Checklist

- [x] Hot-air balloon opening scene: vivid, connects to density concept
- [x] Hydrostatic pressure diagrams: show depth dependence clearly
- [x] Barometer: both the apparatus and the formula interpretation
- [x] Buoyancy and Archimedes: multiple perspectives (pressure arrows, density comparison)
- [x] Continuity equation: pipe narrowing with streamline visualization
- [x] Bernoulli effect: pressure manometers show the pressure drop
- [x] Shower curtain: relatable, everyday example
- [x] Laminar vs. turbulent: visual distinction
- [x] Velocity profile (Poiseuille): parabolic profile at the wall
- [x] Radius dependence: quantified and graphed (r⁴ scaling)
- [x] Stenosis: medical application with numbers
- [x] Airplane wing: lift explanation via streamlines and pressure
- [x] Scale shifts: capillary to ocean, showing parameter changes
