# Research: Chapter 10 — Linear Systems and Matrices
## Mathematics for Physics

**Chapter one-line:** Math: simultaneous equations, substitution/elimination, matrices and determinants, 2×2/3×3 solving. Physics source: ch.10/13 (static equilibrium ΣF=0, Στ=0; multi-body collisions).
**Research date:** 2026-05-30

---

## 1. Primary Sources

### Foundational papers and texts

- **Anonymous (Chinese), *Jiuzhang Suanshu* (The Nine Chapters on the Mathematical Art), c. 150 BCE–100 BCE; commentary by Liu Hui, 3rd c. CE.** Chapter 8, *Fangcheng* ("rectangular arrays"), poses systems of simultaneous linear equations and solves them by an array-based elimination essentially identical to modern Gaussian elimination — counting rods arranged in a grid, columns reduced by subtraction. This is the earliest documented matrix-style elimination and the right historical anchor for the chapter: the *method* predates the *notation* by two millennia. Use it to show students that "elimination" is older than algebraic symbolism. (Source: Wikipedia "Fangcheng (mathematics)"; ResearchGate "Jiu Zhang Suan Shu and the Gauss algorithm for linear equations.")

- **Gabriel Cramer, *Introduction à l'analyse des lignes courbes algébriques* (1750).** States, without proof, the determinant rule now called Cramer's rule, for the general n×n system. Cramer arrived at it from a geometry problem — finding the equation of a plane curve forced through a set of given points, itself a linear system in the unknown coefficients. Note for the chapter: Colin Maclaurin published special cases in his *Treatise of Algebra* (1748, possibly known to him by 1729), so Cramer's rule has a contested priority. (Sources: Kosinski, "Cramer's Rule Is Due to Cramer," Rutgers PDF; MacTutor "Matrices and determinants.")

- **Seki Takakazu (1683, Japan) and Gottfried Wilhelm Leibniz (1693).** Independently and in parallel introduced determinants: Seki, without a word for "determinant," gave general methods and computed 2×2 through 5×5 cases; Leibniz studied the determinant as the condition for a linear system to have a solution. Good for the "two cultures, one idea" sidebar and to separate *determinant* (a number testing solvability) from *matrix* (the array itself) — a distinction students conflate. (Source: HandWiki "Determinant"; MacTutor.)

- **James Joseph Sylvester (1850).** Coined the word "matrix" (Latin for "womb") — "an oblong arrangement of terms" out of which determinants (minors) are born. The word predates the algebra. (Sources: MacTutor "Matrices and determinants.")

- **Arthur Cayley, "A Memoir on the Theory of Matrices," *Philosophical Transactions of the Royal Society* 148 (1858), pp. 17–46.** The first paper on matrix algebra as such: defines matrix addition and multiplication, the inverse (Cayley had given the inverse in an 1853 note), and treats matrices as objects with their own algebra — a "linear associative algebra." Contains the Cayley–Hamilton theorem, which Cayley proved only for 2×2 and 3×3 (asserting the general case). Freely available on Internet Archive (philtrans05474612). This is the source to quote for "a matrix is a thing you can do arithmetic with," and the 2×2/3×3 restriction matches the book's scope exactly. (Sources: Internet Archive; Higham, "Cayley, Sylvester, and Early Matrix Theory," 2008.)

### Key empirical cases

- **The two-string pan (static equilibrium → 2×2 linear system).** From source ch.13: a pan hangs from two strings at different angles; the horizontal and vertical force-balance equations, ΣFx = 0 and ΣFy = 0, are two linear equations in the two unknown tensions T₁, T₂. Solving them is *literally* solving a 2×2 system; the chapter can show the same problem solved by substitution, by elimination, and by Cramer's rule, getting the identical answer three ways. Documented worked example in `chapters/13-static-equilibrium-and-elasticity.md`.

- **The leaning ladder (ΣF=0 and Στ=0 → 3×3 linear system).** A ladder against a frictionless wall has three unknowns (wall normal, floor normal, floor friction) and three equations (two force components plus one torque). A genuine 3×3 system from mechanics; ideal for introducing the 3×3 determinant and showing why three equations are needed for three unknowns. (Standard problem in source ch.13.)

- **Two-body 1D collision (conservation laws → linear system).** From source ch.10: conservation of momentum is linear in the unknown final velocities; for a perfectly inelastic collision the system is linear and solvable by elimination. For elastic collisions, momentum is linear but kinetic-energy conservation is quadratic — a clean illustration of where the *linear* toolkit stops and why that boundary matters. Documented in `chapters/10-linear-momentum-and-collisions.md`.

---

## 2. The Core Concept — State of the Field

