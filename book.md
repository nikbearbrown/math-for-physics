# University Physics

## Title
University Physics — Mechanics, Waves, and the Mathematics Behind Both

## Subtitle
The calculus-based introductory sequence — measurement, vectors, kinematics, dynamics, energy, momentum, rotation, gravity, fluids, oscillations, waves, sound — with the derivations on the page and the experiments named.

## Author
Nik Bear Brown.

## Audience

This book is written for the engineering, physics, chemistry, and pre-med student taking the calculus-based introductory physics sequence — typically the first of two semesters, often paired concurrently with calculus I or II. They have completed high school physics; they are taking the math seriously now. They will be tested on derivations, not just plug-and-chug.

Specifically:

- Engineering freshmen and sophomores in PHYS 151 / 161 / equivalent.
- Physics and astronomy majors taking the introductory sequence before moving on to mechanics, E&M, and modern physics.
- Chemistry, materials, and biophysics majors needing the calculus-based foundation.
- Pre-med students at institutions that require calculus-based physics rather than algebra-based.
- Adult learners and self-studiers working through the standard university curriculum.

This is the calculus-based version. Vectors are vectors. Derivatives are derivatives. The chapter on motion in 1D introduces $v(t) = dx/dt$ on the page. The chapter on rotation derives the moment of inertia from the integral, not from a memorized formula. Where the algebra-based version invokes a result, this one shows where the result comes from.

## Scope

Volume 1 of the standard sequence — mechanics through sound. The seventeen content chapters cover, in order:

1. **Units and measurement** — the SI system, dimensional analysis, significant figures, estimation.
2. **Vectors** — components, dot product, cross product, vector algebra in 3D.
3. **Motion along a straight line** — position, velocity, acceleration; derivative and integral relations; constant-acceleration kinematics; free fall.
4. **Motion in two and three dimensions** — vector kinematics; projectile motion; uniform circular motion; relative motion.
5. **Newton's laws of motion** — the three laws, free-body diagrams, common forces.
6. **Applications of Newton's laws** — friction, drag, centripetal force; problem-solving strategies.
7. **Work and kinetic energy** — work as line integral, the work-energy theorem, power.
8. **Potential energy and conservation of energy** — conservative forces, potential-energy curves, mechanical-energy conservation, energy-conservation problem-solving.
9. **Linear momentum and collisions** — momentum, impulse, conservation; elastic and inelastic collisions; center of mass; the rocket equation.
10. **Fixed-axis rotation** — angular kinematics, moment of inertia, rotational kinetic energy, torque, Newton's second law for rotation.
11. **Angular momentum** — angular momentum of a particle and a rigid body, conservation; precession.
12. **Static equilibrium and elasticity** — first and second conditions of equilibrium; stress, strain, and Young's modulus.
13. **Gravitation** — Newton's law of universal gravitation, gravitational potential energy, Kepler's laws, satellite motion.
14. **Fluid mechanics** — pressure, buoyancy, fluid dynamics, Bernoulli's equation, viscosity.
15. **Oscillations** — simple harmonic motion, energy in SHM, the pendulum, damping, resonance.
16. **Waves** — wave equation, traveling waves, energy and power, superposition and interference, standing waves.
17. **Sound** — sound waves, intensity and intensity level, the Doppler effect, shock waves, sources of musical sound.

(The original numbering goes 1-19 with two empty section-divider folders for "Mechanics" and "Waves and acoustics." Those are organizational headers in the source, not chapters with content. The numbering above lists only the 17 content chapters; final chapter files preserve the original numbering for reference.)

Out of scope: thermodynamics, electricity and magnetism, optics, modern physics — those belong to Volumes 2 and 3 of the sequence.

## Voice notes for this book

The Attenborough × Feynman v1.1 voice applies, with adjustments for calculus-based physics.

**Cold opens earn their place.** A chapter on units opens with the 1999 Mars Climate Orbiter crash — $325 million lost because Lockheed used pound-seconds and JPL used newton-seconds. A chapter on gravitation opens with Henry Cavendish in 1798 weighing the Earth in his garden shed. A chapter on oscillations opens with the Tacoma Narrows bridge tearing itself apart in November 1940. Real physics, real consequences.

**Math is on the page.** This is calculus-based physics. The chapter shows the derivation, not just the result. When introducing $v(t) = dx/dt$, the chapter traces the limit of $\Delta x / \Delta t$ as $\Delta t \to 0$. When introducing the moment of inertia, the chapter sets up the integral $I = \int r^2 \, dm$ and works through at least one full case (a uniform rod, a hoop, a disk).

**Notation taught.** Greek letters get glossed on first use. $\omega$ is "omega, the angular frequency, with units of radians per second"; $\tau$ is "tau, the torque, the rotational analogue of force." Vector notation gets unpacked: $\vec{F} = m\vec{a}$ is the same equation as three scalar equations $F_x = ma_x$, $F_y = ma_y$, $F_z = ma_z$, and the chapter shows the link.

**Grounded examples.** Real engineering scenarios: a car of stated mass accelerating through a stated distance, a satellite at a stated altitude, a beam of stated length and stated load. SI units throughout. Where the source uses an imperial number, the rewrite either translates to SI on the spot or notes the conversion.

**The cost of getting it wrong.** Physics has consequences. The Mars Climate Orbiter named in Chapter 2 stays as a reference. Tacoma Narrows in Chapter 15. The Apollo 13 free-return trajectory in Chapter 13. The chapter teaches the math by showing how the math is used.

**Calculus is required.** This book does not avoid the calculus. When the source presents a result that requires derivatives or integrals, the rewrite shows the derivation. The companion *College Physics Bundle* in this workshop is the algebra-based version for the audience that needs that.

## Prerequisites assumed

- Calculus I (single-variable derivatives and definite integrals); Calculus II concurrent or recent.
- High school algebra and trigonometry — sine, cosine, the unit circle, basic identities.
- Comfort with vectors at the level of components and basic operations (the chapter on vectors re-introduces these formally).
- Willingness to derive results, not just remember them.

## Author byline convention

Author is Nik Bear Brown. First-person voice when taking a position. "I find that students who memorize the kinematic equations without deriving them once never quite trust them — derive each one once from $v(t) = dx/dt$ and you'll have the structure for life..."

## Style file location

Voice ground truth: workshop-root `style/`, with per-book overrides in `books/university-physics-bundle/style/` (currently empty). Where the per-book style is empty, agents anchor on `books/contemporary-mathematics/chapters/01-sets.md` (canonical voice anchor). The math voice carries; the additions are calculus-on-the-page, vector notation made explicit, and named experiments with named consequences.
