# Bookmap: University Physics — Motion in Two and Three Dimensions

## Source Material

**Original source:** 6 sections from OpenStax University Physics, Vol. 1. Chapter 4 (Motion in Two and Three Dimensions). Total approximately 17,000 words across 6 markdown files covering:

1. Vector kinematics — position, velocity, acceleration in 2D/3D
2. Projectile motion — trajectory, range, time of flight
3. Circular motion — centripetal acceleration, uniform and nonuniform cases
4. Relative motion — reference frames and velocity addition

**Conversion task:** Translate from OpenStax pedagogy (objective-driven, comprehensive, organized by topic) to Attenborough × Feynman voice (scene-first, mechanism-focused, trade-offs named, moral weight at end).

---

## Scene-Anchored Cold Opens: Ideas for Each Layer

### Layer 1: Vector Kinematics
**Cold open angle:** NOT "Vectors are useful in physics" but a specific moment of observation.
- **Best option:** A satellite in polar orbit passing overhead the North Pole, then reappearing at -45° latitude. The observer on the ground sees two positions; the satellite sees a continuous path. This duality — same motion, different perspectives depending on reference frame — is the engine of the chapter.
- **Alternative:** A ship's navigation room. Plotting position $\vec{r}(t)$ in three dimensions as the ship moves through the ocean. Each coordinate — east, north, depth — is recorded separately, yet they combine to place the ship uniquely in space.
- **Why it works:** Concrete, visual, immediately raises the question: "How do we track motion when it happens in multiple directions at once?" The answer is the entire chapter.

### Layer 2: Projectile Motion
**Cold open angle:** The moment a pitcher releases a baseball and the batter watches the trajectory.
- **Source tension:** The human eye can predict roughly where the ball will land by watching its path for the first 20 meters. But throw the same ball sideways and the eye can't predict at all. This suggests there's structure to projectile motion that the eye is unconsciously learning.
- **Alternative:** Fireworks. A shell launched into the night sky reaches its apex just as the fuse ignites. The engineers timed this using the same equations we're deriving. Show the math getting the fuse timing exactly right — that's the payoff.
- **Why it works:** Sport and spectacle are universally understood. Everyone has seen a ball in flight. The chapter is saying: there's a formula for that, and it's surprisingly simple.

### Layer 3: Circular Motion
**Cold open angle:** A point on a spinning record player or a second hand on a clock.
- **Source tension:** The speed is constant — the needle on the record doesn't speed up or slow down — but the velocity is constantly changing because the direction changes. This seems contradictory. How can something accelerate if its speed is constant?
- **Alternative:** A car entering a circular turn. The speedometer reads constant (e.g., 20 m/s), but passengers feel pushed sideways. They sense an acceleration even though the speed isn't changing. This is centripetal acceleration — a change in direction, not speed.
- **Why it works:** The contradiction (constant speed, changing velocity) is puzzling and invites resolution. The resolution is that velocity and speed are different.

### Layer 4: Relative Motion
**Cold open angle:** Two trains passing in opposite directions, or a plane compensating for wind.
- **Source tension:** The ground observer and the train observer measure different velocities for the same object. Neither is wrong. Both frameworks are consistent. This invites the question: how do we transform between them?
- **Alternative:** A boat trying to cross a river with a current. The boat captain points the bow in one direction, but the actual path over the ground is different. The boat's speed relative to the water is not the same as its speed relative to the shore.
- **Why it works:** Relative motion is immediately practical. Navigation, weather, relative velocity are constants in human experience.

---

## Specificity Harvests: What the Original Teaches That's Harvestable

### Concrete Examples (Names, Numbers, Real Scenarios)
- **Satellite in polar orbit at 400 km altitude:** Specific number; Earth radius 6,371 km; specific latitude (-45°). These ground the abstract in reality.
- **Fireworks shell at 70 m/s, 75° launch angle:** Real fireworks parameter (70 m/s is realistic for pyrotechnics). Result: maximum height 233 m, time to apex 6.9 s. These are memorable because they're substantial.
- **Baseball problems:** Pitcher 16.7 m from plate, throwing at 40 m/s. Specific field distances (Pebble Beach 496 m dogleg). These anchor the math to experience.
- **Jet centripetal acceleration:** 134 m/s (480 km/h typical combat speed), producing 1*g* acceleration at 1.835 km radius. Then 8*g* at 229 m radius. The tightness of the turn drives home the trade-off: faster turns require smaller radius and higher acceleration.

