# Bookmap: Chapter 14 — Gravitation

**Source:** University Physics (OpenStax), Chapter 13 (Gravitation)  
**Voice:** Attenborough × Feynman v1.1  
**Date:** May 7, 2026

---

## Overview

The OpenStax source material is organized into six sections: (1) Newton's law and the Cavendish experiment, (2) gravitation near Earth's surface and apparent weight, (3) gravitational potential energy and escape velocity, (4) satellite orbits and energy, (5) Kepler's laws and elliptical orbits, and (6) tidal forces and general relativity.

The current chapter distills sections 1, 3, 4, and 5 into three concepts arranged vertically: the law itself (Newton), energy and escape (potential), and orbits (Kepler). Sections 2 and 6 are deferred to other contexts (section 2 to rotational motion and Earth's structure; section 6 to a dedicated treatment of tides and relativistic gravity).

This bookmap extracts the pedagogical machinery worth reusing: where the source succeeds at clarity, what it hides, where it might go deeper.

---

## What the source teaches well

**The torsion balance and Cavendish.** The source dedicates a full example to the apparatus and the measurement. This is excellent. It grounds an abstract physical constant ($G$) in a concrete experiment. The student sees:
- The apparatus itself (quartz fiber, lead masses, twist angle)
- How tiny the force is (micronewtons)
- How ingenious the measurement (detecting a twist too small to see without magnification)
- The historical context (1798; G verified to modern precision)

This cold open was retained in the new chapter, and the source provided the concrete details needed.

**The inverse square law from geometry.** The source mentions it briefly: force spreads over a sphere of area $4\pi r^2$, so it goes as $1/r^2$. This is the core insight. The new chapter expands this, making the geometry explicit and pointing out that the same law applies to light, sound, and electrostatics. The source's brevity left room for deepening.

**Escape velocity as a condition on total energy.** The source derives it cleanly: set total energy to zero at infinity, $\frac{1}{2}mv^2 - \frac{GMm}{R} = 0$, solve for $v$. The source also notes that escape velocity is independent of the mass escaping (beautiful, counterintuitive). The new chapter kept this derivation and added the interpretation: escape velocity is the speed at which you have exactly enough kinetic energy to reach infinity with zero speed remaining.

**Kepler's Third Law from circular orbits.** The source shows that $T^2 \propto a^3$ follows from Newton's law, not the other way around. This inversion of historical order is pedagogically powerful: Newton explains Kepler, not vice versa. The source correctly distinguishes between the historical observation and the physical explanation.

**Kepler's Second Law from angular momentum.** The source shows that constant areal velocity is equivalent to constant angular momentum, and that constant angular momentum follows from the fact that gravity is a central force (no torque). This is elegant. The source walks through it step-by-step, and the new chapter preserved the reasoning.

---

## What the source underexplains

**The reference point for potential energy.** The source sets $U = 0$ at infinity and explains it is a choice for convenience. But it does not elaborate on why this choice is natural. The new chapter added:
- The intuition: to pull two masses apart requires doing positive work, so potential energy increases (becomes less negative) as you separate them
- The contrast with near-Earth potential energy ($U = mgh$, where we usually choose $U = 0$ at ground level), showing that potential energy is defined only up to an additive constant

**Why $G$ is so small.** The source calculates $G = 6.67 \times 10^{-11}$ but does not address the mystery: why is gravity so much weaker than other forces? The new chapter named this in the "Still puzzling" section, acknowledging that the hierarchy of forces is an open question.

**The principle of equivalence.** The source mentions it briefly in the context of astronauts appearing weightless in orbit. But it does not explain it in detail or make clear how radical the principle is (that gravity and acceleration are indistinguishable locally). The new chapter has one mention in the synthesis section, enough to signal the idea without claiming to explain it fully.

**Why the Moon orbits where it does.** Given Earth's mass and the Moon's distance, Kepler's Third Law tells us the orbital period. But the source does not ask: what determined the Moon to be at this particular distance? (The answer involves the formation of the Earth-Moon system and tidal locking, topics beyond this chapter's scope.) The new chapter did not add this, but it is a natural follow-up question.

