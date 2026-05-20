# Images and Visual Guides: Waves

Companion to Chapter 18. Each section corresponds to a key concept.

---

## Figure 1: Transverse vs. Longitudinal Waves

[FIGURE: Side-by-side diagrams]

**Left panel (Transverse wave on a string):**
- Horizontal axis labeled "Direction of wave propagation →"
- String shown with sinusoidal curve
- Arrows at two points on the string pointing vertically (up and down)
- Caption: "Each point on the string oscillates perpendicular to the wave's motion. The disturbance travels horizontally; the medium moves vertically."

**Right panel (Longitudinal wave in a spring):**
- Spring coils drawn in two states: relaxed spacing and compressed spacing
- Arrows at two locations showing compression and expansion
- Caption: "Each coil oscillates along the direction of wave propagation. Compressions and rarefactions (expansions) alternate."

---

## Figure 2: The Wave Function $y(x,t) = A \sin(kx - \omega t)$

[FIGURE: Snapshots at three times]

**Top row (t = 0):**
- Sinusoidal curve with peak at $x = \lambda/4$, trough at $x = 3\lambda/4$
- Vertical line at equilibrium labeled $y = 0$
- Wavelength $\lambda$ marked with a double-headed arrow
- Amplitude $A$ marked with an arrow from $y=0$ to peak

**Middle row (t = T/4):**
- Same sine curve, but shifted to the right by $\lambda/4$
- Annotation: "Wave moved a distance $vt = v \cdot T/4 = \lambda/4$ to the right"

**Bottom row (t = T/2):**
- Curve shifted right by $\lambda/2$ from $t = 0$
- Annotation: "At $t = T/2$, the wave has moved $\lambda/2$. The peak is now at $x = 3\lambda/4$."

**Bottom annotation:**
"The wave function $y(x,t) = A \sin(kx - \omega t)$ with $k = 2\pi/\lambda$ and $\omega = 2\pi/T = 2\pi f$ describes the position of every point at every time. The minus sign indicates motion in the positive $x$-direction."

---

## Figure 3: Particle Motion in a Transverse Wave

