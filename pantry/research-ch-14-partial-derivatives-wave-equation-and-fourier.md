# Research: Chapter 14 — Partial Derivatives, the Wave Equation, and Fourier Analysis
## Mathematics for Physics

**Chapter one-line:** Math: functions of several variables, partial derivatives, the 1D wave equation as a PDE, superposition, Fourier series, logarithms (decibels) as a coda. Physics source: ch.18/19 (wave on a string; building a tone from harmonics).
**Research date:** 2026-05-30

---

## 1. Primary Sources

### Foundational papers and texts

- **Jean le Rond d'Alembert, "Recherches sur la courbe que forme une corde tendue mise en vibration" (1747; published in the Berlin Academy *Mémoires* 1749).** Derived the 1D wave equation ∂²y/∂t² = c²∂²y/∂x² and gave the general traveling-wave solution y(x,t) = f(x−ct) + g(x+ct) — the *exact* derivation and solution the chapter teaches. This is the foundational primary source and arguably the first genuine partial differential equation. Public domain. (Sources: SciRP "D'Alembert and the Wave Equation"; Jouve, *Centaurus* 2017.)

- **Leonhard Euler (1748–1755) and the d'Alembert–Euler dispute over "arbitrary functions."** Euler insisted the solution f, g could be *any* shape (including a plucked string's corner), forcing a broadening of the very notion of "function" and "continuity"; d'Alembert wanted them restricted to analytic expressions. This 18th-century quarrel — later drawing in Daniel Bernoulli and Lagrange — is the single best *intellectual-history* hook in the book: deciding what counts as a function was a *consequence* of the wave equation. (Sources: Springer "Vibrating Strings and Eighteenth-Century Mechanics"; SciRP.)

- **Daniel Bernoulli, "Réflexions et éclaircissements sur les nouvelles vibrations des cordes" (1753).** Argued that *every* possible string motion is a superposition of the simple sinusoidal modes (harmonics) — i.e., a trigonometric series. Euler rejected the claim that an arbitrary function could be so represented. Bernoulli was essentially right, and his claim is the physical seed of Fourier series: a complex tone is a sum of harmonics. The chapter's "build a tone from harmonics" thread is Bernoulli's idea, vindicated by Fourier. (Sources: SciRP; ch.18/19 standing-wave material.)

- **Joseph Fourier, *Théorie analytique de la chaleur* (1822); earlier 1807 memoir and 1811 prize essay.** Asserted that *any* function — even with jumps — can be written as a series of sines and cosines, and developed the integral formulas for the coefficients. Lagrange *blocked* the 1807 publication (it conflicted with his own 1750s stance on trigonometric series); the prize version (1811) won but was faulted for rigor; the book appeared only in 1822 after Lagrange's death. Full text on Gallica (BnF) and Internet Archive. This is the primary source for the chapter's Fourier-series section. (Sources: Gallica bpt6k1045508v; SophiaRareBooks; ResearchGate.)

- **Reference derivations:** source `chapters/18-waves.md` derives ∂²y/∂x² = (1/v²)∂²y/∂t² from Newton's second law on a string element with v = √(F_T/μ), and treats standing waves/superposition; source `chapters/19-sound.md` gives the decibel β = 10 log₁₀(I/I₀) and the Weber–Fechner basis. These are the in-house derivations to mine.

### Key empirical cases

- **Wave on a taut string, ∂²y/∂t² = v²∂²y/∂x², v = √(F_T/μ).** From source ch.18: apply Newton's second law to a small string element; the net transverse force from the curvature (the second *spatial* derivative) drives the transverse acceleration (the second *time* derivative). The PDE *and* its derivation are fully worked in `chapters/18-waves.md` — the chapter's spine and the motivation for needing partial derivatives at all (two independent variables, x and t).

- **Building a complex tone from harmonics (Fourier synthesis).** From source ch.19/18: a plucked string or a sustained note is a sum of a fundamental and its overtones; adding sinusoids of frequencies f, 2f, 3f, … with the right amplitudes reproduces a sawtooth/square/real instrument waveform. The "periodic signal = sum of sines" claim made concrete and audible — and historically Bernoulli's conjecture proved by Fourier. (Source ch.18 standing waves, ch.19 timbre.)

