# Bookmap: Chapter 17 Oscillations (Source Analysis)

**Source:** OpenStax *University Physics*, Volume 1, Chapter 15 (Oscillations). Seven modular sections, ~15,500 words.

**Date mined:** 2026-05-07

**Voice:** Attenborough × Feynman (narrative-explanatory; mechanisms first; scene-anchored openings where possible)

---

## Source Section-by-Section Breakdown

### Section m58360 — Introductory Hook

**Content:** Two sentences on the Comcast Building (Philadelphia, 305m tall, 300,000-gallon tuned-mass damper on top to reduce oscillations from wind and seismic activity).

**What it teaches:** 
- Real buildings oscillate and must be damped.
- Tall buildings are inverted physical pendulums.
- Engineers solve oscillation problems with mass dampers.

**Useful for the chapter:** 
- The Comcast Building is mentioned but not the scene-opener (the Tacoma Narrows Bridge is more dramatic and more directly illustrates resonance failure). The section provides a contemporary engineering example of damping in practice.

**For future chapters (waves, structural dynamics):**
- Buildings as coupled oscillators with multiple modes.
- Seismic isolation and tuned-mass dampers as applications of resonance.
- The physics of skyscraper design.

---

### Section m58361 — Simple Harmonic Motion and the Equations of Motion

**Content:** 
- Definition of period $T$ and frequency $f = 1/T$.
- Characteristics of SHM: acceleration proportional to displacement, opposite direction.
- Position equation: $x(t) = A \cos(2\pi t / T) = A \cos(\omega t)$.
- Velocity: $v(t) = -A \omega \sin(\omega t + \phi)$.
- Acceleration: $a(t) = -A \omega^2 \cos(\omega t + \phi)$.
- Period and frequency of a mass on a spring: $T = 2\pi\sqrt{m/k}$, $f = (1/2\pi)\sqrt{k/m}$.
- Vertical spring motion: gravity shifts equilibrium but does not change the period.

**Worked examples in source:**
1. Ultrasound machine emits at 0.400 μs period → frequency 2.50 MHz.
2. 2.00-kg mass on 32.00 N/m spring pulled to 0.020 m → equations of motion.

**What it teaches:**
- The mathematical form of SHM.
- Period depends only on mass and spring constant, not amplitude.
- Gravity shifts equilibrium without affecting oscillation frequency.
- The connection between the physical setup and the differential equation.

**Useful for the chapter:**
- This is the backbone of Concept 1. Used almost verbatim.
- The ultrasound example is replaced with a quartz crystal example (more relevant to modern devices).
- The mass-spring example is kept and expanded.

**For future chapters:**
- Coupled oscillators (two masses on springs connected together).
- Resonance in mechanical and electrical systems.
- The wave equation (continuous chain of coupled oscillators).

---

### Section m58362 — Energy in SHM

**Content:**
- Potential energy stored in a spring: $U = \frac{1}{2}kx^2$.
- Total energy: $E = \frac{1}{2}kA^2$ (constant).
- Energy oscillates between kinetic and potential.
- Velocity from energy: $|v| = \sqrt{(k/m)(A^2 - x^2)}$.
- Stable vs. unstable equilibrium (marble in a bowl).
- Van der Waals interaction and the Lennard-Jones potential as a nonlinear example.

**Worked example in source:**
- None explicit, but the energy diagram shows the conversion at specific points.

**What it teaches:**
- Energy conservation in oscillations.
- The relationship between energy and amplitude.
- Stable equilibrium points (restoring force toward equilibrium).
- Nonlinear systems (Lennard-Jones) behave like SHM near equilibrium if you expand to first order.

**Useful for the chapter:**
- The energy section in Concept 2 is drawn directly from this.
- The Lennard-Jones example is excluded as too advanced for this level; the chapter focuses on harmonic systems.
- The marble-in-bowl analogy is kept for stable/unstable equilibrium intuition.

**For future chapters:**
- Potential-energy-based analysis (how to recognize SHM-like behavior in any potential).
- Nonlinear oscillations (larger oscillations, elliptic integrals).
- Molecular dynamics (atoms in a crystal oscillate about equilibrium positions).

---

### Section m58363 — Connection Between SHM and Circular Motion

**Content:**
- A rotating peg casting a shadow oscillates like a mass on a spring.
- The projection of uniform circular motion onto a diameter undergoes SHM.
- This analogy explains why $v = A \omega$ and $a = A \omega^2$.

**What it teaches:**
- Geometric intuition for SHM (the shadow is the component of circular motion).
- Why velocity leads position by 90°.
- Why acceleration is proportional to displacement.

**Useful for the chapter:**
- This is a beautiful geometric insight, but it is not essential to the narrative. The chapter explains SHM through the differential equation and solution, which is more direct.
- The analogy could be mentioned in a remarks or as a way to remember the phase relationships, but it is not the primary explanation.

