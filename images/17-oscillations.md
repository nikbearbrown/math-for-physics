# Image References: Chapter 17 (Oscillations)

This file lists all figures that should accompany the oscillations chapter. Each entry specifies what the figure shows, where it appears in the chapter, and key details for clarity.

## Figure 1: Coordinate System for a Mass on a Spring

**Location:** Concept 1, opening section.

**Description:** 
A horizontal surface with a mass attached to a spring. The spring is attached at the left to a fixed wall. The mass is shown at three positions: at equilibrium (spring at natural length), displaced to the right by amplitude $+A$, and displaced to the left by amplitude $-A$. Arrows show the position $x$, the restoring force $F = -kx$ (always pointing back toward equilibrium), velocity $v$ (arrows showing direction at each position), and acceleration $a = -\omega_0^2 x$ (pointing toward equilibrium).

**What students should see:**
- The spring force always opposes displacement.
- Velocity is perpendicular to force at each instant.
- Acceleration points toward equilibrium.
- The system is symmetric about equilibrium.

---

## Figure 2: Position, Velocity, and Acceleration in SHM Over Time

**Location:** Concept 1, after equations are derived.

**Description:**
Three graphs, stacked vertically:
1. $x(t) = A\cos(\omega_0 t)$ — displacement oscillates between $+A$ and $-A$.
2. $v(t) = -A\omega_0 \sin(\omega_0 t)$ — velocity oscillates between $-v_{\max}$ and $+v_{\max}$, leading the position by $\pi/2$.
3. $a(t) = -A\omega_0^2 \cos(\omega_0 t)$ — acceleration is proportional to displacement with a negative sign, leads position by $\pi$.

All three graphs cover two complete periods. Vertical dashed lines mark $t = 0, T/4, T/2, 3T/4, T, 5T/4, 3T/2$.

**What students should see:**
- Position and acceleration are always opposite in sign (out of phase by $\pi$).
- Velocity leads position by $\pi/2$ (when position is maximum, velocity is zero; when position is zero, velocity is maximum).
- The three quantities oscillate at the same frequency.

---

## Figure 3: Energy Exchange in Simple Harmonic Motion

**Location:** Concept 2, energy section.

**Description:**
Two sub-figures side-by-side:

*Left:* A sinusoidal curve of potential energy $U = \frac{1}{2}kx^2$ as a function of position $x$. The parabola is symmetric about $x = 0$. Mark the total energy $E_{\text{total}} = \frac{1}{2}kA^2$ as a horizontal line across the top. At the turning points ($x = \pm A$), all energy is potential. At $x = 0$, the potential is at its minimum and kinetic energy is maximum.

*Right:* Three rows of bars at positions $x = -A$, $x = 0$, and $x = +A$. Each row shows a bar divided into potential (shaded) and kinetic (not shaded) portions. At $x = \pm A$, the bar is all shaded (all potential). At $x = 0$, the bar is all unshaded (all kinetic). The total bar height is the same at all three positions.

**What students should see:**
- Energy oscillates between kinetic and potential.
- Total energy is conserved.
- Where displacement is large, kinetic energy is small (the mass is momentarily at rest at the turning points).

---

## Figure 4: A Simple Pendulum at Four Positions in One Cycle

**Location:** Concept 2, pendulum section.

**Description:**
Four snapshots of a simple pendulum hanging from a fixed pivot. In each:
- Show the string at a different angle: $\theta = 0$ (hanging straight down), $\theta = +\theta_{\max}$ (displaced to the right), $\theta = 0$ (passing through bottom, moving left), and $\theta = -\theta_{\max}$ (displaced to the left).
- For each position, draw:
  - The weight $mg$ (vertical downward).
  - The tension $T$ (along the string toward pivot).
  - The component of weight tangent to the arc (the restoring force, pointing toward equilibrium).
  - An arrow showing velocity direction (tangent to the arc, zero at the turning points).

Label the angle $\theta$ at each position and note where kinetic energy is maximum (at $\theta = 0$) and where it is zero (at $\theta = \pm \theta_{\max}$).

**What students should see:**
- The restoring force (tangential component of gravity) is not constant; it is proportional to $\sin \theta$.
- For small angles, $\sin \theta \approx \theta$, which makes the equation linear.
- The pendulum trades kinetic and potential energy just like the mass on a spring.

---

## Figure 5: Underdamped, Critically Damped, and Overdamped Responses

**Location:** Concept 3, damping section.

**Description:**
Three graphs on the same set of axes, all showing displacement $x(t)$ versus time $t$, all starting from the same initial condition (e.g., released from rest at $x = A$).

1. **Underdamped** (e.g., $b = 0.5 b_c$): A decaying oscillation. The envelope $A_0 e^{-bt/2m}$ is shown as a dashed curve above and below the oscillation. The mass passes through equilibrium multiple times before coming to rest.

2. **Critically damped** (e.g., $b = b_c$): The displacement decreases smoothly and monotonically to zero, approaching it asymptotically. No oscillation. The approach is fastest among all cases.

3. **Overdamped** (e.g., $b = 2 b_c$): The displacement decreases smoothly and monotonically, but more slowly than the critically damped case. Again, no oscillation.

All three curves start at the same amplitude and approach zero. The underdamped curve overshoots equilibrium multiple times; the other two do not.

**What students should see:**
- Damping removes energy from the oscillation.
- Critical damping is the "sweet spot"—it returns to equilibrium fastest without oscillating.
- Over-damping is sluggish.
- Under-damping wastes time oscillating but does eventually stop.

---

## Figure 6: Amplitude Response at Resonance

**Location:** Concept 3, resonance section.

