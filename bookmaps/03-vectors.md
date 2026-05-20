# Bookmap — Chapter 3 (Vectors)
## Mining the standard physics textbook for vectors

### Context

Young & Freedman's *University Physics* is the canonical calculus-based introductory mechanics text. Chapter 1 (Units), Chapter 2 (Vectors), and Chapter 3 (Motion in One Dimension) set up the machinery for everything that follows. This bookmap extracts what that chapter does well and what gaps exist for the bear-textbooks voice.

---

## Young & Freedman Chapter 2: Vectors

### What this chapter actually teaches

The standard treatment moves through four moves:

1. **Scalar vs. vector quantities.** Temperature is a scalar (just a number). Displacement is a vector (number plus direction). The distinction is semantic at first, but carries weight immediately: you can add 10°C + 20°C, but you cannot sensibly add "10 m northeast" + "20 m north" as scalars.

2. **Vector representation: magnitude and angle.** A vector in a plane can be described either as (magnitude, direction angle) or as (component in x, component in y). The chapter shows both and the relationship between them via trigonometry.

3. **Vector addition via components.** The key insight: if you know the components of two vectors, you add them component-by-component. This is much simpler than the parallelogram rule once you have components.

4. **Unit vectors and notation.** The textbook introduces $\hat{i}, \hat{j}, \hat{k}$ to write vectors compactly: $\vec{A} = A_x\hat{i} + A_y\hat{j} + A_z\hat{k}$.

The chapter *does not* do dot products or cross products. It stops after establishing the algebra of components and addition. Those products appear in later chapters as needed.

### What it does well

**1. Geometric intuition before algebra.**

The textbook opens with vectors as arrows, draws them carefully, shows magnitude as length and direction as angle. Only after this visual foundation does it introduce components. Students see the triangle formed by a vector and its projections, and understand why the Pythagorean theorem relates them.

**Teaching move to steal:** Start with a picture. Let students see the geometry before you touch the algebra.

**2. The equivalence of two languages.**

The textbook is meticulous about showing that (magnitude, angle) and (x-component, y-component) describe the *same* vector. It provides conversion formulas and worked examples in both directions.

$$A_x = A \cos \theta, \quad A_y = A \sin \theta$$

$$A = \sqrt{A_x^2 + A_y^2}, \quad \theta = \tan^{-1}(A_y / A_x)$$

**Teaching move to steal:** Never give students a formula without showing how it connects to the picture. The formula is a shorthand for the geometry, not a replacement for it.

**3. Multiple strategies for the same problem.**

The textbook solves vector addition problems three ways: graphically (using the parallelogram rule), using components, and using geometry formulas. It shows that all three arrive at the same answer, building confidence that the abstract algebra is reliable.

**Teaching move to steal:** Show students they already know how to do the thing. You're just teaching them a faster way to write it down.

**4. Problem-solving structure.**

The worked examples follow a consistent template: (Given), (Find), (Approach), (Execute), (Evaluate). This structure appears in every problem. By the end of the chapter, students recognize it and know what to do when they see a new problem.

**Teaching move to steal:** A consistent problem-solving structure is a gift to students. Repetition builds automatic competence.

### What it doesn't do (and bear-textbooks can fill)

**1. Grounding in a real scenario.**

The standard chapter opens with "A scalar is a quantity that has magnitude only," the textbook answer. bear-textbooks could open with the airplane example (pilot calculating ground track), which has immediate consequence. You miss the island if you get this wrong.

**2. Why three-dimensionality matters.**

The textbook introduces $\hat{k}$ and extends to 3D briefly, but doesn't dwell on why 3D is different from 2D. In 2D, a single angle specifies direction. In 3D, you need two angles (latitude and longitude, or spherical coordinates). Cross products only exist in 3D (and 7D, but that's esoteric). The chapter could mark the boundary.

**3. The dot and cross products.**

The standard textbook doesn't introduce these in Chapter 2. They appear later, when needed (dot product in work, cross product in torque). bear-textbooks includes them here, because students need to see that vectors have *three* operations (addition, dot, cross), each answering a different question. Including them makes the chapter complete.

**4. Etymology and vocabulary as teaching.**

The standard chapter uses the words but doesn't explain why they're called what they are. *Vector* comes from *to carry*. *Scalar* comes from *scale*. *Component* comes from *to put together*. These aren't just names — they're mnemonic anchors. bear-textbooks leans into this.

**5. Honest acknowledgment of what puzzles us.**

The standard chapter states the cross product exists in 3D as fact. Why? It doesn't say. bear-textbooks can say: "I don't fully understand why rotation is special to three dimensions. Here's what we can observe and use, and here's what remains mysterious."

---

## Ideas harvest for bear-textbooks

### Structural moves to adopt