### Hidden Elegancies (That Become Visible)
- **The complementary angle property of range:** Launch at 30° and 60°, same range. This seems like magic until you see $\sin 2\theta = \sin(180° - 2\theta)$. The original source mentions this but doesn't emphasize why it's beautiful: the parabola is symmetric in a way that makes two different launch angles equivalent. This is convertible into a narrative moment: "Here's why."
- **Maximum range at 45°:** A direct consequence of the $\sin 2\theta$ formula. Natural maximum at $\theta = 45°$. But the original source doesn't ask why. The Attenborough version should: this is the angle where you optimize for distance, not height or time. That optimization is human strategy.
- **The three-equation kinematic set:** The original presents these as a menu: you choose which equation depending on what you know. This is pedagogically sound but unsatisfying. The deeper truth: they're all the same relationship between $v$, $a$, $x$, and $t$, just rearranged. This is harvestable as a structural insight.

### Trade-offs and Failures (Explicitly Named)
- **Air resistance:** The original mentions it and gives an example (Mars Climate Orbiter), but doesn't emphasize the trade-off cleanly. The Attenborough version should: we gain closed-form solutions, we lose accuracy. This is a real choice, not a simplification.
- **Uniform circular motion assumption:** Real motion is nonuniform. The original covers nonuniform motion but treats it as an add-on. The Attenborough version should frame it as an extension: the simplest case is uniform (constant speed); real motion requires both centripetal and tangential acceleration.
- **Reference frame choice:** The original shows Galilean relativity is frame-dependent, but doesn't ask why. The Attenborough version should: inertial frames (constant velocity relative to each other) preserve Newton's laws. Accelerating frames require fictitious forces. This is the seed of General Relativity.

### Derivations (That Deserve to Be Shown)
- **Centripetal acceleration from geometry:** The original derives this via similar triangles. This is perfect for the Attenborough approach: the geometry is visual and non-obvious. The limit as $\Delta t \to 0$ is the insight.
- **Trajectory equation from kinematic equations:** Eliminating time between two equations to get $y(x)$. This is the move where projectile motion becomes a shape (parabola). The original shows it; the Attenborough version should celebrate it: this is where calculus produces geometry.
- **Range formula from trajectory:** Setting $y = y_0$ and solving for $x$. Then using the double-angle identity. The original does this mechanically. The Attenborough version should show the move as an unfolding: we start with a vector equation, eliminate time, and discover a symmetric function of the launch angle.