**Description:**
A graph of amplitude $A$ (vertical axis) versus driving frequency $\omega_d$ (horizontal axis, in units of the natural frequency $\omega_0$). Three curves are plotted:

1. **High-Q system** ($Q = 10$): A sharp, tall peak centered at $\omega_d = \omega_0$. The peak is narrow; the amplitude is large only within a narrow frequency band.

2. **Medium-Q system** ($Q = 2$): A moderate peak, broader than the high-Q curve but still distinct.

3. **Low-Q system** ($Q = 0.5$): A broad, low peak spread over a wide frequency range.

All three curves:
- Go to zero as $\omega_d \to 0$ and as $\omega_d \to \infty$.
- Have their peak (or near-peak) near $\omega_d = \omega_0$.
- Show the relationship $A = F_0 / \sqrt{m^2(\omega_d^2 - \omega_0^2)^2 + b^2 \omega_d^2}$.

Mark the resonance frequency $\omega_d = \omega_0$ and the half-maximum amplitude points. Indicate the width $\Delta \omega$ at half-maximum and show that $Q = \omega_0 / \Delta \omega$.

**What students should see:**
- Resonance is where the driving frequency matches the natural frequency.
- Less damping (higher $Q$) gives a sharper, higher resonance peak.
- A system with low damping responds only to a narrow band of driving frequencies centered at its natural frequency.
- A system with high damping responds to a broader range of driving frequencies but with smaller amplitude.

---

## Figure 7: The Tacoma Narrows Bridge in Torsional Oscillation

**Location:** Concept 3, introduction to resonance.

**Description:**
A photograph or sketch of the Tacoma Narrows Bridge showing the roadway twisting (in torsion). The bridge deck is shown rotated clockwise on one end and counterclockwise on the other, illustrating the torsional mode of oscillation. Include a timeline: "November 7, 1940, 11:00 a.m." and a caption explaining that wind at the bridge's natural torsional frequency drove the oscillations to failure.

Alternatively, show a sequence of three stills from the newsreel footage:
- Early in the oscillation: small amplitude, bridge is intact.
- Mid-oscillation: amplitude growing, visible twisting.
- Failure: the bridge deck has fractured and is falling into the water.

**What students should see:**
- Real structures have natural frequencies determined by their mass and stiffness.
- External forces (wind) can excite oscillations.
- Resonance can build amplitude to destructive levels.
- This is not an abstract mathematical phenomenon—it has real consequences.

---

## Figure 8: Quartz Crystal Oscillator (Cross-Section)

**Location:** Chapter opening or connections forward.

**Description:**
A cutaway diagram of a quartz crystal oscillator as used in digital watches:

- The quartz crystal (a rectangular or tuning-fork-shaped piece of silicon dioxide).
- Electrodes on the surface of the crystal.
- A circuit that drives the crystal at its resonant frequency.
- A frequency divider circuit that counts oscillations and produces a 1-Hz output.

Annotations:
- "Resonant frequency: 32,768 Hz"
- "$Q > 10,000$" (very high quality factor; very low damping in the crystal).
- "Frequency divider: 32,768 = $2^{15}$, so 15 stages of binary division produces exactly 1 Hz."

**What students should see:**
- Oscillatory systems are not just academic exercises; they are the basis of precise timekeeping.
- A high-$Q$ oscillator (low damping) maintains its frequency precisely.
- The choice of 32,768 Hz is deliberate: it is a power of 2, allowing easy digital division.

---

## Figure 9: The Angle Approximation for a Pendulum

**Location:** Concept 2, small-angle approximation.

**Description:**
A graph on the left showing $\sin \theta$ and $\theta$ (in radians) plotted together from $\theta = 0$ to $\theta = \pi/2$. The curves coincide for small $\theta$ and diverge for larger $\theta$. Mark the point $\theta = 15° \approx 0.26$ rad, where the error becomes ~1%. Mark $\theta = 45° \approx 0.785$ rad, where the error is ~7%.

On the right, show how the error in period varies with initial angle. For $\theta_0 = 5°$, the error is negligible. For $\theta_0 = 15°$, the error is ~0.1%. For $\theta_0 = 45°$, the error is ~7%. For $\theta_0 = 60°$, the error is ~20%.

**What students should see:**
- The small-angle approximation is good for small angles.
- A 1% error requires $\theta < 15°$.
- The approximation breaks down at large angles; the true period is longer.
- The approximation is the reason pendulum clocks work well: small swings keep the frequency constant.

---

## Caption Guidelines

Each figure should have:
- **Figure number and title** (e.g., "Figure 17.3: Energy Exchange in Simple Harmonic Motion").
- **Brief description** of what is shown (one or two sentences).
- **Key labels:** All axes, variables, and important points should be labeled clearly.
- **Reference in text:** Every figure is cited at least once in the chapter.

---

## Image Quality Standards

- All figures should be **clean, professional, and unambiguous**.
- Axes should be labeled with units.
- Colors should be used consistently (e.g., kinetic energy in one color, potential in another).
- Vector arrows should be proportional to their magnitudes (longer arrows for larger forces).
- Time-series plots should clearly mark the period $T$ or frequency $f$.

---

## Placeholder Status

As of 2026-05-07, all figure descriptions are provided. The actual image files can be generated using:
- **Python/Matplotlib** for graphs (Figures 2, 3, 5, 6, 9).
- **Adobe Illustrator or similar** for diagrams (Figures 1, 4, 7, 8).
- **Archival footage** for Figure 7 (existing video of Tacoma Narrows Bridge available in public domain).

Each figure title in the chapter is marked as `[FIGURE: ...]` in the draft, to be replaced with an embedded image reference during finalization.