**For future chapters:**
- Phasor diagrams (rotating vectors for AC circuits).
- The representation of oscillatory motion in the complex plane.

---

### Section m58364 — The Pendulum

**Content:**
- Simple pendulum: $T = 2\pi\sqrt{L/g}$.
- Period independent of mass and amplitude (for small angles).
- Small-angle approximation: $\sin\theta \approx \theta$ for $\theta < 0.26$ rad (15°).
- Physical pendulum: $T = 2\pi\sqrt{I/(mgd)}$.
- Torsional pendulum: $T = 2\pi\sqrt{I/\kappa}$.

**Worked examples in source:**
1. Pendulum of length 0.75000 m has period 1.7357 s; solve for $g$.
2. Skyscraper sway-damping design: 100-ton pendulum with frequency 0.50 Hz; find required length (answer: 1.49 m).
3. Torsional pendulum: 4.00-kg rod, length 0.30 m, period 0.5 s; find torsion constant.

**What it teaches:**
- The period formula for a simple pendulum.
- The small-angle approximation and when it breaks down.
- That physical and torsional pendulums follow the same mathematics, just with different quantities.
- Practical engineering applications (buildings, dampers).

**Useful for the chapter:**
- The simple pendulum is Concept 2. The source material is used directly.
- The skyscraper damper example is included in Concept 3 (resonance and damping).
- The torsional pendulum is mentioned briefly but not fully explained (it is a generalization; the chapter focuses on simpler systems).

**For future chapters:**
- Coupled pendulums (two or more pendulums linked by springs or strings).
- Bifurcation (how the pendulum can "flip" at large amplitudes).
- Chaos (nonlinear pendulum driven at certain frequencies exhibits chaotic motion).

---

### Section m58365 — Damped Harmonic Motion

**Content:**
- Damping force proportional to velocity: $F_d = -b v$.
- Equation of motion: $m d^2x/dt^2 + b dx/dt + kx = 0$.
- Solution (underdamped): $x(t) = A_0 e^{-bt/2m} \cos(\omega t + \phi)$ with $\omega = \sqrt{\omega_0^2 - (b/2m)^2}$.
- Critical damping: $b_c = 2\sqrt{mk}$.
- Three regimes: underdamped, critically damped, overdamped.

**Worked examples in source:**
- Graphs showing the three regimes.
- Qualitative discussion of car shock absorbers (critically damped is desired).

**What it teaches:**
- How friction removes energy from oscillations.
- The exponential decay envelope.
- Why car suspensions are designed to be critically damped (fast return without oscillation).

**Useful for the chapter:**
- This is the core of Concept 3. The chapter uses the material directly and adds more discussion of the physics.

**For future chapters:**
- Stochastic damping (noise-driven oscillations).
- Fluctuation-dissipation theorem (at the molecular level, damping is related to thermal fluctuations).
- Electrical analogs (resistor in an RLC circuit).

---

### Section m58366 — Driven Oscillations and Resonance

**Content:**
- Driving force: $F_d = F_0 \sin(\omega_d t)$.
- Equation: $m d^2x/dt^2 + b dx/dt + kx = F_0 \sin(\omega_d t)$.
- Steady-state amplitude: $A(\omega_d) = F_0 / \sqrt{m^2(\omega_d^2 - \omega_0^2)^2 + b^2 \omega_d^2}$.
- Resonance occurs at $\omega_d = \omega_0$ (approximately; correction for damping is small).
- Maximum amplitude at resonance: $A_{\max} = F_0 / (b\omega_0)$.
- Quality factor: $Q = \omega_0 / \Delta\omega$ where $\Delta\omega$ is the width at half-maximum amplitude.
- Practical example: piano strings resonating to a loud note.

**Worked examples in source:**
- Paddle ball on an elastic band (pushing at the natural frequency amplifies the bounce).
- Radio circuit tuned to a specific frequency.
- London Millennium Footbridge ("Wobbly Bridge") — pedestrians excited the bridge's natural frequency.

**What it teaches:**
- How driving a system at its natural frequency leads to large-amplitude oscillations.
- The relationship between damping and the sharpness of resonance.
- Real-world consequences of resonance (bridge sway, structural failure).

**Useful for the chapter:**
- This is the core of Concept 3. The chapter adds the Tacoma Narrows Bridge as the primary example (more dramatic and earlier than the Millennium Bridge).
- The $Q$ factor is explained in detail.

