# Images for Chapter 5: Motion in Two and Three Dimensions

## Image Assets Required

All images referenced in the chapter text use the placeholder format `[FIGURE: description]` as per CLAUDE.md hard rules. This file lists the figures that should be created or sourced.

### Figure 1: Curiosity Rover Landing Sequence
- **Context:** Chapter opening, showing the descent stages
- **Content:** Time sequence of Curiosity's descent: entry at 5.4 km/s, parachute deployment, retrorocket firing, final descent on cables
- **Data source:** NASA JPL Curiosity mission profile; publicly available images and animations
- **Caption:** The Curiosity rover lands on Mars in 2012, decelerating from hypersonic speed to zero through multiple stages. For seven minutes, it must manage motion in three dimensions simultaneously — deceleration both vertically and horizontally — with no communication feedback. The engineers have computed every second of this motion using vector kinematics.

### Figure 2: 3D Coordinate System with Position Vector
- **Context:** Concept 1, section on vector kinematics
- **Content:** Right-handed coordinate system (x east, y north, z up) with origin at Earth's center, satellite in orbit, position vector $\vec{r}(t)$ drawn from origin to satellite
- **Mathematical:** Point at (4787 km east, -4787 km south) at radius 6771 km from center
- **Caption:** A position vector $\vec{r}(t)$ specifies the particle's location in three-dimensional space. Each component ($x$, $y$, $z$) is a separate function of time and moves independently.

### Figure 3: Displacement of Satellite
- **Context:** Concept 1, worked example
- **Content:** Two positions of a satellite in polar orbit: Position 1 at North Pole, Position 2 at -45° latitude. Displacement vector drawn from start to end. Curved orbital path shown in gray.
- **Mathematical:** Start: (0, 6771, 0); End: (4787, -4787, 0); Displacement: (4787, -11558, 0)
- **Caption:** The displacement vector (blue arrow) is the straight-line path from the initial to final position. The satellite's actual orbital path (gray curve) is much longer. Displacement depends only on endpoints; the path does not matter.

### Figure 4: Horizontal vs. Vertical Motion Independence
- **Context:** Concept 1, section on independence
- **Content:** Two baseballs falling from the same height. One is released (zero horizontal velocity). One is thrown horizontally. Stroboscopic snapshot showing positions at equal time intervals. Both balls are at the same height at each time step, despite different horizontal motion.
- **Caption:** A ball dropped straight down (left) and a ball thrown horizontally (right) are at the same height at every instant. The horizontal and vertical motions are independent. Horizontal motion does not affect how fast the ball falls.

### Figure 5: Velocity Vector Tangent to Trajectory
- **Context:** Concept 1, illustrating velocity definition
- **Content:** Curved trajectory of a particle. Velocity vector drawn tangent to the curve at a point. Position vector from origin to particle also shown, perpendicular to velocity.
- **Mathematical:** Smooth curve (e.g., spiral), point on curve, $\vec{r}(t)$ from origin to point, $\vec{v}(t)$ tangent to curve
- **Caption:** The velocity vector is always tangent to the trajectory. As the particle moves, $\vec{v}$ changes direction. This change in direction is acceleration.

### Figure 6: Parabolic Trajectory of a Thrown Object
- **Context:** Concept 2, opening
- **Content:** Parabola traced by a baseball thrown horizontally from a 233-meter cliff at 18.1 m/s. Ground at y=0, launch point at (0, 233), impact point at (125, 0). Parabola curve shown. Vectors showing initial velocity (horizontal), gravity (vertical, downward), at a few points along the trajectory.
- **Caption:** A projectile launched horizontally follows a parabola. The horizontal velocity remains constant (no horizontal forces), while gravity accelerates the object downward. The combination produces the curved path.

### Figure 7: Trajectory Equation Components
- **Context:** Concept 2, deriving trajectory
- **Content:** Graph of $y = ax + bx^2$ (a parabola opening downward), with coefficients labeled in terms of $\theta_0$, $v_0$, $g$. Several points along the curve marked with coordinates.
- **Mathematical:** $y = (\tan\theta_0)x - \frac{g}{2(v_0\cos\theta_0)^2}x^2$
- **Caption:** The trajectory equation is a parabola. The slope ($\tan\theta_0$) and curvature (proportional to $-g$) depend on the launch angle and initial speed.

### Figure 8: Projectile Range vs. Launch Angle
- **Context:** Concept 2, discussing range
- **Content:** Graph of range $R$ on the y-axis vs. launch angle $\theta_0$ on the x-axis (0° to 90°). Curve shows maximum at 45°. Two symmetric angles (e.g., 30° and 60°) marked, both reaching the same range.
- **Caption:** The range is maximum at 45°. Launch angles that are complementary (summing to 90°) produce the same range but different trajectories (one low and flat, one high and arching).

### Figure 9: Maximum Height of a Projectile
- **Context:** Concept 2, deriving maximum height
- **Content:** Trajectory of a projectile launched at 75° with initial speed 70 m/s. Maximum height marked at apex (v_y = 0). Height label shows 233 meters. Time to apex shown on time axis.
- **Mathematical:** $h = 233$ m, $t = 6.9$ s, $v_0 = 70$ m/s, $\theta_0 = 75°$
- **Caption:** The maximum height depends only on the vertical component of initial velocity. A 45° launch and a 75° launch at the same speed reach different heights, but if both have the same $v_{0y}$, they reach the same height.