- **The decibel as a log ratio.** From source ch.19: β = 10 log₁₀(I/I₀), I₀ = 10⁻¹² W/m². A trillion-fold intensity range compresses to 0–120 dB; "+10 dB ≈ ×10 intensity ≈ twice as loud" (Weber–Fechner). The coda case showing logarithms as a *re-scaling* tool. Fully worked example (0.656 Pa → 87 dB) in `chapters/19-sound.md`.

---

## 2. The Core Concept — State of the Field

### What is settled
- A partial derivative ∂f/∂x holds all other variables fixed; for y(x,t), ∂y/∂t is the velocity of a fixed point on the string, ∂y/∂x is the slope of the snapshot. Both are needed; they are different questions.
- The 1D wave equation ∂²y/∂t² = v²∂²y/∂x² has d'Alembert's general solution y = f(x−vt) + g(x+vt): any right-mover plus any left-mover. Sinusoidal solutions A sin(kx−ωt) are the special periodic case, with ω = vk.
- Superposition holds because the equation is *linear*: sums of solutions are solutions. This is why standing waves (sum of two opposite travelers) and Fourier synthesis work.
- Fourier's theorem: a periodic function (meeting mild conditions) equals a sum of sines/cosines at integer-multiple frequencies, with coefficients given by integrals. Settled and exact (with care about discontinuities — Gibbs phenomenon).
- log identities: log(ab) = log a + log b; the decibel turns multiplicative intensity ratios into additive levels.

### What is disputed
- No mathematical dispute at intro level. **Historical:** the wave-equation "arbitrary function" quarrel and the priority/credit around Fourier (blocked by Lagrange; trigonometric series known partially to Euler/Bernoulli/Clairaut before him) are genuine and worth narrating honestly. **Pedagogical:** how much PDE machinery to expose to an intro reader — consensus is "derive the wave equation and its traveling-wave solution, state Fourier and demonstrate it, do not prove convergence."
- Convergence subtleties (Gibbs overshoot at jumps) are settled mathematics but a known student-confusion point; mention, don't belabor.

### What has changed recently (last 5 years)
- Content stable (200-year-old mathematics). Recent PER (2024–2025) on two-variable calculus — Phys. Rev. PER 21 (2025) 010131 and its companion on the gradient/Laplacian — is new and directly relevant to how partial derivatives should be taught; worth citing as current pedagogy evidence. Minimal aging risk for the mathematics.

---

## 3. Application Domain Examples

1. **Transverse wave on a string**: derive the wave equation from F = ma on an element; identify ∂²y/∂x² (curvature) as the restoring agent and v = √(F_T/μ). (Source ch.18.) Headline.
2. **Standing wave as superposition**: A sin(kx−ωt) + A sin(kx+ωt) = 2A sin kx cos ωt — two travelers add to a standing pattern; explains string harmonics and why only certain frequencies resonate. (Source ch.18.)
3. **Fourier synthesis of a tone/timbre**: a sawtooth or square wave = Σ (1/n) sin(nω t) etc.; why a clarinet and a violin playing the same pitch sound different (different harmonic amplitudes). (Source ch.19.)
4. **Decibel scale, β = 10 log₁₀(I/I₀)**: pressure amplitude → intensity → dB; the +3 dB doubling rule; inverse-square fall-off translated to a log scale. (Source ch.19.) The logarithm coda.
5. **Beats as superposition of near-frequencies** (pointer): two close sinusoids add to an amplitude-modulated wave — another superposition payoff. (Source ch.18/19.)

---

## 4. The Book's Thesis Connection

This capstone chapter braids three tools — partial derivatives, a PDE, and Fourier series — and shows the thesis at full strength: the wave on a string is *unintelligible* without the math, and the math (a second derivative in space equaling a second derivative in time) literally *is* the physics. The chapter's contribution to the argument is to demonstrate that "a wave" is not a substance but a *solution to a partial differential equation*, that superposition is just linearity, and that the timbre of a sound is the Fourier content of a periodic function. The decibel coda lands the secondary thesis that even the loudness scale is a mathematical choice (a logarithm) made to match perception.