### What is settled
- Elimination (the row operations of Gaussian elimination) and substitution are equivalent, complete methods for solving a square linear system with a unique solution; both date in essence to the *Nine Chapters*. (ScienceDirect, Grcar, "How ordinary elimination became Gaussian elimination.")
- A square system Ax = b has a unique solution iff det(A) ≠ 0; Cramer's rule expresses each unknown as a ratio of determinants. This is mathematically exact and is the right *conceptual* tool even though it is computationally inefficient for large systems. (MacTutor; Cramer 1750.)
- The 2×2 determinant ad − bc is the signed area of the parallelogram spanned by the rows/columns; the 3×3 determinant is the signed volume. This geometric reading is settled and is the bridge to "determinant = 0 means the equations are not independent / the vectors are coplanar."

### What is disputed
- **Naming/priority (historical):** "Gaussian elimination" is a misnomer — Euler, Legendre, and Gauss himself called the method "common" or "ordinary"; Gauss's name attached only because professional human computers adopted his least-squares *notation*. Cramer's rule has a Maclaurin-priority dispute. These are pedagogy-relevant: name the method honestly. (Grcar 2011; Kosinski 2001.)
- **Notation (pedagogy):** whether to introduce augmented-matrix notation [A | b] before or after students are fluent in substitution/elimination on bare equations is debated in the math-ed literature; introducing the array too early can make elimination feel like an opaque ritual.

### What has changed recently (last 5 years)
- Pure-math content here is stable; no recent change to the theorems. Recent math-ed work (2019–2025) continues to document that students treat the three solution methods as unrelated procedures rather than as the same act of eliminating unknowns, and recommends grounding the formal procedures in informal reasoning first (Colorado CDE Systems-of-Equations guide; IJMRA 2025 study). Minimal aging risk for the mathematics.

---

## 3. Application Domain Examples