### Scale Shifts (from Intimate to Cosmic)
- **Curiosity rover landing:** A real, recent event (2012). The engineers computed 3D motion under constant acceleration. This is the same calculation you would do for any projectile, just with different numbers (hypersonic speeds, Martian gravity). The scale: 325-million-dollar spacecraft, 7 minutes of autonomous flight, real stakes. This is harvestable as the opening cold scene.
- **Baseball to artillery to ICBMs:** The source mentions this trajectory progression implicitly. The original problem about a baseball can be rephrased as an artillery problem by changing speeds and angles. And the same math governs ICBM trajectories (though those must account for Earth's curvature and changing gravity). This is the cosmic scale shift: from personal (throwing a ball) to global (intercontinental ballistic missiles).
- **Satellite orbits:** A satellite in circular orbit at the right speed experiences zero net force in the radial direction (gravity provides the centripetal force). This connects circular motion to gravitation. The source doesn't make this connection in this chapter, but it's harvestable as foreshadowing.

### Specific Problems Worth Preserving
- **Satellite displacement problem:** Position at North Pole, then at -45° latitude. Displacement vector magnitude 12,509 km. This is concrete and carries real data.
- **Projectile landing at different height:** Tennis player hitting into the stands, catching at height 10 m above launch. Requires solving a quadratic equation and choosing the non-trivial root. This is the kind of real-world complication that makes the problem interesting.
- **Boat crossing river with current:** A canonical problem. The boat aims northwest to move due north. The calculation is straightforward but the geometry is non-obvious. This is perfect for the Attenborough version: watch what velocity addition does to the apparent direction.
- **Jet barrel roll radius:** Combat relevance, physiological stakes (pilot blacking out at 8*g*). The number (229 m radius) is impressively tight. This is harvestable as a moment of wonder.

---

## Structural Moves (That Translate to Attenborough-Feynman)

### The Hook → Explanation → Trade-off → Scale Shift → Weight Pattern

**Observation from OpenStax:**
1. Each section opens with a scenario (hook).
2. It introduces definitions and equations (explanation).
3. It gives worked examples (application).
4. It summarizes key results.

**Translation to Attenborough-Feynman:**
1. **Hook:** Expand the initial scenario into a full cold scene. Make it sensory, specific, visceral.
2. **Explanation:** Show the derivation, not just the result. Emphasize first principles.
3. **Trade-off:** Name what the model gains (simplicity, solvability) and what it sacrifices (air resistance, nonuniform motion, accelerating frames).
4. **Scale shift:** Connect the intimate (throwing a ball) to the cosmic (Mars landing) or vice versa.
5. **Weight:** End with moral clarity — why this matters, what the reader now understands that they didn't before.

### The Worked Example as Narrative Unit

The original includes many worked examples. Each is solvable and pedagogically sound. But they feel procedural (given these inputs, follow steps 1-5 to get the output).

The Attenborough version should keep the same examples but reframe them as unfoldings: *"Here is the question that matters. Here is why we can solve it now. Here is the calculation. Here is what the answer tells us."* The narrative arc is: puzzle → method → result → meaning.

---

## Gaps and Extensions (Opportunities for the Attenborough Version)

1. **Why is independence so robust?** The original uses it as a principle; the Attenborough version should ask: what force configurations allow perpendicular motions to separate? When does independence fail?

2. **Geometric intuition for the parabola:** Why is the trajectory a parabola? What is special about constant acceleration that produces this shape? The original derives it algebraically; the Attenborough version should include geometric insight.

3. **Centripetal vs. centrifugal:** The original distinguishes them briefly. The Attenborough version should emphasize that centrifugal is fictitious, appearing only in rotating frames. This is philosophically important: the distinction between inertial and non-inertial frames.

4. **Galilean relativity as a model:** The original presents velocity addition as a formula. The Attenborough version should ask: under what conditions does this simple rule work? (Answer: speeds much slower than light, constant relative velocity of frames.) What breaks down? (Answer: relativistic speeds, accelerating frames.)

5. **History and discovery:** Who first derived the trajectory equation? When? The original is timeless and ahistorical. The Attenborough version could include a moment of intellectual history — not as decoration, but as evidence that these ideas were hard-won and important.

---

## Forbidden Phrases Eliminated

From the OpenStax source:
- "It is worth noting that..." → just state the fact
- "Interestingly..." → show why it's interesting
- "Can be shown..." → show it on the page
- "It is remarkable that..." → let the fact speak
- "The data shows..." → state which data, which calculation

All of these are candidates for replacement with the specific mechanism or the numerical result.

---

## Final Integration: The Four-Layer Thesis

The original material, properly read, presents four conceptual layers:
1. **Vector kinematics** — the language and grammar of multidimensional motion
2. **Projectile motion** — the simplest case (gravity only) producing a universal shape (parabola)
3. **Circular motion** — a different constraint (fixed radius) producing different acceleration (always inward)
4. **Relative motion** — a different perspective (change reference frames) transforming velocities predictably

Each layer builds on the last. Together, they constitute a worldview: motion in multiple dimensions is solvable if you separate it properly, name the constraints, and transform between perspectives as needed.

The Attenborough-Feynman version inherits this structure but emphasizes it: four moves, four layers, four kinds of simplification. The reader finishes understanding not just how to solve problems, but why these particular mathematical structures appear in nature.