---

## What the source omits or gets wrong

**Tidal forces.** The source has a long section on tides, including spring and neap tides, the Bay of Fundy, and Io's volcanism. This material is important but tangential to the core of gravitation mechanics. The new chapter omitted it, noting in the "Gaps" section that tides deserve their own treatment. A student who has read this chapter and wants to understand tides should read a section dedicated to the subject, with the machinery of differential forces made explicit.

**General relativity.** The source has a final section on Einstein, the principle of equivalence, black holes, and the Schwarzschild radius. This is excellent material, but it is not core to understanding Newton's gravitation. The new chapter notes in the synthesis that general relativity is the deeper truth, but reserves a full treatment for a later book (Relativity volume).

**Atmospheric drag and orbital decay.** Real satellites lose energy to air resistance and spiral inward. The source does not address this. The new chapter omitted it as well (it is a practical detail, not a fundamental concept), but it would be a natural extension for engineering applications.

---

## Angles and framings the source doesn't use (but could)

**Gravity as the limit of strong interactions.** In the early universe, gravity was unified with the other forces. As the universe cooled, gravity decoupled and became the weakest force by far (because it was diluted into extra dimensions?). This is speculative, but it reframes the question: gravity is not weak by nature; it became weak through the history of the universe. The source does not mention this angle.

**Orbital mechanics as a design constraint.** Where you place a satellite (altitude, inclination, eccentricity) determines not only what it can see or when, but how much fuel is required, how long it lasts before decay, and whether it can maintain its position. The source calculates orbital speed and period but does not frame them as constraints on engineering. An engineer reading this chapter would benefit from seeing the trade-offs.

**The Moon's recession from Earth.** Tidal friction is gradually transferring angular momentum from Earth's rotation to the Moon's orbit. The Moon is receding from Earth at about 3.8 cm per year. Eventually (billions of years hence) the Earth and Moon will be tidally locked to each other. This is a macroscopic example of conservation of angular momentum in action. The source mentions tidal locking of the Moon to Earth but not the ongoing process.

**Lagrange points and mission design.** When two masses orbit each other, there are five points in the orbital plane where the gravitational forces of the two masses plus the centrifugal effect exactly balance. The James Webb Space Telescope sits at the Sun-Earth L2 point. The source does not mention these, but they are natural consequences of the gravitational machinery and important for modern space missions.

---

## Specification moves the source makes (and the new chapter retained)