[FIGURE: Three panels showing a single point's trajectory]

**Left: Position of one point ($x = x_0$) over one period**
- Vertical axis: $y$ (displacement)
- Horizontal axis: $t$ (time)
- Sinusoidal curve showing $y(x_0, t) = A \sin(kx_0 - \omega t)$
- Points marked at $t = 0, T/4, T/2, 3T/4, T$
- Annotations showing: "Equilibrium, moving up" → "Maximum (crest)" → "Equilibrium, moving down" → "Minimum (trough)" → "Equilibrium, moving up"

**Center: Velocity of the same point**
- Vertical axis: $v_y = \partial y / \partial t = -A\omega \cos(kx_0 - \omega t)$
- Horizontal axis: $t$
- Cosine curve, 90° out of phase with position
- Annotation: "Velocity lags position by $T/4$, just like in simple harmonic motion"

**Right: Phase space diagram**
- Horizontal axis: $y$ (position)
- Vertical axis: $v_y$ (velocity)
- Elliptical path showing the trajectory in phase space
- Annotation: "The point traces an ellipse in phase space, returning to the same position and velocity each period."

---

## Figure 4: Energy in a Sinusoidal Wave

[FIGURE: Snapshot of one wavelength showing energy density]

**Top: Spatial profile at $t = 0$**
- Sinusoidal displacement curve
- Three locations marked: Node (equilibrium, no motion), Quarter-wavelength (maximum displacement), Antinode (for standing wave context, explained later)

**Middle: Kinetic energy density $\propto v_y^2$**
- Curve showing where $v_y$ is maximum (at equilibrium) and zero (at crests/troughs)
- Shaded regions indicate high kinetic energy

**Bottom: Potential energy density (elastic strain)**
- Curve showing where elastic energy is stored (maximum curvature, near crests/troughs)
- Complementary pattern to kinetic energy

**Overall caption:**
"In a traveling sinusoidal wave, kinetic and potential energy oscillate between locations. At equilibrium, kinetic energy is maximum; the string moves fastest. At maximum displacement, potential energy is maximum; the string is most curved. The total energy per wavelength is constant in an undamped wave."

---

## Figure 5: Superposition and Interference

[FIGURE: Three rows of waveforms]

**Row 1: Two waves in phase (constructive interference)**
- Left column: Red sine curve (Wave 1)
- Center column: Blue sine curve (Wave 2), identical to Wave 1
- Right column: Black curve (Sum), with amplitude $2A$
- Caption: "When crests align with crests and troughs with troughs, the amplitudes add: $y_{\text{total}} = 2A \sin(kx - \omega t)$"

**Row 2: Two waves 180° out of phase (destructive interference)**
- Left column: Red sine curve (Wave 1)
- Center column: Blue inverted sine curve (Wave 2)
- Right column: Black line at $y = 0$ (Sum cancels to zero)
- Caption: "When crests of one wave align with troughs of the other, they cancel: $y_{\text{total}} = 0$"

**Row 3: Two waves at intermediate phase difference**
- Left column: Red sine curve
- Center column: Blue sine curve, phase-shifted by ~90°
- Right column: Black curve (Sum) with intermediate amplitude, shifted phase
- Caption: "General case: the sum is another sinusoid, with amplitude and phase determined by the phase difference between the input waves."

---

## Figure 6: Standing Wave on a String (Fundamental and Second Harmonic)

[FIGURE: Two snapshots of string motion, showing fundamental and second harmonic modes]

**Top panel (Fundamental, $n = 1$):**
- String shown at three times: $t = 0$ (maximum displacement), $t = T/4$ (passing through equilibrium), $t = T/2$ (maximum in opposite direction)
- Red dots at both ends (fixed boundaries = nodes)
- Blue dot at midpoint (antinode, oscillates with maximum amplitude)
- Wavelength $\lambda_1 = 2L$ marked
- Caption: "The fundamental mode fits half a wavelength between the fixed ends. The entire string oscillates in unison, all reaching maximum displacement at the same time."

**Bottom panel (Second harmonic, $n = 2$):**
- String shown at same three times
- Red dots at both ends and at midpoint (nodes)
- Two blue dots at 1/4 and 3/4 along the string (antinodes, oscillating out of phase with each other)
- Wavelength $\lambda_2 = L$ marked
- Caption: "The second harmonic fits one full wavelength. The left and right halves oscillate in opposite directions, meeting at the midpoint node."

**Common annotation for both:**
"In each mode, the standing wave is $y(x,t) = 2A \sin(kx) \cos(\omega t)$. The spatial factor $\sin(kx)$ determines the nodes (where $\sin(kx) = 0$) and antinodes (where $|\sin(kx)| = 1$). The temporal factor $\cos(\omega t)$ means all points oscillate at the same frequency $\omega = 2\pi f_n$."

---

## Figure 7: Resonance and the Tuning of a String

[FIGURE: Driving frequency vs. amplitude response curve]

**Horizontal axis:** Driving frequency $f$ (frequency at which you shake the string)

**Vertical axis:** Amplitude at antinode $A_{\text{max}}$

**Curve:** Sharp peaks at $f_1, f_2 = 2f_1, f_3 = 3f_1$, etc. (the natural frequencies).

**Bottom:** Smooth baseline curve showing small-amplitude background oscillations at all frequencies.

**Annotations:**
- "If the string is driven at a frequency that does not match any natural frequency, the oscillations are small."
- "At $f = f_1 = v/(2L)$ (the fundamental), resonance occurs, and the amplitude grows large."
- "At $f = f_2, f_3, \ldots$ (harmonics), secondary resonances occur with progressively smaller amplitudes."
- "In a real string with damping, the peaks are broadened; in the ideal case, they are infinitely sharp."

---

## Figure 8: Tsunami Wave Speed in Shallow Water

[FIGURE: Ocean profile showing waves in different depths]

**Horizontal axis:** Distance from shore

**Vertical axis:** Water depth (not to scale)

**Regions:**
1. **Deep ocean** ($h = 4$ km): Wave shown with small amplitude, widely spaced crests. Label: "Speed $v = \sqrt{gh} = 200$ m/s. Wavelength $\lambda$ large; amplitude $A$ small."

2. **Continental shelf** ($h = 500$ m): Wave with slightly increased amplitude, closer-spaced crests. Label: "Depth 1/8 of deep ocean; speed drops to 56 m/s. Energy concentrates into shorter wavelength."

3. **Shallow water** ($h = 10$ m): Wave with very large amplitude, short wavelength. Label: "Shallow water; speed 10 m/s. Amplitude can exceed 10 m. Wave begins to steepen."

4. **Shore break:** Heavily stylized wave breaking on beach.

**Bottom caption:**
"As a tsunami approaches shallow water, the wave speed decreases ($v \propto \sqrt{h}$), so the wavelength shortens ($\lambda = vf$, and $f$ is constant). The same energy is compressed into a smaller distance, so the amplitude grows dramatically. This is why tsunamis pose such a hazard near the coast."

---

## Figure 9: Wave Parameters Quick Reference

[FIGURE: Single sinusoidal wave with all parameters labeled]

**Horizontal axis:** Position $x$

**Vertical axis:** Displacement $y$

**Sinusoidal curve with annotations:**
- Peak marked: $y = A$ (amplitude)
- Trough marked: $y = -A$
- Distance between two consecutive peaks: $\lambda$ (wavelength) with double-headed arrow
- At peak, arrow showing "Crest"
- At trough, arrow showing "Trough"
- Two consecutive "identical points" marked and distance between them labeled $\lambda$
- Slope of the curve at equilibrium marked and labeled "Slope $\partial y / \partial x$ maximum at equilibrium"

**Inline text boxes:**
- Wavelength: $\lambda$ (meters)
- Frequency: $f = v / \lambda$ (hertz)
- Period: $T = 1 / f$ (seconds)
- Wave number: $k = 2\pi / \lambda$ (rad/m)
- Angular frequency: $\omega = 2\pi f$ (rad/s)
- Wave speed: $v = \lambda f = \omega / k$ (m/s)

---

## Figure 10: The Wave Equation in Physical Terms

[FIGURE: Curved string segment with forces and acceleration labeled]

**Setup:** Small element of string of length $\Delta x$, mass $\Delta m = \mu \Delta x$

**Left endpoint:** Tension force $F_T$ at angle $\theta_1$ to the horizontal. Component balances along $x$; vertical component contributes to net force upward/downward.

**Right endpoint:** Tension force $F_T$ at angle $\theta_2$. Vertical component.

**Net vertical force:** $F_{\text{net}} = F_T (\sin \theta_2 - \sin \theta_1) \approx F_T (\tan \theta_2 - \tan \theta_1) = F_T (\partial y / \partial x|_{x + \Delta x} - \partial y / \partial x|_x)$

**Newton's second law:** $F_{\text{net}} = \Delta m \cdot a_y = \mu \Delta x \cdot \partial^2 y / \partial t^2$

**Final equation:** $F_T \frac{\partial^2 y}{\partial x^2} = \mu \frac{\partial^2 y}{\partial t^2}$, or $\frac{\partial^2 y}{\partial x^2} = \frac{1}{v^2} \frac{\partial^2 y}{\partial t^2}$ with $v = \sqrt{F_T / \mu}$.

**Caption:**
"The wave equation emerges directly from Newton's second law applied to a small element. The acceleration of the element is driven by the difference in slope on either side (the curvature). The curvature drives the motion."

---

## Figure 11: Energy Flow in a String

[FIGURE: Wave traveling to the right; power flow illustrated]

**String segment:** Sinusoidal wave shown in two snapshots: early time and slightly later time.

**At one point ($x = x_0$):** Arrow showing the instantaneous vertical velocity $v_y$.

**Force on that point:** Tension $F_T$ acts on the string at an angle $\theta$ to the horizontal. The vertical component of tension is $F_T \sin \theta \approx F_T (\partial y / \partial x)$.

**Power at that point:** $P = $ (vertical component of force) $\times$ (vertical velocity) $= F_T (\partial y / \partial x) \times (\partial y / \partial t)$.

**Shading on the wave:** Regions of positive power (energy flowing to the right) shown in one color; regions of negative power (energy temporarily flowing left) in another. The net power averaged over one period is positive to the right.

**Caption:**
"Power flows through the medium as the product of force and velocity. In a traveling wave, power is continuously delivered by the driving source and continuously absorbed (in a damped medium) or redistributed (in an ideal medium). The average power $P_{\text{ave}} = \frac{1}{2} \mu A^2 \omega^2 v$ represents the sustained energy flux."

---

## Figure 12: Boundary Conditions and Reflections

[FIGURE: Three scenarios of wave reflection at boundaries]

**Left panel (Fixed boundary):**
- Incident wave moving right, shown as red
- At the wall: phase inverts, so the reflected wave (blue) is an upside-down version moving left
- At the wall boundary: $y = 0$ always
- Caption: "Fixed boundary: The wave cannot move the boundary, so the boundary exerts a reaction force that inverts the phase. Crest reflects as trough."

**Center panel (Free boundary):**
- Incident wave moving right (red)
- At the free end: ring of negligible mass on a frictionless pole
- Reflected wave (blue) has same phase as incident
- At the boundary: $\partial y / \partial x = 0$ (string is horizontal)
- Caption: "Free boundary: The boundary is free to move, so there is no reaction force to invert the phase. Crest reflects as crest."

**Right panel (Impedance mismatch):**
- Incident wave moving right on string 1 (light)
- Meets string 2 (heavy) at boundary
- Partial reflection (blue, inverted because the heavy string resists motion)
- Partial transmission (black, moving right on string 2)
- Caption: "Impedance mismatch: Some energy reflects, some transmits. The fraction reflected depends on the impedance ratio $Z_1 / Z_2$."

---

## Sketch Prompts for Students

1. **Sketch a standing wave on a string of length $L$ showing:**
   - The first three modes ($n = 1, 2, 3$)
   - Location of nodes and antinodes for each
   - Wavelength $\lambda_n$ for each mode
   - Which mode has the longest wavelength?

2. **Sketch a point on a string oscillating in simple harmonic motion as a traveling wave passes through, showing:**
   - Position $y(x_0, t)$ vs. time over two periods
   - Velocity $v_y(x_0, t)$ vs. time
   - Acceleration $a_y(x_0, t)$ vs. time
   - Phase relationships between these three

3. **Sketch the energy density (kinetic + potential) in one wavelength of a sinusoidal traveling wave, showing:**
   - Where kinetic energy is maximum (particle velocity maximum)
   - Where potential energy is maximum (curvature maximum)
   - How the total energy is distributed

4. **Sketch two waves with the same frequency but different amplitudes interfering:**
   - Show the two incident waves
   - Show the resultant wave
   - Label the amplitude of the resultant as a function of phase difference

---

## Animation Suggestions (if creating video or interactive content)

1. **Traveling wave visualization:** Sinusoidal string oscillation moving left to right. Show the wave function $y(x,t)$ updating in time. Add particle-velocity vectors at several points to show perpendicular motion.

2. **Standing wave formation:** Incident and reflected waves traveling in opposite directions. Gradually increase the overlap until a standing wave appears. Highlight nodes and antinodes.

3. **Energy oscillation:** Show kinetic and potential energy densities in a single wavelength, updating as the wave evolves. Use color: blue for kinetic, red for potential.

4. **Resonance:** Drive a string at different frequencies. Show small oscillations off-resonance, and large oscillations at $f_1, f_2, f_3$. Illustrate how the amplitude peaks at these natural frequencies.

5. **Tsunami approach:** Ocean profile showing waves in deep water, continental shelf, and shallow water. Shrink the wavelength and grow the amplitude as depth decreases. Show the wave slowing down.

