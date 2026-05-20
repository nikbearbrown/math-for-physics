# Image References — Chapter 12: Angular Momentum

## Figures referenced in chapter text

### Concept 1 — Angular momentum of a particle

**[FIGURE: Particle angular momentum geometry]**
- **Location in text:** After "The cross product is the key..."
- **Caption:** A particle at position $\vec{r}$ moving with momentum $\vec{p}$. The angle $\theta$ between $\vec{r}$ and $\vec{p}$ determines the magnitude of $\vec{l} = \vec{r} \times \vec{p}$. The lever arm $r_\perp$ is the perpendicular distance from the origin to the line of motion. For a particle moving perpendicular to $\vec{r}$ (as shown), $\theta = 90°$ and the lever arm equals the radius.
- **Elements to show:**
  - Origin point
  - Position vector $\vec{r}$ from origin to particle
  - Momentum vector $\vec{p}$ at the particle location
  - Angle $\theta$ between vectors
  - Perpendicular line from origin to the line of motion (the lever arm $r_\perp$)
  - Angular momentum vector $\vec{l}$ perpendicular to the plane of $\vec{r}$ and $\vec{p}$ (using right-hand rule)
- **Pedagogical purpose:** Establish that the cross product captures the geometric dependence on angle and the concept of lever arm

**[FIGURE: Meteor trajectory and angular momentum]**
- **Location in text:** In worked example (after "A meteor enters Earth's atmosphere...")
- **Caption:** A meteor observed from a point on the ground. The position vector $\vec{r}$ and velocity vector $\vec{v}$ determine the angular momentum about the observer. The meteor moves downward at an angle; its angular momentum has magnitude $7.5 \times 10^8$ kg·m²/s and points out of the page (positive $\hat{k}$).
- **Elements to show:**
  - Ground reference frame (xy-plane shown)
  - Observer at origin
  - Meteor position at $(25\text{ km}, 25\text{ km})$
  - Velocity vector pointing downward at angle
  - Result vector $\vec{l}$ pointing out of page
- **Pedagogical purpose:** Concrete calculation practice; shows that the choice of origin matters (observer far from the line of motion sees large angular momentum)

---

### Concept 2 — Angular momentum of rigid body

**[FIGURE: Disk rotation and moment of inertia]**
- **Location in text:** After "For a continuous rigid body rotating about a fixed axis..."
- **Caption:** A disk of mass $m$ and radius $r$ rotates about a vertical axis through its center with angular velocity $\omega$. A small mass element $dm$ at distance $R$ from the axis has tangential velocity $v = R\omega$ and contributes $R^2 \omega \, dm$ to the total angular momentum. The sum over all elements gives $L = I\omega$, where $I = \int R^2 \, dm$ is the moment of inertia.
- **Elements to show:**
  - Disk viewed from above (circle)
  - Rotation axis through center (vertical, perpendicular to page)
  - Angular velocity vector $\vec{\omega}$ pointing up (right-hand rule)
  - Small mass element $dm$ at distance $R$ from axis
  - Velocity vector $\vec{v}$ tangent to the circle
  - Indication that vectors outside the plane have perpendicular components that cancel (leaving only z-component)
- **Pedagogical purpose:** Visual derivation of $L = I\omega$; show where the integral comes from

**[FIGURE: Cross section of spinning disk]**
- **Location in text:** In worked example (after "A uniform disk of mass $m = 2.0$ kg...")
- **Caption:** Top view of the disk showing rotation direction (counterclockwise), the angular velocity vector $\vec{\omega}$ pointing out of the page (by right-hand rule), and the resulting angular momentum vector $\vec{L}$ in the same direction.
- **Elements to show:**
  - Disk outline (circle)
  - Rotation direction arrows around the circumference (counterclockwise)
  - Angular velocity vector emerging from center (out of page)
  - Angular momentum vector (same direction as $\vec{\omega}$)
  - Labels for $\omega$, $L$, $r$, $m$
- **Pedagogical purpose:** Reinforces the relationship $\vec{L} = I\vec{\omega}$ and the direction rule (right-hand rule)

---

### Concept 3 — Conservation of angular momentum

**[FIGURE: Ice skater spinning—arms extended vs. tucked]**
- **Location in text:** Opening of "The ice skater—the canonical example."
- **Caption:** Left: Ice skater with arms extended, spinning slowly at $\omega_0 = 2\text{ rev/s}$, with moment of inertia $I_0$. Right: Same skater with arms pulled in close to the body, spinning much faster at $\omega_1 = 4\omega_0 = 8\text{ rev/s}$, with moment of inertia $I_1 = \frac{1}{4}I_0$. No external torque acts; angular momentum $L = I\omega$ remains constant. The spin rate increases as the moment of inertia decreases.
- **Elements to show:**
  - Two side-by-side views of the skater from above
  - Left: arms extended, radius of rotation large, slower spin indicated by arc length markers
  - Right: arms folded in, radius small, faster spin indicated by denser arc length markers
  - Arrows showing the transfer (angular momentum conservation arrow between the two states)
  - Labels: $I_0$, $\omega_0$, $I_1$, $\omega_1$, $L =$\text{constant}
- **Pedagogical purpose:** Intuitive visualization of the key insight (faster spin from geometric change, not external push)

**[FIGURE: Gymnast on high bar—extended and tucked]**
- **Location in text:** In worked example (after "A gymnast dismounts from a high bar...")
- **Caption:** A gymnast in mid-air after dismounting. Left: Fully extended at the moment of release ($I_0 = 21.6$ kg·m², $\omega_0 = 1.0$ rev/s). Right: Tucked into a ball during the fall ($I_1 = 5.4$ kg·m², $\omega_1 = 4.0$ rev/s). During 0.5 seconds in the tuck, he completes 2 full rotations before landing.
- **Elements to show:**
  - Side-by-side views of the gymnast (stick figure acceptable)
  - Left: arms and legs extended
  - Right: arms and legs folded, body compact
  - Trajectory arc showing fall path
  - Rotation count indicator (e.g., position markers for 0, 0.5, 1.0, 1.5, 2.0 rotations)