1. **Tension in two support cables** (ΣFx=0, ΣFy=0): the canonical 2×2 system; solve by elimination and verify with the 2×2 determinant. (Source ch.13.)
2. **Leaning ladder / hinged beam with a cable**: 3×3 system from two force equations and one torque equation; introduces 3×3 determinant and cofactor expansion. (Source ch.13.)
3. **Perfectly inelastic two-body collision**: momentum conservation gives a linear equation; with a constraint (objects stick) the system is linear and solvable. (Source ch.10.)
4. **Truss joint (method of joints)**: at a pin joint in equilibrium, ΣFx=0 and ΣFy=0 give two linear equations per joint in the unknown member forces — a network of coupled linear systems. (Statics application of ch.13 material.)
5. **Currents in a resistor network (Kirchhoff's laws), as a "where it generalizes" pointer**: node and loop equations form a linear system solved identically; shows the same matrix machinery outside mechanics.

---

## 4. The Book's Thesis Connection

The thesis is that intro physics is a sequence of mathematical tools, and a linear system is the first place where physics *forces* the student into genuinely simultaneous reasoning. Equilibrium is not one equation but a *coupled set*: ΣFx, ΣFy, Στ must hold at once, and no amount of algebra on a single equation reaches the answer. The chapter's contribution to the argument is to show that "set up the equilibrium equations and solve" *is* the act of solving a linear system — and that matrices/determinants are not extra machinery but the general bookkeeping for it.

What the student must supply that a solver cannot: **the modeling step**. A calculator or `numpy.linalg.solve` inverts the matrix instantly, but only after a human has drawn the free-body diagram, chosen the axes, decided which forces are unknown, and written the *correct* coefficient matrix. The determinant being zero is a mathematical fact; recognizing that a zero determinant means "you picked a redundant torque axis" or "the structure is a mechanism, not a rigid body" is physical judgment. The research literature on student difficulties (method-selection errors, treating substitution/elimination/matrix as unrelated) supports the book's claim: the failure is rarely arithmetic — it is not seeing the underlying single act, exactly the transferable understanding the book wants to install.

---

## 5. The AI Wayback Machine — Candidate Figures

- **Seki Takakazu (関 孝和)** (c. 1642–1708, Japanese mathematician). Independently invented determinants in 1683, before Leibniz, computing them up to 5×5 to test solvability of linear systems. Worked *on the math itself*. Non-Western, lesser-known to Western students, Wikipedia-accessible. Anchor prompt: "Seki Takakazu (circa 1690, Japanese mathematician) — man in late-Edo-period scholar's robes, counting rods arranged in a rectangular array and determinant calculations nearby, historically plausible editorial portrait, face-centered composition, period-appropriate clothing and workspace, no text, no watermark." **Skew flag:** strong choice — diversifies on nationality and era; no portrait-fidelity concern since few likenesses exist (lean on period plausibility).

- **James Joseph Sylvester** (1814–1897, British mathematician). Coined "matrix"; close collaborator of Cayley. Famous-ish but the matrix-naming story is fresh; faced antisemitic exclusion from English academic posts, a genuine biographical hook. Anchor prompt: "James Joseph Sylvester (circa 1855, British mathematician) — bearded Victorian man in formal coat, arrays of terms and minor determinants nearby, historically plausible editorial portrait, face-centered composition, no text, no watermark." **Skew flag:** another European man; use only if Seki is taken elsewhere.

- **Olga Taussky-Todd** (1906–1995, Austrian-American mathematician). "Torchbearer for matrix theory" who turned matrices into a central object of 20th-c. mathematics and applied them to aircraft flutter (an oscillation/eigenvalue problem connecting to ch.11–12). Woman, refugee from Nazi Europe, applied + pure. Anchor prompt: "Olga Taussky-Todd (circa 1945, Austrian-American mathematician) — woman in 1940s dress at a desk, matrix eigenvalue computations and aircraft vibration notes nearby, historically plausible editorial portrait, face-centered composition, no text, no watermark." **Skew flag:** best diversity pick (gender + era + applied link); recommended primary candidate alongside Seki.

Set balance note: candidates currently skew European; Seki and Taussky-Todd correct gender/nationality, so prefer those two.

---

## 6. Pedagogical Delivery Research

- **Prerequisites:** fluency rearranging and isolating a single variable (book ch.02); vectors and components (ch.04), since equilibrium equations come from resolving forces into x/y; comfort that two equations can constrain two unknowns simultaneously.
- **Most common misconceptions (math-ed literature):** (a) treating substitution, elimination, and matrix methods as three unrelated rituals rather than one act of eliminating unknowns; (b) procedural slips — sign errors moving terms, combining unlike terms, mis-multiplying an equation before adding; (c) not understanding solution *types* — unique vs. none (parallel lines, det = 0) vs. infinitely many (same line); (d) vocabulary/symbol confusion. (Sources: ResearchGate "Students' difficulties in solving linear equation problems"; IJMRA 2025; David Publisher "Ninth-Grade Students' Difficulties in Solving Systems.")
- **Sequences that work:** ground the formal procedures in informal reasoning first — let students reason out a two-unknown balance physically before naming "elimination"; connect the geometric picture (two lines crossing) to the algebra; introduce the determinant as "the number that tells you whether the lines cross" *before* the area interpretation. (Colorado CDE guide.)
- **Failure modes in teaching:** introducing augmented-matrix notation and row-reduction as a black-box algorithm before the student sees it as the same elimination they already do by hand; presenting Cramer's rule as the "real" method (it is a conceptual tool, not the efficient one).
- **Understand vs. memorize:** the dividing line is whether a student, shown an equilibrium problem, *sees the linear system* and chooses a method fluidly, versus pattern-matching to a memorized template. The physics framing (det = 0 ⇒ the structure can move) is exactly what converts memorizers into understanders.

---

## 7. Representation and Display Research

Chapter anatomy benefits from two displays.
- **Multi-method comparison display** (the chapter's natural figure): the same 2×2 equilibrium system solved in three parallel columns — (1) substitution, (2) elimination, (3) Cramer's rule / determinants — each reaching the identical T₁, T₂, visually proving they are one method. Variables: the two tension unknowns and their coefficient matrix.
- **Geometric infographic:** two lines in the (T₁, T₂) plane intersecting at the solution, with a second panel showing parallel lines (det = 0, no solution) and a third showing coincident lines (infinitely many) — ties the determinant to the geometry. Otherwise: no exotic display required.

---

## 8. Open Questions and Research Gaps

- Cramer-vs-Maclaurin and "Gaussian" naming are settled-but-nuanced historical points; the chapter should state them carefully rather than repeat the textbook myth that Gauss invented elimination. (Well sourced via Grcar and Kosinski.)
- Did not retrieve a full translated *Fangcheng* worked example with the rod-array layout; the author may want one concrete Nine-Chapters problem with its array reduction shown. (GAP — recommend pulling from the ResearchGate Jiu Zhang paper or a translation.)
- No source likely to age within 3 years; pure-math content is stable.

## 9. Sourcing Notes
- Cayley's 1858 memoir is public-domain on Internet Archive (philtrans05474612) — quotable directly.
- Higham (2008) and Kosinski (2001) PDFs are open-access (Manchester eprints; Rutgers) and reliable for priority/naming claims.
- Several search hits are secondary (GeeksforGeeks, Studocu, LibreTexts) — use only to corroborate, not cite. Prefer MacTutor, the Cayley archive scan, and the peer-reviewed history papers (Grcar, ScienceDirect) for any historical claim in the chapter.