**For future chapters:**
- Forced harmonic oscillators in phase space (limit cycles).
- Subharmonic resonance (driving at a multiple of the natural frequency).
- Parametric resonance (when the driving force modulates the system's parameters, e.g., pushing a swing by changing the rope length).

---

## Ideas Harvest: For Future Chapters in University Physics

### Structural mechanics and earthquakes
- How do buildings respond to seismic waves?
- What is the relationship between oscillation frequency and structural damage?
- How do base isolators (springs under buildings) protect structures?

### Waves (Chapter 16)
- Waves are oscillations in space and time.
- A traveling wave can be modeled as a coupled chain of oscillators.
- The wave equation emerges from the oscillator equations with coupling.
- Dispersion: how the wave speed depends on frequency.

### Sound (Chapter 17 following)
- Sound is a longitudinal wave of pressure oscillations.
- The frequency of the oscillation determines the pitch.
- Resonance in musical instruments (air columns, vibrating strings).
- The Doppler effect: how motion changes the observed frequency.

### Energy and work
- Work done against a spring: $W = \int F \, dx = \int kx \, dx = \frac{1}{2}kx^2$.
- Energy stored in oscillations: potential, kinetic, and total mechanical energy.
- Energy dissipation through damping.

### Circular motion and rotation (Chapter 10, but connections)
- Angular frequency and tangential velocity.
- Rotational kinetic energy of the oscillating system.
- Moment of inertia in the pendulum problem.

### Coupled oscillators (advanced topic, not in this book)
- Two masses on springs connected together.
- Normal modes: each mode oscillates independently.
- Beating: when two nearly equal frequencies interfere.

### Nonlinear oscillations (advanced, not in this book)
- Anharmonic potentials (not Hooke's law).
- The period depends on amplitude.
- Bifurcations and chaos.

### Quantum oscillators (not in this book, but forward reference)
- The quantum harmonic oscillator is one of the few exactly solvable problems.
- Energy levels are quantized: $E_n = \hbar \omega_0 (n + 1/2)$.
- This leads to spectroscopy (infrared absorption by vibrating molecules).

---

## Structural Moves to Use in Future Chapters

1. **Scene-first opening:** The Tacoma Narrows Bridge (a specific place, a specific date, a concrete failure) draws the reader in before abstracting to the mathematics.

2. **Specification before abstraction:** Name what you mean by "period," "frequency," "amplitude," and "phase shift" before solving equations.

3. **Showing the derivation on the page:** The differential equation $d^2x/dt^2 = -\omega_0^2 x$ is not presented as a magical truth, but derived from Newton's second law and Hooke's law.

4. **Analogies that illuminate:** The rotating peg casting a shadow is a clear picture of why velocity is 90° ahead of position.

5. **Trade-offs named:** The chapter explicitly discusses where the linear model works and where it breaks down.

6. **Energy perspective:** Viewing oscillations through the lens of energy conservation provides intuition that the equations alone do not.

7. **Graded complexity:** Start with the simplest case (mass on a spring, no damping), then add complications (vertical spring, damping, driving force).

---

## Misconceptions Addressed (Model for Other Chapters)

The source material lists conceptual questions but often does not deeply address why students believe the misconceptions. The chapter improves this by:

- **Explicit correction:** "Not this; actually that."
- **Intuition check:** "Here's why your intuition might have led you astray."
- **Counter-example:** "Consider what happens if you change the amplitude and see that the frequency does not change."

This model should be applied to other chapters: whenever a misconception is addressed, explain why it is plausible, why it is wrong, and what the correct understanding is.

---

## Primary vs. Secondary Sources

The source OpenStax text is a secondary source—it synthesizes the physics but does not derive the physics from first principles or from historical sources. For deeper understanding, students could consult:

- **Huygens, *Horologium oscillatorium* (1673):** Original derivation of the pendulum period.
- **Euler's work on damped oscillations:** Foundation of the theory.
- **Rayleigh, *The Theory of Sound* (1877):** Classical treatment of resonance and damping.
- **Modern physics textbooks:** Quantum harmonic oscillator.

The chapter does not require these sources, but they provide context for why the topic matters historically and what the next level of understanding looks like.

---

## Verification of All Claims

All major claims in the chapter are verifiable:

1. **Period formula for a spring:** Derived directly from Newton's second law and verified experimentally in countless introductory physics labs.
2. **Period formula for a pendulum:** Derived from torque balance; verified for small angles; error grows predictably for large angles.
3. **Amplitude-frequency response:** Measured in resonance experiments (mechanical, electrical, acoustic); the formula is standard in every dynamics textbook.
4. **Tacoma Narrows failure date and cause:** Extensively documented; November 7, 1940 is the accepted date; resonance-driven torsional oscillation is the accepted cause.
5. **Quartz crystal frequency:** 32,768 Hz is the standard; it is $(2^{15})$ Hz for easy digital division.
6. **Car shock absorber design:** Critical damping is standard engineering practice.

All etymologies are from standard dictionaries.

---

**End of bookmap.**