What the student must supply that a solver cannot: **the modeling and interpretation across two variables.** A computer evaluates ∂²y/∂t² and computes Fourier coefficients, but it cannot decide that y depends on *both* x and t and that the physics couples the spatial curvature to the temporal acceleration; cannot recognize that "a plucked string" sets the initial *shape* f(x) (d'Alembert's arbitrary function — the very thing Euler and d'Alembert fought over); and cannot judge how many Fourier harmonics are "enough" to capture a real tone. The PER literature is explicit that students' core difficulty is *connecting physical context to the partial-derivative math* and consolidating multiple representations — exactly the transferable understanding the book promises. The 18th-century "what is a function?" dispute is the historical proof that this conceptual work, not the computation, is the hard and human part.

---

## 5. The AI Wayback Machine — Candidate Figures

- **Sophie Kowalevski / Sofya Kovalevskaya** — *avoid here* (likely used in ch.11/source ch.11); see alternatives below.

- **Joseph Fourier** (1768–1830, French mathematician and physicist). The Fourier series is his; also (separately) the first to describe the planetary greenhouse effect. Orphaned, nearly guillotined in the Revolution, accompanied Napoleon to Egypt — a vivid life. Famous, so use the *blocked-by-Lagrange* angle to keep it fresh. Anchor prompt: "Joseph Fourier (circa 1820, French mathematician and physicist) — early-nineteenth-century man in formal coat, heat-conduction diagrams and trigonometric-series expansions nearby, historically plausible editorial portrait, face-centered composition, no text, no watermark." **Skew flag:** European man and relatively famous; acceptable as the chapter's namesake but pair with a less-famous figure.

- **Daniel Bernoulli** (1700–1782, Swiss mathematician). Conjectured that any string vibration is a superposition of harmonics — the physical core of Fourier analysis — decades before Fourier, and was overruled by Euler. The "right but disbelieved" figure. (Check collision with ch.11 candidate list; if used there, drop here.) Anchor prompt: "Daniel Bernoulli (circa 1755, Swiss mathematician) — eighteenth-century man in coat and wig, vibrating-string harmonic-mode diagrams nearby, historically plausible editorial portrait, face-centered composition, no text, no watermark." **Skew flag:** European man.

- **Mary L. Cartwright** (1900–1998, English mathematician) OR **Yvonne Choquet-Bruhat** (b. 1923, French mathematician) for diversity. Cartwright worked on Fourier/analytic function theory and nonlinear oscillations; Choquet-Bruhat proved existence theorems for the wave-like Einstein PDEs (first woman elected to the French Académie des sciences) — a genuine "wave equation / PDE" connection. Anchor prompt (Choquet-Bruhat): "Yvonne Choquet-Bruhat (circa 1960, French mathematician) — twentieth-century woman at a desk, partial-differential-equation manuscripts on wave propagation nearby, historically plausible editorial portrait, face-centered composition, no text, no watermark." **Skew flag:** strongly recommended as the female pick — corrects this chapter's male skew and gives a living-era PDE specialist; verify Wikipedia coverage (both have substantial pages).

Set balance: Fourier + a woman (Choquet-Bruhat or Cartwright) is the recommended pairing; the candidate pool here skews male and European, so the female pick is important.

---

## 6. Pedagogical Delivery Research

- **Prerequisites:** single-variable derivatives and second derivatives (ch.06), the sinusoidal wave function y(x,t) = A sin(kx−ωt) and ω = vk (source ch.18), trig identities for the standing-wave sum, and logs (for the coda). Crucially, comfort that a function can depend on *two* independent variables.
- **Most common misconceptions (PER literature):** (a) failing to hold the other variable fixed — treating ∂/∂x like d/dx of a one-variable function; (b) not connecting the partial derivative to its *physical meaning* (∂y/∂t = transverse velocity vs. ∂y/∂x = slope) — the single most documented difficulty; (c) struggling to consolidate multiple representations (graph, formula, physical motion) of the same partial derivative; (d) thinking the wave "is" the moving bump rather than a solution shape, hence confusion that the medium doesn't translate; (e) believing a sum of smooth sines cannot make a sharp corner (Gibbs/Fourier doubt — historically Euler's own doubt). (Sources: Phys. Rev. PER 21 (2025) 010131 "Students' understanding of two-variable calculus… I. The partial derivative"; companion II on gradient/Laplacian; thermodynamics-PD studies, arXiv:1409.8351.)
- **Sequences that work:** introduce partial derivatives *through* the wave — give physical meaning before formal rules; derive the wave equation from a string element so the two second derivatives are *earned*; show d'Alembert's f(x−vt) is a shape that slides (animate/strip); demonstrate Fourier synthesis additively and *audibly* (add harmonics one at a time toward a square wave); end with the decibel as a deliberate log re-scaling.
- **Failure modes in teaching:** introducing partial derivatives as dry multivariable rules divorced from any wave; asserting the wave equation rather than deriving it; presenting Fourier series as a formula dump without showing partial sums approaching the target; treating the decibel as an arbitrary unit instead of a log ratio chosen to match perception.
- **Understand vs. memorize:** the divide is whether the student can *interpret* ∂y/∂t vs. ∂y/∂x physically and *see* that adding harmonics builds a waveform (understanding), versus memorizing the wave equation and the Fourier coefficient formulas (memorizing).