The source is careful to distinguish:
- **Gravitational mass vs. inertial mass.** The source notes that Newton assumed they were equal and that experiments verify this to high precision. The new chapter expanded this: the equivalence is not a theorem but an experimental fact, and it motivated Einstein's general relativity.
- **Weight vs. mass.** The source defines weight as the gravitational force (Newton's) rather than the quantity $m$ itself. This is correct and important. The new chapter retained this language.
- **Escape velocity vs. orbital velocity.** The source clarifies that escape velocity ($\sqrt{2GM/R} \approx 11.2$ km/s for Earth) is not the same as orbital velocity ($\sqrt{GM/R} \approx 7.9$ km/s). The new chapter kept both examples and the common misconception that they are the same.
- **Perihelion vs. perigee, aphelion vs. apogee.** The source names both pairs: the first for orbits around the Sun, the second for orbits around Earth. The new chapter used the Sun-centric terminology (perihelion/aphelion) as the primary example.

---

## Ideas harvest: What a future chapter could mine from the source

**For a chapter on tides:**
- The source's detailed calculation of tidal forces on a 1-kg mass: how the Moon's pull differs between near and far sides of Earth
- The comparison of tidal effects from Moon vs. Sun (Moon is stronger despite Sun's larger gravitational force, because the fractional change in distance is larger)
- Spring tides (full or new moon, alignment of Sun-Earth-Moon) vs. neap tides (half-moon, right angle)
- Io's volcanism as evidence of tidal heating
- The Bay of Fundy as an example of topographic amplification

**For a chapter on general relativity:**
- The principle of equivalence: free fall and weightlessness are indistinguishable
- Space-time curvature as the explanation for gravity
- The Schwarzschild radius: $R_S = 2GM/c^2$
- Black holes and the event horizon
- Evidence for black holes from stellar orbits at the Galactic center (UCLA Galactic Group, 4 million solar masses)
- Dark matter: the galaxy rotation problem discovered by Vera Rubin

**For a chapter on astrophysics and stellar evolution:**
- How to measure the mass of a distant star using the orbital period and radius of a companion
- The mass-luminosity relation: more massive stars burn hotter and die younger
- Why neutron stars and black holes form (gravitational collapse at the end of stellar life)
- The density required to form a black hole: the Sun would need to be compressed to a 3-km radius

---

## Bridges to adjacent chapters

**From Chapter 13 (Angular Momentum):**
The conservation of angular momentum is not invoked until Kepler's Second Law in this chapter. But it is the same conserved quantity from Chapter 13. A student should see the continuity: angular momentum is conserved whenever torque is zero, and gravity exerts no torque about the center, so angular momentum is conserved in all orbits.

**To Chapter 15 (Fluid Mechanics):**
Gravity acts on fluids. The pressure in the ocean increases with depth because of the weight of water above. Gravity also drives atmospheric circulation. These belong in a chapter on fluids, but they depend on understanding gravitational force.

**To Relativity (later volume):**
The Schwarzschild radius formula appears in this chapter as a curiosity: it gives the radius inside which light cannot escape a mass. But the full meaning requires general relativity. A student who has seen this formula has a hook to hang the later material on.

---

## Pedagogical notes on what worked

The source's decision to organize chronologically (history of gravitation → Newton's law → applications → Kepler → Einstein) is effective for narrative but pedagogically less powerful than the conceptual organization used in the new chapter (law → energy → orbits). The new chapter groups ideas that support each other: the law explains why escape velocity has the form it does, which is needed to understand energy considerations in orbits.

The source's use of many worked examples is excellent. The new chapter retained the three most conceptually dense and added brief calculations inline to show the method without belaboring the point.

The source's inclusion of the Cavendish experiment is exactly right: it grounds the abstract constant $G$ in a real measurement and builds credibility for Newton's law.

---

## Unused source material (and why)

- **Gravitational field lines.** The source shows a diagram of field lines pointing radially inward toward a mass, with spacing indicating field strength. This is useful for intuition but not essential. The new chapter omitted it to stay focused.
- **The problem of action-at-a-distance.** The source mentions that Newton's law assumes instantaneous gravitational force across arbitrary distances, which troubled scientists for centuries until relativity showed that gravity propagates at the speed of light (as gravitational waves). This is historically interesting but beyond the scope.
- **Binary star systems.** The source has an example of two galaxies (Milky Way and Andromeda) orbiting their common center of mass. This is rich material but adds complexity to an already full chapter. A follow-up chapter could expand this.
- **Hohmann transfer orbits.** The source discusses the most fuel-efficient path from Earth to Mars (a half-ellipse with perihelion at Earth and aphelion at Mars). This is important for space mission design but requires simultaneous comfort with both circular and elliptical orbits. The new chapter did not include it, but it is a natural extension problem for students comfortable with the core concepts.

---

## How the source compares to peer texts

**Compared to Halliday, Resnick, & Walker:**
- The OpenStax source is more narrative and historically grounded (Cavendish, Kepler, Newton).
- H&R is more procedural: here's the law, here's how to apply it, here are worked examples.
- The OpenStax source gives more attention to special cases (apparent weight from Earth's rotation, gravity at different altitudes).

**Compared to Serway & Jewett:**
- OpenStax and Serway both use the inverse square law as the organizing principle.
- Serway spends more time on the mathematical structure of orbits (polar coordinates, conic sections).
- OpenStax is more accessible to students with less math background; Serway assumes more calculus fluency.

The new chapter tries to thread the needle: accessible prose (Attenborough × Feynman), but calculus on the page (showing derivations, not just results).

