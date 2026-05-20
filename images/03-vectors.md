# Images — Chapter 3 (Vectors)

## Figure placement and specifications

### Figure 1: Vector components in 2D (after "Converting from magnitude and direction to components")

**Title:** Breaking a vector into $x$ and $y$ components.

**Description:** Coordinate system with origin at bottom-left. Show a single vector $\vec{D}$ pointing northeast (upper-right), drawn from the origin. The angle $\theta$ from the horizontal +$x$ axis is labeled clearly. Drop perpendicular lines from the tip of $\vec{D}$ to both axes. Label the horizontal projection as $D_x$ (with a right-pointing arrow along the $x$-axis) and the vertical projection as $D_y$ (with an upward-pointing arrow along the $y$-axis). Show a right triangle formed by $\vec{D}$ as the hypotenuse, $D_x$ as the adjacent side, and $D_y$ as the opposite side. Include the formula $D = \sqrt{D_x^2 + D_y^2}$ in the figure or caption.

**Learning goal:** Students should see that any vector can be broken into perpendicular parts and that the Pythagorean theorem relates the whole to its parts.

---

### Figure 2: Unit vectors $\hat{i}, \hat{j}, \hat{k}$ in 3D (in section "3D: adding the $z$ component")

**Title:** Unit vectors in three-dimensional Cartesian coordinates.

**Description:** A 3D coordinate system with three unit vectors emanating from the origin. Show $\hat{i}$ pointing to the right (east, +$x$), $\hat{j}$ pointing forward/up (north, +$y$), and $\hat{k}$ pointing upward (up, +$z$). Each should be the same length visually (length 1 in an isometric or perspective drawing). Label each clearly. Show a sample vector $\vec{D} = D_x\hat{i} + D_y\hat{j} + D_z\hat{k}$ as a combination of these unit vectors, with the vector itself drawn as a diagonal in the coordinate system. Include small labels showing the three component vectors forming a rectangular box with $\vec{D}$ as the space diagonal.

**Learning goal:** Students should visualize that any 3D vector is a weighted sum of the three perpendicular unit vectors.

---

### Figure 3: The dot product and scalar projection (in section "Geometric interpretation: scalar projection")

**Title:** Scalar projection and the dot product.

**Description:** Show two vectors $\vec{A}$ and $\vec{B}$ emanating from a common origin, with angle $\varphi$ between them. Along the direction of $\vec{B}$, draw a perpendicular line from the tip of $\vec{A}$ to the $\vec{B}$ direction, creating a right triangle. The projection of $\vec{A}$ along $\vec{B}$ is shown as a thick arrow along $\vec{B}$, labeled as $A \cos \varphi$ (or $A_\parallel$). Include the formula $\vec{A} \cdot \vec{B} = A_\parallel \times B = AB \cos \varphi$ in or near the figure. Use shading or color to show the right triangle clearly.

**Learning goal:** Students should see that the dot product relates to the shadow (projection) one vector casts on the other.

---

### Figure 4: The cross product and right-hand rule (in section "The definition and the right-hand rule")

**Title:** The right-hand rule for the cross product.

**Description:** Show a right hand in position: fingers pointing in the direction of $\vec{A}$, curling toward $\vec{B}$ (through the angle $\varphi$). The thumb points out of the palm in the direction of $\vec{A} \times \vec{B}$, which is perpendicular to the plane containing $\vec{A}$ and $\vec{B}$. In the background, lightly show the two input vectors in a horizontal plane and the resulting cross product pointing upward (or downward if the order is reversed). Include labels: "$\vec{A}$" along the fingers' initial direction, "$\vec{B}$" in the curl direction, "$\vec{A} \times \vec{B}$" along the thumb. Consider showing a second figure with the order reversed ($\vec{B} \times \vec{A}$) to illustrate anticommutativity.

**Learning goal:** Students should have a visual anchor for the right-hand rule and immediately see that reversing the order reverses the direction.

---

## Supplementary visualizations (optional, useful for student understanding)

### Figure S1: Vector addition — parallelogram and tail-to-head methods

Show two methods for adding vectors geometrically. Left side: parallelogram rule (place both vectors at the same origin, complete the parallelogram, resultant is the diagonal). Right side: tail-to-head rule (place the tail of the second vector at the head of the first, resultant goes from the tail of the first to the head of the second). Both should arrive at the same resultant $\vec{R} = \vec{A} + \vec{B}$.

---

### Figure S2: Boat-on-river problem (worked example)

A top-down view showing the riverbank (two parallel lines), a boat at a starting position on the bottom bank, and three vectors: (1) boat velocity through water ($\vec{v}_{\text{boat}}$, pointing straight across), (2) river current ($\vec{v}_{\text{river}}$, pointing downstream), and (3) resultant ground velocity ($\vec{v}_{\text{ground}}$, at an angle). Show the boat's actual path as a curved dashed line reaching a point downstream on the opposite bank.

---

### Figure S3: Torque on a wrench (worked example)

A wrench seen from above, with the nut in the center. The position vector $\vec{r}$ from the nut to the point where the force is applied is shown as an arrow. The force vector $\vec{F}$ is shown at that point, perpendicular to the wrench (maximum torque case). The resulting torque vector $\vec{\tau} = \vec{r} \times \vec{F}$ is shown coming out of the page (using the @ symbol for out-of-page, ⊗ for into-page). Include an arc showing the direction of rotation the wrench undergoes.

---

## Notes for the artist/designer

1. **Unit vectors:** Make $\hat{i}, \hat{j}, \hat{k}$ visually distinct (e.g., red, green, blue or different line styles). Students often mix them up.

2. **Angles:** Label all angles clearly. Use standard notation ($\varphi, \theta$). Make the angle arc visible.

3. **Right-hand rule:** This is the hardest figure to execute. Consider multiple angles to make the geometry clear. A 3D rendering or a photograph of an actual hand might help more than a schematic drawing.

4. **Equations in figures:** Keep equations brief. Full derivations go in the text. Figures should caption results.

5. **Color:** Use consistently (e.g., always red for $\vec{A}$, always blue for $\vec{B}$, always green for the result). This helps students track quantities across multiple figures.

6. **Gridlines:** Include a coordinate grid lightly in the background of any 2D or 3D figure to help students estimate magnitudes and angles.

---

## Replacement text for [FIGURE: ...] placeholders in chapter

All four main figures are referenced in the chapter text at specific points. Replace each [FIGURE: ...] placeholder with the actual figure caption and image. The placeholders are located at:

1. After "Convert from magnitude and direction to components"
2. In section "3D: adding the $z$ component"
3. In section "Geometric interpretation: scalar projection"
4. In section "The definition and the right-hand rule"

Each placeholder follows this format:
```
[FIGURE: 03-vectors-fig-{N}: {descriptive-title}]
```

Final chapter should have actual image files embedded (SVG or high-quality PNG), not placeholders.