### Figure 10: Circular Motion Geometry
- **Context:** Concept 3, deriving centripetal acceleration
- **Content:** Circle of radius $r$. Particle at two nearby positions separated by angle $\Delta\theta$. Position vectors $\vec{r}(t)$ and $\vec{r}(t+\Delta t)$. Displacement vector $\Delta\vec{r}$. Velocity vectors $\vec{v}(t)$ and $\vec{v}(t+\Delta t)$ perpendicular to positions. Change in velocity $\Delta\vec{v}$. Similar triangles highlighted.
- **Caption:** As the particle moves on the circle, the displacement $\Delta\vec{r}$ is small and perpendicular to the velocity. The velocity vectors form a similar triangle with the same angle $\Delta\theta$. This similarity gives $\Delta v / v = \Delta r / r$, leading to $a_c = v^2 / r$ in the limit.

### Figure 11: Centripetal Acceleration Direction
- **Context:** Concept 3, showing direction toward center
- **Content:** Particle moving counterclockwise on a circle. Velocity vector $\vec{v}$ at several positions, always tangent. Acceleration vector $\vec{a}_c$ at each position, always pointing toward center. Radial lines from center to particle.
- **Caption:** Centripetal acceleration always points toward the center of the circle, perpendicular to the velocity. The particle does not spiral inward; the constant inward acceleration continuously curves the path to follow the circle.

### Figure 12: Uniform vs. Nonuniform Circular Motion
- **Context:** Concept 3, discussing acceleration components
- **Content:** Left: circle with velocity vector (constant magnitude, tangent) at one point. Acceleration vector pointing toward center only. Right: circle with velocity changing in magnitude (velocity vectors of different lengths), and acceleration with both radial (toward center) and tangential (along velocity) components.
- **Caption:** Uniform circular motion (left) has only centripetal acceleration toward the center. Nonuniform circular motion (right) has both centripetal acceleration (changing direction) and tangential acceleration (changing speed).

### Figure 13: Jet Barrel Roll Radius
- **Context:** Concept 3, worked example
- **Content:** Diagram showing a jet path (loop) with radius 229 meters labeled. Jet at several points around the circle. Centripetal acceleration vector at one point, labeled $a_c = 8g$.
- **Caption:** A jet pulling 8 *g* of centripetal acceleration while flying at 134 m/s must follow a circle of radius 229 meters. At higher speeds, the radius must increase to avoid exceeding the structural and physiological limits.

### Figure 14: Relative Motion in One Dimension
- **Context:** Concept 4, train and person
- **Content:** Side view of a train moving east at 10 m/s. Person inside walking forward at 2 m/s relative to train. Ground frame below showing the person moving 12 m/s east. Velocity vectors labeled.
- **Caption:** The person's velocity relative to the ground is the vector sum of their velocity relative to the train and the train's velocity relative to the ground: $\vec{v}_{PG} = \vec{v}_{PT} + \vec{v}_{TG} = 2 + 10 = 12$ m/s.

### Figure 15: Boat Crossing River
- **Context:** Concept 4, worked example
- **Content:** Top view of a river flowing east at 3 m/s. Boat with velocity vector relative to water (4.5 m/s) aimed northwest at angle 41.8° west of north. Resultant velocity relative to ground (3.35 m/s north) shown. Current velocity vector (3 m/s east) shown.
- **Mathematical:** $\vec{v}_{BW} = (-4.5\sin(41.8°)\hat{i} + 4.5\cos(41.8°)\hat{j})$ = $(-3.0\hat{i} + 3.35\hat{j})$ m/s, $\vec{v}_{WG} = 3.0\hat{i}$ m/s, $\vec{v}_{BG} = 3.35\hat{j}$ m/s
- **Caption:** To cross due north, the boat must point northwest to compensate for the eastward current. The resultant velocity relative to the ground is purely northward.

### Figure 16: Car Approaching Intersection
- **Context:** Concept 4, challenge problem setup
- **Content:** Top view of intersection. Car A approaching from the west (east direction of motion), Car B approaching from the south (north direction of motion). Velocity vectors for each. Position relative to intersection marked. Relative velocity vector from Car A's frame.
- **Caption:** In Car A's reference frame, Car B appears to approach at an angle determined by vector subtraction. The rate of change of distance between cars depends on the relative velocity.

### Figure 17: Summary Diagram: Four Layers of Motion
- **Context:** Integration section
- **Content:** Schematic showing four nested circles or layers. Layer 1: "Vector kinematics" with equations for $\vec{r}$, $\vec{v}$, $\vec{a}$. Layer 2: "Projectile motion" with parabola. Layer 3: "Circular motion" with centripetal acceleration. Layer 4: "Relative motion" with frame transformation. Arrows showing how each layer adds constraints or structure to the previous.
- **Caption:** Motion in multiple dimensions unfolds in layers. Each adds constraints (gravity only, circular path, reference frame change) and tools (parabolic trajectory, centripetal formula, velocity addition). Together, they solve real-world problems like satellite orbits and spacecraft landings.

## Notes on Sources

- **Curiosity rover:** NASA JPL mission data, publicly available. Landing sequence is well-documented.
- **Projectile motion figures:** Standard textbook diagrams; the physics is universal.
- **Circular motion:** Geometry is exact; derived from calculus and vector algebra.
- **Relative motion:** Diagrams illustrate Galilean transformation; standard in all mechanics texts.

All diagrams should be drawn with clear labeling, consistent vector notation (arrows for vectors, magnitudes in units), and dimensions accurate to scale where relevant (e.g., satellite orbit radius to Earth radius comparison).