---

## 7. Representation and Display Research

This chapter is display-rich (per the chapter anatomy, the most figure-dependent of the five).
- **Diagram (essential):** the string element free-body / curvature derivation — the small arc with tension at both ends, showing how net transverse force ∝ ∂²y/∂x². Source: ch.18 derivation.
- **Chart (essential):** traveling wave f(x−vt) shown as successive snapshots sliding right, beside a standing wave (fixed envelope, oscillating amplitude) — the two solution types side by side.
- **Chart / multi-panel (essential for Fourier):** progressive Fourier synthesis — fundamental, then +3rd harmonic, +5th, … converging to a square wave, with the target overlaid; shows "periodic signal = sum of sines" and the Gibbs overshoot at the jump. Variables: harmonic number vs. amplitude (a stem/bar "spectrum" panel pairs well).
- **Chart (coda):** decibel vs. intensity on a log axis — the trillion-fold range compressed to 0–120 dB, with everyday sources marked (whisper, conversation, jet). From source ch.19 table.
- **Multi-representation table (useful):** for one wave, the three views — formula y(x,t)=A sin(kx−ωt), the t-snapshot meaning of ∂y/∂x (slope), the x-fixed meaning of ∂y/∂t (velocity) — to combat the consolidation difficulty PER identifies.

---

## 8. Open Questions and Research Gaps

- Exact primary citations: d'Alembert 1747 (Berlin Mémoires 1749) and Bernoulli 1753 should be pinned to page/volume before quoting; the dispute is well documented in secondary history (SciRP, Springer) but the author should confirm primaries. (Minor GAP.)
- Fourier's blocked-1807 / 1811-prize / 1822-book chronology is solid; verify the precise nature of Lagrange's objection if quoting it. (Sourced via SophiaRareBooks and ResearchGate; confirm.)
- This chapter folds *three* major tools plus a coda into one chapter — the heaviest load in the batch. FLAG for the author: it may need the most careful scoping (what to derive vs. state) to fit the intro reader; the PER on partial derivatives suggests not rushing the two-variable conceptual step.
- No source likely to age within 3 years; the 2025 PER papers are the freshest pedagogy evidence and should be cited as current.

## 9. Sourcing Notes
- Fourier's *Théorie analytique de la chaleur* (1822) is public-domain on Gallica (BnF, bpt6k1045508v) and Internet Archive — quote primary; a Cambridge reissue and Dover English translation exist for accessible quotation.
- d'Alembert's and Bernoulli's memoirs are public-domain (Berlin Academy); the SciRP and Springer secondary histories are reliable for the dispute narrative — cite them for interpretation, the memoirs for the claims.
- The 2025 Phys. Rev. Phys. Educ. Res. partial-derivative papers are peer-reviewed and paywalled-abstract/open-PDF in places (ResearchGate copies exist) — the strongest current pedagogy sources; cite the journal.
- Source chapters 18 and 19 contain in-house, already-vetted derivations (wave equation, decibel worked example) — use them directly for worked examples.