1. **Geometric then algebraic.** Always show the picture first. The arrow, the angle, the right triangle. Then introduce notation.

2. **Equivalence of representations.** A vector is *not* a pair of numbers. A pair of numbers is *a way to write down* a vector. The distinction matters.

3. **Conversion as a core skill.** Students must fluently move between (magnitude, angle) and (components). Test this repeatedly.

4. **Multiple solution paths.** Show that graphical, component-based, and geometric-formula approaches converge. This builds trust in abstraction.

5. **Consistent problem structure.** Given → Find → Approach → Execute → Evaluate. Repeat it until it's automatic.

### Conceptual moves to extend

1. **Operations on vectors.** Don't just add them. Show that you can *scale* them (multiply by a scalar), and that there are two different ways to *multiply* two vectors together (dot and cross). Three operations, three different results.

2. **Why dot products matter.** The dot product tells you overlap. Mathematically: $\vec{A} \cdot \vec{B} = AB \cos \varphi$. Physically: the component of $\vec{A}$ parallel to $\vec{B}$. Both perspectives are needed.

3. **Why cross products matter.** The cross product tells you rotation. It's perpendicular to both inputs. The magnitude is largest when they're perpendicular. This is fundamentally different from dot product geometry. Mark the difference sharply.

4. **Anticommutativity.** $\vec{A} \times \vec{B} \neq \vec{B} \times \vec{A}$. They differ by a sign. This is not a quirk — it encodes directional information. Rotation has a handedness.

### Worked examples to borrow and adapt

**From Young & Freedman:**

1. **Vector addition on a grid.** Two displacement vectors at given angles; find the resultant using both graphical and component methods. Simple, concrete, builds confidence.

2. **Finding a resultant force.** Three forces acting on an object; find the net force and its angle. Tests addition and magnitude calculation.

3. **Velocity in a moving reference frame.** Boat crossing a river, plane in a crosswind. This is *the* motivating example for vector addition. bear-textbooks should include a similar setup.

**Extensions for bear-textbooks:**

1. **Dot product in work.** Force at an angle, displacement, calculate work done. Students see immediately why the dot product matters.

2. **Cross product in torque.** Force perpendicular to a lever arm, calculate torque. Same reasoning: the cross product captures something physical.

3. **Magnetic force on a moving charge.** A charged particle moving through a magnetic field experiences a force $\vec{F} = q\vec{v} \times \vec{B}$. Three vectors, one cross product, one direction that's hard to visualize without the right-hand rule.

---

## Gaps and limitations in the standard approach

### Gap 1: "Why vectors?"

The standard chapter motivates vectors by saying "some quantities need direction." True, but not compelling. bear-textbooks says: *without vectors, you cannot solve problems in 2D or 3D. The moment you have two perpendicular components, you need vector algebra.* That's more powerful.

### Gap 2: The pedagogical sequence

Standard chapter: scalars vs. vectors → magnitude and angle → components → addition → unit vectors.

bear-textbooks sequence: problem (pilot) → recognize three directions matter → introduce component representation → add component-by-component → generalize to dot and cross products.

The second sequence is more motivated and has a sharper arc.

### Gap 3: Notation

Standard chapter: uses $\vec{A}$ and also $\vec{AB}$ (displacement from A to B), sometimes $\overrightarrow{AB}$ (arrow notation). This is okay but inconsistent.

bear-textbooks: Stick with $\vec{A}$ throughout. It's clear, it's standard, it's what students will see in every subsequent course.

### Gap 4: The cross product belongs here

The standard chapter leaves cross products to Chapter 11 (Rotational Motion). But students who finish Chapter 2 don't understand why there are *three* vector operations. The cross product should be introduced here, even if the deep applications come later. It completes the picture.

---

## Final synthesis

The standard textbook chapter on vectors is solid. It builds geometric intuition, introduces notation, establishes procedures, and provides practice. It does *not* motivate deeply, it doesn't explain etymology, it doesn't include cross products, and it doesn't acknowledge what remains puzzling.

bear-textbooks can do all of these without departing from the pedagogical core. The cold open (airplane ground track calculation) is more visceral than "a vector has magnitude and direction." The inclusion of dot and cross products makes the chapter complete. Etymology and history make the vocabulary stick. And honest uncertainty ("I don't yet fully understand why rotation is special to 3D") models the intellectual humility that physics demands.

---

## Word count by section

- Young & Freedman Chapter 2: ~40 pages in print, ~15,000 words
- bear-textbooks Chapter 3: ~7,200 words
- Compression ratio: 2:1

This is appropriate. bear-textbooks omits routine problems (students solve those for homework), repetitive examples, and some historical context. It keeps the essential concepts, the core mechanisms, the worked examples that teach method, and the exercises that scaffold learning.