- **Pedagogical purpose:** Reinforces conservation in a practical athletic context; connects geometry to observable outcome (number of rotations)

---

### Concept 4 — Precession

**[FIGURE: Spinning top precessing—side view and top view]**
- **Location in text:** After "Imagine a spinning top resting on a pivot point..."
- **Caption:** A spinning top tilted at angle $\theta$ from the vertical. Left (side view): The gravitational force $\vec{F} = m\vec{g}$ acts downward on the center of mass, producing a torque $\vec{\tau} = \vec{r} \times \vec{F}$ perpendicular to both $\vec{r}$ and $\vec{F}$ (horizontal, pointing to the right). This torque changes the direction of the angular momentum vector $\vec{L}$, causing the spin axis to rotate around the vertical. Right (top view, looking down): The spin axis traces a cone around the vertical axis, completing one precession cycle in time $T_P = 2\pi/\omega_P$.
- **Elements to show:**
  - Side view: top with spin axis at angle $\theta$, gravitational force downward at center of mass, torque vector horizontal, angular momentum vector along spin axis
  - Top view: vertical axis (looking down), spin axis as a radial line rotating around the center, dashed circle showing the precession path
  - Labels: $\vec{L}$, $\vec{\tau}$, $\theta$, $\omega_P$, precession period $T_P$
- **Pedagogical purpose:** Show the geometric mechanism: perpendicular torque rotates the direction of $\vec{L}$ (not its magnitude), causing the axis to precess

**[FIGURE: Torque and angular momentum change]**
- **Location in text:** After "This torque points horizontally (perpendicular to the vertical angular momentum)."
- **Caption:** Vector diagram showing how a horizontal torque $\vec{\tau}$ changes the angular momentum vector $\vec{L}$ by a horizontal amount $d\vec{L} = \vec{\tau} dt$. The tip of the $\vec{L}$ vector moves horizontally, tilting the vector. Over one complete precession cycle, the tip traces a circle, and the spin axis (along $\vec{L}$) traces a cone.
- **Elements to show:**
  - Angular momentum vector $\vec{L}$ pointing upward at an angle
  - Torque vector $\vec{\tau}$ perpendicular to $\vec{L}$ (horizontal)
  - Change in angular momentum $d\vec{L}$ in direction of $\vec{\tau}$
  - New angular momentum vector $\vec{L} + d\vec{L}$ (tilted further)
  - Circular path traced by the tip of $\vec{L}$ (dashed circle at the end of the vector)
- **Pedagogical purpose:** Clarify the vector mathematics of precession; show that magnitude stays constant while direction rotates

**[FIGURE: Classroom gyroscope precessing]**
- **Location in text:** In worked example (after "A gyroscope disk has mass $m = 0.30$ kg...")
- **Caption:** A gyroscope with its disk spinning at 20 rev/s, supported at a pivot. The spin axis (initially at some angle) precesses around the vertical at a rate $\omega_P = 3.12$ rad/s, completing one cycle in $T_P = 2.0$ seconds. Students can watch the spin axis slowly circle around the vertical, demonstrating steady precession.
- **Elements to show:**
  - Gyroscope apparatus (disk in a housing, mounted on a pivot)
  - Spin axis shown as an arrow (initially at an angle)
  - Vertical precession axis
  - Circular precession path (dashed) traced by the spin axis
  - Rotation arrows showing spin direction and precession direction
  - Time labels: $t = 0$, $t = 0.5\text{ s}$ (1/4 cycle), $t = 1.0\text{ s}$ (1/2 cycle), $t = 2.0\text{ s}$ (1 cycle)
- **Pedagogical purpose:** Concrete, observable demonstration of the precession equation; numbers are verifiable in the lab

---

## Image production notes

- **Style:** Technical diagrams, not artistic renderings. Use arrows for vectors, dashed lines for construction (lever arms, precession path), solid lines for physical objects.
- **Labeling:** All vectors labeled with their symbols ($\vec{L}$, $\vec{\tau}$, etc.). Magnitudes noted where relevant (e.g., $\omega = 100\text{ rad/s}$).
- **Color:** Use color to distinguish types of vectors (e.g., position vectors in blue, momentum vectors in red, angular momentum in green, torque in orange). Keep distinct but not garish.
- **Views:** Multiple views where helpful (side and top for spinning top; extended and tucked for skater). Isometric where three dimensions matter.
- **Scaling:** Physical scale unimportant; geometric relationships are. Make vectors and angles large enough to read.

---

## Image count

Total figures to be produced or sourced: **9**

1. Particle angular momentum geometry
2. Meteor trajectory and angular momentum
3. Disk rotation and moment of inertia
4. Cross section of spinning disk
5. Ice skater (extended vs. tucked)
6. Gymnast (extended vs. tucked)
7. Spinning top (side and top views)
8. Torque and angular momentum change (vector diagram)
9. Classroom gyroscope precessing

All images are technical diagrams suitable for production via vector graphics (SVG, AI, PDF) or illustration software. No photographs required. All images are referenced in the chapter text with [FIGURE: ...] markup.

---

## Accessibility notes

- Every figure has a caption describing what is shown and what it illustrates
- Captions include physical quantities (masses, velocities, angles) for reference
- Colors and patterns (cross-hatching, dashed lines) distinguish elements for color-blind readers
- Arrows indicate direction and vector nature clearly
- All labels use standard notation from the chapter text
