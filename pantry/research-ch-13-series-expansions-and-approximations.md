# Research: Chapter 13 — Series, Expansions, and Approximations
## Mathematics for Physics

**Chapter one-line:** Math: sequences/series, Taylor/Maclaurin expansion, small-angle & binomial approximations, convergence intuition. Physics source: ch.17 (sin θ ≈ θ for the pendulum).
**Research date:** 2026-05-30

---

## 1. Primary Sources

### Foundational papers and texts

- **Mādhava of Sangamagrāma (c. 1340–c. 1425) and the Kerala school.** Discovered the power-series expansions of sine, cosine, and arctangent — and the π/4 (Madhava–Leibniz) series — roughly 250 years before Newton and Taylor, *with* error/correction terms showing he grasped the limit nature of the series. Preserved in later Kerala texts (Nilakantha's *Tantrasangraha*; the *Yuktibhāṣā*). This is the chapter's strongest historical anchor and a genuine non-Western primary lineage: the sine series the chapter derives was first found in 14th-c. Kerala. (Sources: Wikipedia "Madhava of Sangamagrama" and "Madhava series"; arXiv:2405.11134 on the correction terms.)

- **Brook Taylor, *Methodus Incrementorum Directa et Inversa* (1715).** First *European* publication of the general expansion f(a+h) = Σ f⁽ⁿ⁾(a)hⁿ/n! — though Gregory, Newton, and Leibniz knew special cases earlier. Taylor's theorem went unrecognized until Lagrange (1772) called it "the main foundation of differential calculus." Use to frame the general Taylor formula the chapter builds. (Sources: MacTutor "Brook Taylor"; LibreTexts "Taylor's Formula.")

- **Colin Maclaurin, *A Treatise of Fluxions* (1742).** Contains the a = 0 special case — the Maclaurin series — which is exactly the form the chapter uses for sin x, cos x, eˣ expanded about 0. Maclaurin credited Taylor; the name stuck to the special case. (Sources: MacTutor; LibreTexts.)

- **Isaac Newton, generalized binomial theorem (c. 1665, communicated 1676 in the *Epistola prior* to Oldenburg/Leibniz).** (1+x)ⁿ = 1 + nx + n(n−1)x²/2! + … for any real n — the source of the binomial *approximation* (1+x)ⁿ ≈ 1 + nx for small x that the chapter needs (relativistic/√ expansions, etc.). Public-domain primary lineage. (Standard history; MacTutor.)

- **Joseph-Louis Lagrange (1772, and *Théorie des fonctions analytiques*, 1797).** Recognized Taylor's theorem as foundational and supplied the *remainder term* (Lagrange form), which is what makes "truncate after n terms with bounded error" rigorous — the conceptual backing for the small-angle and binomial approximations. (Source: MacTutor "Brook Taylor"; LibreTexts.)

### Key empirical cases

- **The pendulum's small-angle approximation, sin θ ≈ θ.** From source ch.17: the exact pendulum equation θ̈ = −(g/L) sin θ is *not* the harmonic-oscillator equation and has no elementary solution. Replacing sin θ by the first term of its Taylor series (θ) linearizes it to θ̈ = −(g/L)θ, which *is* SHM, giving T = 2π√(L/g). This is the chapter's spine: a Taylor truncation is the move that makes the physics solvable. Documented in `chapters/17-oscillations.md` (pendulum / small-angle sections).

- **Binomial approximation in a √ expression.** Wherever a physics formula contains √(1 ± x) or (1 ± x)ⁿ with small x — e.g., expanding a potential, a period correction, or √(1 − v²/c²) — (1+x)ⁿ ≈ 1 + nx collapses it to a linear estimate. A clean worked example: the next-order pendulum correction T ≈ 2π√(L/g)(1 + θ₀²/16) comes from keeping the cubic term of sin θ. (Standard; pendulum amplitude correction.)

- **Why eˣ, sin, cos series matter for ch.12.** The series for eˣ, cos x, sin x are the proof of Euler's formula (substitute iθ into the eˣ series and split). The chapter's derivations of these three Maclaurin series are the prerequisite for the previous chapter's central identity — note the (deliberate) back-reference. (Source: ch.12 research file; Euler *Introductio* 1748.)

---

## 2. The Core Concept — State of the Field

### What is settled
- Any sufficiently smooth function has a Taylor series Σ f⁽ⁿ⁾(a)(x−a)ⁿ/n!; truncating it gives a polynomial approximation whose error is bounded by the Lagrange remainder.
- The Maclaurin series sin x = x − x³/3! + x⁵/5! − …, cos x = 1 − x²/2! + …, eˣ = Σ xⁿ/n! are exact and converge for all real x.
- Small-angle: for small θ (radians), sin θ ≈ θ, cos θ ≈ 1 − θ²/2, tan θ ≈ θ; these are first/second Taylor truncations, *not* coincidences.
- Binomial: (1+x)ⁿ ≈ 1 + nx for |x| ≪ 1, any real n (Newton's generalized binomial theorem).
- Convergence has a *radius*: some series (e.g., 1/(1−x) = Σ xⁿ) converge only for |x| < 1 — a fact students must meet even at intuition level.

### What is disputed
- No mathematical dispute at this level. **Pedagogical:** how much convergence *rigor* to demand of intro-physics students — the consensus in PER is "intuition and the radius/truncation idea, not ε–N proofs." **Historical priority/credit:** Taylor's name on a result known earlier to Gregory/Newton/Leibniz and *much* earlier to Madhava — a live equity issue worth naming honestly (the "Madhava–Taylor"/"Madhava–Gregory–Leibniz" relabeling is increasingly used).

### What has changed recently (last 5 years)
- Content stable. Growing scholarship (incl. arXiv:2405.11134, 2024) on Madhava's correction terms continues to strengthen the case for crediting the Kerala school — relevant to the chapter's historical framing and its diversity commitments. Minimal aging risk for the mathematics.

---

## 3. Application Domain Examples

1. **Pendulum small-angle linearization, sin θ ≈ θ** → SHM and T = 2π√(L/g). (Source ch.17.) The headline application.
2. **Amplitude correction to the pendulum period** using the next Taylor term of sin θ: T ≈ 2π√(L/g)(1 + θ₀²/16). Shows why "small angle" is an approximation with a measurable error.
3. **Binomial approximation (1+x)ⁿ ≈ 1+nx** in expanding a force/potential or √ expression — e.g., the leading correction to a near-equilibrium potential energy U(x) ≈ U₀ + ½U″x², itself a Taylor expansion that *defines* the effective spring constant and explains why *any* smooth potential near a minimum is harmonic. (Connects ch.11 and ch.17.)
4. **Linearizing a restoring force** F(x) ≈ F(0) + F′(0)x near equilibrium — the universal reason small oscillations are simple harmonic regardless of the force law.
5. **eˣ, sin x, cos x series** as the bridge that proves Euler's formula (ch.12) and underlies the exponential decay/growth of ch.11.

---

## 4. The Book's Thesis Connection

This chapter most directly embodies the thesis "the physics is solvable *because* of a mathematical move." The pendulum is the case study every intro course uses, and the secret is rarely stated: sin θ ≈ θ is not a simplification of convenience but a *Taylor truncation* with a controllable error. The chapter's contribution to the argument is to expose the hidden math step — to show that "assume small angle" means "keep the first term of a Taylor series" — and thereby convert a memorized shortcut into a general, transferable technique.

What the student must supply that a solver cannot: **the judgment of when to truncate and at what order, and the awareness of the error incurred.** A CAS can spit out the full Taylor series, but it cannot decide that θ = 5° is "small enough" to drop the θ³ term for *this* problem, cannot recognize that expanding a potential about its minimum is the move that reveals SHM, and cannot tell you that the approximation breaks for a wide-swinging pendulum. The PER literature is explicit that students fixate on surface features and struggle to reason about *truncation* — exactly the conceptual skill the book wants installed, and exactly what no algorithm supplies. This is the cleanest chapter for the "math-as-judgment, not math-as-computation" claim.

---

## 5. The AI Wayback Machine — Candidate Figures

- **Mādhava of Sangamagrāma** (c. 1340–c. 1425, Indian mathematician-astronomer, Kerala school). Found the sine, cosine, and arctangent power series — the chapter's core content — centuries before Europe, with error terms. The ideal anchor: non-Western, pre-Newtonian, *worked precisely on the thing*. Anchor prompt: "Mādhava of Sangamagrāma (circa 1400, Indian mathematician and astronomer of the Kerala school) — South Asian scholar in medieval Kerala dress, palm-leaf manuscripts with infinite-series and sine-table calculations nearby, historically plausible editorial portrait, face-centered composition, period-appropriate setting, no text, no watermark." **Skew flag:** outstanding diversity pick (non-Western, 14th c.); no authentic likeness exists, so rely entirely on period plausibility — flag that the image is necessarily imagined. Strongly recommended primary.

- **Colin Maclaurin** (1698–1746, Scottish mathematician). The Maclaurin series (a = 0 case) is the exact form the chapter uses; child prodigy, defended Newton's calculus, organized Edinburgh's defenses in the 1745 Jacobite rising. Anchor prompt: "Colin Maclaurin (circa 1740, Scottish mathematician) — eighteenth-century man in coat and wig, a fluxions treatise and power-series expansions nearby, historically plausible editorial portrait, face-centered composition, no text, no watermark." **Skew flag:** European man; use as secondary if Madhava is placed elsewhere.

- **Mary Cartwright** (1900–1998, English mathematician). Worked on the convergence and analytic theory of functions and on nonlinear oscillations (the Cartwright–Littlewood work seeded chaos theory) — a genuine "series/convergence and oscillation" connection, and a woman in analysis. Anchor prompt: "Mary Cartwright (circa 1945, English mathematician) — twentieth-century woman in 1940s attire, analysis notes on series convergence and oscillating systems nearby, historically plausible editorial portrait, face-centered composition, no text, no watermark." **Skew flag:** corrects gender skew; recommended as the female option for this chapter (and could anchor ch.12 instead if needed). 

Set balance: Madhava + Cartwright give a non-Western/female pair — the strongest combination across the five chapters; prefer them.

---

## 6. Pedagogical Delivery Research

- **Prerequisites:** higher derivatives (ch.06), factorials and summation notation, the value of derivatives of sin/cos/eˣ at 0, and radians (ch.03) — the small-angle results *only* hold in radians, a frequent stumble.
- **Most common misconceptions (math-ed / PER literature):** (a) students fixate on surface features of the series and miss the structural idea of approximating a function by a polynomial; (b) genuine difficulty reasoning about *truncation* — when and why dropping higher terms is legitimate; (c) treating convergence as all-or-nothing and ignoring the radius/interval of convergence; (d) using sin θ ≈ θ with θ in degrees. (Sources: Martin & Oehrtman et al., *Educational Studies in Mathematics* 79 (2012) "Differences between experts' and students' conceptual images… of Taylor series convergence"; PRPER 9 (2013) 020110 "Student understanding of Taylor series in statistical mechanics"; ACER framework arXiv:1207.0987.)
- **Sequences that work:** motivate with a function you *can't* integrate/solve exactly (the pendulum), then show the truncation rescues it; build sin/cos/eˣ series by repeated differentiation at 0 so the pattern is *derived*; show the partial sums converging graphically (the polynomial hugging the curve over a widening interval); make the error explicit (plot sin θ − θ) so "small angle" has a number attached.
- **Failure modes in teaching:** presenting the Taylor formula abstractly before any motivating approximation; asserting sin θ ≈ θ without deriving it from the series; never showing the *error*, so students think the approximation is exact; ignoring convergence entirely so series feel like magic.
- **Understand vs. memorize:** the divide is whether a student can *derive* sin θ ≈ θ as a truncation and estimate the dropped term (understanding) versus reciting the small-angle rule (memorizing). The book's "derive on the page" rule is the remedy.

---

## 7. Representation and Display Research

- **Chart (essential):** sin θ plotted with its successive Taylor approximations (θ; θ − θ³/6; θ − θ³/6 + θ⁵/120) overlaid, showing each higher polynomial hugging the curve over a wider interval — makes convergence and truncation *visible*. From source ch.17 angle range.
- **Chart:** the error |sin θ − θ| (or percent error) vs. θ, with a marker at ~10–15° showing where the small-angle approximation crosses a chosen tolerance — gives "small" a quantitative meaning.
- **Infographic (optional):** a timeline/lineage strip — Madhava (c.1400) → Gregory/Newton/Leibniz (1660s–70s) → Taylor (1715) → Maclaurin (1742) → Lagrange remainder (1797) — honest credit for the series.
- Otherwise no special display required.

---

## 8. Open Questions and Research Gaps

- Precise primary citations for Madhava's series survive only through later Kerala texts (Nilakantha, *Yuktibhāṣā*); the author should cite the transmitting text, not Madhava directly, and note the attribution chain. (GAP — primary documents are second-hand.)
- The exact wording/location of Taylor's 1715 statement and Newton's binomial communication should be pinned before quoting. (Minor GAP.)
- Convergence rigor: decide how much to include for the intro reader; research supports intuition-level treatment but the author should state explicitly what is asserted vs. proved (per the book's calibration rule).
- No source likely to age within 3 years; recent Madhava scholarship only strengthens the historical section.

## 9. Sourcing Notes
- The Taylor/Maclaurin priority and the Madhava precedence are well documented in MacTutor and peer-reviewed history (arXiv:2405.11134); cite those, not the SEO/blog hits (storyofmathematics, vedicmathschool, etc.).
- The PER sources (Educational Studies in Mathematics 2012; PRPER 2013; ACER arXiv) are peer-reviewed and directly on *Taylor-series* student difficulties — the strongest pedagogy evidence of any chapter in this batch.
- Maclaurin's *Treatise of Fluxions* and Taylor's *Methodus Incrementorum* are public-domain primary sources.
