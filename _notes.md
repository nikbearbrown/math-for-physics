# Revision Notes

Track what you've added, removed, or rewritten here.

## 2026-05-07 — book.md created

Drafted `book.md` for the bundle. Audience: engineering, physics, chemistry, and pre-med students taking the calculus-based introductory sequence (Volume 1 — mechanics through sound). The signature pedagogical move: calculus is on the page. Every result that requires derivatives or integrals gets derived rather than asserted. Voice anchored on contemporary-mathematics chapter 1.

## 2026-05-07 — Attenborough × Feynman v1.1 conversion run: Chapters 2–19

17 content chapters dispatched in parallel to subagents. Two source folders (chapters/01-mechanics/ and chapters/16-waves-and-acoustics/) were empty section dividers — the Volume 1 source uses these as organizational headers between chapter groups. Skipped per the workflow's "subfolder contains no .md files: Skip it" rule, deleted in cleanup. The 17 content chapters all converted successfully. `_toc.md` rewritten preserving the source's chapter numbering (so chapters 1 and 16 are intentionally absent from the table of contents — Volume 2 will renumber if combined later).

| Ch | Slug | Words | Notes |
|---|---|---:|---|
| 02 | units-and-measurement | 6,780 | 8 source modules → 3 concepts (SI base units & 2019 redefinition; conversion & dimensional analysis; sig figs & estimation). Cold open: Mars Climate Orbiter 1999. |
| 03 | vectors | 3,574 | 5 source modules → 3 concepts (components & unit vectors; dot product; cross product). Cold open: pilot computing ground track from airspeed + wind. Lean — just above the 3,500 floor. |
| 04 | motion-along-a-straight-line | 5,231 | 7 source modules → 3 concepts (position/velocity/acceleration with calculus; constant-acceleration kinematics derived; free fall). Cold open: Felix Baumgartner October 2012. |
| 05 | motion-in-two-and-three-dimensions | 5,449 | 6 source modules → 3 concepts (vector kinematics; projectile motion; circular motion + relative motion). Cold open: Curiosity rover landing 2012. |
| 06 | newton-s-laws-of-motion | 5,849 | 8 source modules → 3 concepts (the three laws; free-body diagrams; common forces). Cold open: SpaceX Falcon 9 landing on a drone ship. |
| 07 | applications-of-newton-s-laws | 6,148 | 5 source modules → 3 concepts (friction; drag & terminal velocity; circular-motion applications). Cold open: NASCAR turn-three at Talladega. *Re-dispatched after first agent confused the book directory and refused; second agent succeeded.* |
| 08 | work-and-kinetic-energy | 4,936 | 5 source modules → 3 concepts (work as line integral; KE & work-energy theorem; power). Cold open: archer drawing a bow. |
| 09 | potential-energy-and-conservation-of-energy | 4,608 | 6 source modules → 3 concepts (conservative forces & PE; conservation of mechanical energy; PE diagrams). Cold open: roller coaster at the top of the first hill. |
| 10 | linear-momentum-and-collisions | 4,773 | 8 source modules → 3 concepts (momentum & impulse; conservation & collisions; CM & rocket propulsion). Cold open: Apollo 13 mid-course correction. Rocket equation derived. |
| 11 | fixed-axis-rotation | 6,646 | 9 source modules → 3 concepts (angular kinematics; moment of inertia & rotational KE; torque & Newton's second law for rotation). Cold open: medical centrifuge at 14,000 RPM. |
| 12 | angular-momentum | 5,116 | 5 source modules → 4 concepts (particle L; rigid-body L; conservation; precession). Cold open: Hubble Space Telescope reaction wheels. |
| 13 | static-equilibrium-and-elasticity | 4,452 | 5 source modules → 3 concepts (equilibrium conditions; FBD problem-solving; stress/strain/Young's modulus). Cold open: structural engineer reviewing a bridge design. |
| 14 | gravitation | 3,716 | 8 source modules → 3 concepts (Newton's law; gravitational PE & escape velocity; Kepler's laws). Cold open: Henry Cavendish 1798 weighing the Earth in his garden shed. Just above the 3,500 floor. |
| 15 | fluid-mechanics | 4,164 | 8 source modules → 3 concepts (pressure & buoyancy; Bernoulli; viscosity & Poiseuille). Cold open: hot-air balloon at dawn. |
| 17 | oscillations | 5,639 | 7 source modules → 3 concepts (SHM; physical pendulums; damping & resonance). Cold open: Tacoma Narrows Bridge collapse, November 7, 1940. |
| 18 | waves | 5,452 | 7 source modules → 3 concepts (traveling waves & wave equation; energy & power; superposition & standing waves). Cold open: Boxing Day 2004 tsunami. Wave equation derived from Newton's second law on a string. |
| 19 | sound | 6,906 | 9 source modules → 3 concepts (longitudinal pressure waves; intensity & decibel scale; Doppler & shock waves). Cold open: Felix Baumgartner breaking the sound barrier in free fall. The book's closer. |

**Totals.** 17 chapters, 89,439 words. 51 companion files (17 each in `pantry/`, `images/`, `bookmaps/`). All chapters above the 3,500-word floor (the leanest is Ch 3 at 3,574; the densest is Ch 19 at 6,906). Forbidden-phrase audit: 6 stray hits in the first pass — mostly "remarkable" used the right way emotionally but the wrong way per the style guide; all replaced with specific-fact language. Final audit: 0 hits across all 17.

**Source folders.** All 17 source subfolders deleted after verification, plus the 2 empty section-divider folders (`01-mechanics/`, `16-waves-and-acoustics/`).

**Filename cleanup.** One issue caught:
- Ch 4 (motion-along-a-straight-line) wrote companion files to a `companions/{pantry,images,bookmaps}/` subfolder that didn't exist in the canonical structure; cleaned up in the final pass by moving them to the canonical companion folders and removing the `companions/` directory. The agent's chapter file itself was at the right path.
- Ch 7 (Applications of Newton's Laws) failed entirely on first dispatch — the agent claimed it couldn't find the source folder. Re-dispatched with the EXACT path emphasized; second agent succeeded at 6,148 words.

**Voice consistency.** Anchored on contemporary-mathematics/chapters/01-sets.md throughout. Cold opens hit canonical physics scenes — Mars Climate Orbiter, Phineas-Gage-equivalent named experiments, Cavendish 1798 weighing the Earth, Apollo 13 mid-burn, Tacoma Narrows 1940, Felix Baumgartner. Calculus on the page — every chapter that needs it shows the derivation: kinematic equations from $v = dx/dt$, work-energy theorem from $\vec{F} = m\,d\vec{v}/dt$, moment of inertia from $\int r^2 dm$, rocket equation by separation of variables, escape velocity from energy conservation, wave equation from Newton's second law on a string, Poiseuille from Newton's viscosity law in pipe geometry.

**TOC.** Rewritten to a flat structure pointing at the 17 chapter files. Numbering preserves the source's 1-19 with chapters 1 and 16 intentionally absent (they were empty section dividers).

**Known follow-ups.**
- Ch 3 (Vectors) at 3,574 and Ch 14 (Gravitation) at 3,716 are just above the 3,500 floor. Both could be expanded; bookmaps name the deferred topics.
- Ch 13 (Static Equilibrium) at 4,452 is also lean; bookmap mentions Poisson's ratio, stress concentrations, and dislocation theory as deferred topics.
- This book is Volume 1. A Volume 2 covering thermodynamics, E&M, optics, and modern physics would complete the standard sequence.
