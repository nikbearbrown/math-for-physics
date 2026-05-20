# Bookmap: Waves

Mining sources for writing ideas: explanations, worked examples, alternative angles, and gaps.

This map is a harvest of ideas, not a summary of the sources.

---

## Source 1: OpenStax University Physics (Waves, Chapters 16–17)

**URL:** https://openstax.org/books/university-physics-volume-1

**What it teaches:**
Opens with a concrete image (buoy converting ocean wave motion to electricity). Establishes the practical stakes immediately—waves carry power. Moves systematically through wave characteristics: amplitude, wavelength, period, frequency, speed. Introduces transverse/longitudinal distinction with careful examples (strings vs. springs). Uses water waves and seagulls as a recurring visual anchor.

**Key mechanism explained:** Wave function derivation from simple spatial snapshot plus translation. $y(x) = A \sin(kx)$ at $t=0$; replace $x$ with $x - vt$ to get $y(x,t) = A \sin(k(x - vt))$. This is clean and visual.

**Trade-off discussion:** The source notes that superposition works only for small amplitudes (linear regime). Acknowledges the nonlinear breakdown without dwelling on it. Practical boundary: amplitude small relative to wavelength.

**Scale shift:** Seismic waves (S-waves and P-waves) travel at different speeds through Earth's interior. Timing difference between arrivals determines earthquake epicenter location. Nice transition from lab-scale string to planetary scale.

**Gaps:** Does not derive the wave equation from Newton's laws; states it. Does not explain why $v = \sqrt{F_T/\mu}$ from first principles—just asserts it. Standing waves appear suddenly without motivation. Could be stronger on the mechanism.

**Worked examples:** Guitar string tension change (how to keep speed constant when changing density); ultrasonic coating thickness measurement (inverse problem: given time delay, find thickness).

**Ideas to harvest:**
- Cold open with energy conversion (buoy) is effective. Motivates "why waves matter."
- Seagull + water waves is a memorable image for transverse motion. Keeps reappearing.
- Matching impedance section (wave crossing from one string to another) is underexplored in typical texts. Good for trade-off discussion.

---

## Source 2: Halliday, Resnick, Walker - Fundamentals of Physics (Chapters 16–17)

**URL:** Standard undergraduate textbook

**What it teaches:**
Heavy on calculus. Derives $v = \sqrt{F_T/\mu}$ from Newton's second law on a string element. Shows the algebra cleanly: net force is the difference in slopes at two points, leading to $\partial^2 y / \partial x^2 = (1/v^2) \partial^2 y / \partial t^2$. This derivation is the gold standard.

**Energy derivation:** Integrates kinetic energy over one wavelength, finds $K_\lambda = (1/4) \mu A^2 \omega^2 \lambda$. Shows that potential energy equals kinetic energy (on average). Total energy per wavelength: $E_\lambda = (1/2) \mu A^2 \omega^2 \lambda$. Time-averaged power: $P_{\text{ave}} = E_\lambda / T = (1/2) \mu A^2 \omega^2 v$. Every step is explicit.

**Standing wave algebra:** Two counter-propagating sine waves added: $\sin(kx - \omega t) + \sin(kx + \omega t) = 2 \sin(kx) \cos(\omega t)$ using trig identity. Factorization into spatial and temporal parts. Nodes at $kx = n\pi$. This is the canonical approach.

**Superposition:** Linear wave equation proof. If $y_1$ and $y_2$ satisfy the wave equation, so does $y_1 + y_2$. Direct consequence of linearity of the differential operator.

**Strengths:**
- Derivations shown completely. Algebra not skipped.
- Multiple worked examples with numbers.
- Conceptual questions force deeper thinking.
- Problems at multiple difficulty levels.

**Gaps:**
- Very dense. Conceptual narrative gets buried in algebra.
- Motivation (why should you care?) is implicit, not explicit.
- Boundary conditions and reflections are mentioned but not deeply explored.
- Nonlinear waves not discussed at all.

**Ideas to harvest:**
- The derivation of $v = \sqrt{F_T/\mu}$ is cleanest here. Use this exact path.
- Energy integration over wavelength is instructive. Show how $\cos^2$ and $\sin^2$ average to 1/2.
- The identity $\sin(\alpha \pm \beta) = \sin \alpha \cos \beta \pm \cos \alpha \sin \beta$ is crucial for standing waves. Worth teaching explicitly.
- Numerical examples are thorough and realistic.

---

## Source 3: Feynman Lectures on Physics, Vol. 1, Chapter 47 (Sound, Waves)

**URL:** https://www.feynmanslectures.caltech.edu/

**What it teaches:**
Opening: "Why do we care about waves? Because they are everywhere—sound, light, water, even matter itself at quantum scales. But let's start simple: waves on a string."

Uses the string as a toy model to understand general principles. Introduces the **idea of propagation**: why a disturbance travels at a constant speed. The tension pulls the next segment along; that segment pulls the next; and so on. The speed depends on how strongly each segment couples to the next (tension) and how much mass resists (density). Mechanical intuition before algebra.

**Doppler effect:** Derives it from first principles for a moving source. "If you move toward the wave source, you encounter more wavefronts per second. If you move away, you encounter fewer." Simple, direct.

**Energy and power:** "Power is force times velocity." In a wave, the force oscillates, and so does the velocity. Average power is the time-average of their product. Connects to the formula $P \propto A^2 \omega^2$.

**Standing waves as eigenvalues:** A string fixed at both ends can only resonate at certain frequencies because the reflected wave must interfere constructively with the incident wave. These frequencies are "eigenfrequencies" or "modes" of the system. The system "selects" which frequencies can survive. Eigenfunctions of the operator $\partial^2/\partial x^2$ are $\sin(nπx/L)$.

**Conceptual gaps:** Does not derive the wave equation in detail. Does not discuss nonlinearity. But the physical intuition is crystal clear.

**Register:** Conversational. Assumes intelligence but not advanced preparation. Explains the "why" before the "how."

**Ideas to harvest:**
- Start with physical intuition: coupling + inertia → wave speed.
- Propagation mechanism is key insight: each segment pulls the next.
- Doppler derivation by counting wavefronts is simple and memorable.
- Eigenvalue language for standing waves: the system "selects" frequencies.
- Register is conversational without being vague. A model for voice.

---

## Source 4: Alonso & Finn - Fundamental University Physics, Vol. 1 (Waves section)

**What it teaches:**
Emphasizes the wave equation as the central object. "Any function $f(x - vt)$ is a solution to the wave equation. Proof: substitute and verify. So waves can have any shape—sine, square, pulse, whatever—as long as they propagate at speed $v$."

**Interesting pedagogical move:** Introduces the wave function via a **graphical approach first**, before algebra. Take a snapshot of the wave at $t = 0$: $y(x) = f(x)$. Now imagine the whole pattern shifts to the right by distance $d$. The new pattern is $y(x) = f(x - d)$. If the shift happens at speed $v$ over time $t$, then $d = vt$, and $y(x,t) = f(x - vt)$. This is intuitive.

**Boundary value problems:** Emphasizes that the solution to the wave equation is not unique until you specify boundary conditions (what happens at the ends) and initial conditions (shape and velocity at $t = 0$). A string fixed at both ends has very different standing waves than a string with one fixed and one free end.

**Reflection and transmission:** Derives the reflection and transmission coefficients for waves crossing from one medium to another. Impedance mismatch. Energy conservation: reflected power + transmitted power = incident power.

**Strengths:**
- Conceptual narrative is strong.
- Graphical intuition before algebra.
- Boundary conditions treated as important, not afterthought.

**Gaps:**
- Fewer worked examples than Halliday & Resnick.
- Energy derivation is sketched, not shown in detail.
- Does not discuss damping or quality factor.

**Ideas to harvest:**
- Graphical introduction to wave function: shift a snapshot over time.
- Emphasis on boundary conditions as essential, not optional.
- Impedance mismatch and reflection/transmission deserves more space.
- The wave equation satisfied by any $f(x \mp vt)$, not just sine.

---

## Source 5: Crawford - Waves (Berkeley Physics Course, Vol. 3)

**URL:** Specialized monograph; old but still cited

**What it teaches:**
This is a waves-focused text, much deeper than introductory chapters. But the first few chapters are accessible and excellent.

**Emphasizes mechanism over formula:** "A wave is a means of energy transport. The energy is carried by the oscillations of the medium, coupled from point to point. Understand the coupling, and you understand the wave."

**Group velocity and phase velocity:** Introduces the idea that $v_{\text{phase}} = \omega / k$ and $v_{\text{group}} = d\omega / dk$ can be different. In a non-dispersive medium (like an ideal string), they are the same. But in water waves (gravity vs. capillary), they differ. This explains why a group of waves on the ocean moves slower than the individual ripples within it.

**Dispersion relation:** The relationship between $\omega$ and $k$ (e.g., $\omega = \sqrt{gk}$ for deep-water gravity waves) determines all dynamics.

**Resonance from energy perspective:** A system resonates at frequencies where the driving force phase-locks with the oscillation. Energy is transferred most efficiently when the driving and oscillating motions are in phase.

**Nonlinear waves:** Brief discussion of how amplitudes become comparable to wavelength, and the linear approximation breaks down. Shock formation. Solitons.

**Strengths:**
- Deeper than intro texts.
- Energy and mechanism emphasized throughout.
- Group velocity and dispersion are worth knowing.
- Nonlinearity mentioned (even if not fully explored).

**Limitations for this chapter:**
- Too advanced for an intro physics course.
- Assumes more background (Fourier analysis, complex notation).
- But *sections* of it (on resonance, energy, mechanism) are inspirational.

**Ideas to harvest:**
- Mechanism (coupling + inertia) is the heart of understanding.
- Group velocity / phase velocity distinction: worth a mention, even if not fully developed.
- Resonance from energy perspective: force and oscillation in phase.
- Nonlinearity: acknowledge where breakdown occurs.

---

## Cross-Source Ideas Harvest

### Puzzles and Cold Opens
- **2004 Indian Ocean tsunami:** Scale (planetary), consequence (devastating), and accessible physics ($v = \sqrt{gh}$). This is a strong opening.
- **Guitar string tuning:** Immediate, hands-on, musical. Why does tension matter? Why does length matter? Natural entry point to standing waves and pitch.
- **Seismic waves and earthquake location:** S-waves and P-waves travel at different speeds. Time difference → distance to epicenter. Practical application of wave mechanics.
- **Ocean ripples passing through each other:** Why don't they bounce? Superposition as surprise.
- **Buoy energy conversion:** Waves carry energy. Extraction is engineering problem.

### Mechanisms Worth Featuring
- **Coupling and inertia determine wave speed:** Not just a formula. The idea that tension pulls the next segment, and mass resists, leads directly to $v = \sqrt{F_T/\mu}$.
- **Propagation from first principles:** Derive from Newton's second law on a small element.
- **Energy as superposition of kinetic and potential:** Integrate over wavelength. Show how they alternate.
- **Boundary conditions as selection principle:** Fixed end → nodes. Free end → antinodes. String "chooses" frequencies.
- **Impedance and reflection:** Why do some waves transmit and others reflect?

### Trade-offs and Limitations
- **Superposition fails at large amplitude:** When amplitude comparable to wavelength, restoring force is nonlinear.
- **Wave equation is approximate:** Assumes continuum medium, no atomic-scale roughness.
- **Damping absent in ideal case:** Real strings lose energy; amplitude decays.
- **Dispersion not addressed:** For non-dispersive media, phase velocity = group velocity. For water waves, they differ.

### Scale Shifts
- Lab-scale string → seismic waves through Earth → gravitational waves through spacetime.
- Local standing wave on guitar → resonance in concert hall → resonance in atomic cavity (laser).
- Water wave on a pond → tsunami across an ocean → tidal waves on exoplanets.

### Worked Examples Worth Including
- **String with given tension and density:** Calculate wave speed, resonant frequency.
- **Ultrasonic thickness measurement:** Pulse-echo, time delay → thickness (inverse problem).
- **Power delivered to vibrating string:** Given amplitude, frequency, density, tension—find power.
- **Standing wave modes on string of length $L$:** Node and antinode locations for $n = 1, 2, 3$.
- **Tsunami speed in deep vs. shallow water:** Use $v = \sqrt{gh}$; verify with known values.
- **Doppler shift:** Moving source or observer; calculate frequency change.

### Conceptual Questions That Deepen Understanding
- Why does a heavier string (higher $\mu$) produce a lower frequency note for the same tension and length?
- Why does increasing tension on a guitar string raise the pitch?
- In a standing wave, why are nodes always stationary while antinodes oscillate?
- Why can two waves pass through each other without scattering?
- Why does the wavelength shorten as a tsunami enters shallow water (at constant frequency)?
- What happens to a standing wave if you introduce damping?

### Extensions Beyond Chapter Scope
- **Quantum waves:** Electrons and atoms have wave properties. The wavefunction $\psi(x,t)$ obeys the Schrödinger equation, which is wave-like.
- **Electromagnetic waves:** No medium required. Speed is always $c$. Maxwell's equations are the "wave equation" for $E$ and $B$ fields.
- **Nonlinear waves:** Shock waves, solitons, weak turbulence.
- **Waveguides and cavities:** 3D confinement (not just 1D string). Modes of a rectangular cavity.
- **Interference and diffraction:** Multiple sources, obstacles, thin slits.

---

## Source-Specific Pitfalls to Avoid

1. **From OpenStax:** Be careful not to state "the wave equation is ..." without deriving it. Derivation adds credibility and understanding.

2. **From Halliday & Resnick:** Avoid burying conceptual narrative in algebra. Alternate: explain idea in words, then show the math.

3. **From Feynman:** Don't oversimplify to the point of imprecision. "Waves are cool" is not an explanation.

4. **From Alonso & Finn:** Don't assume graphical intuition alone is sufficient for students new to calculus. Follow with algebraic verification.

5. **From Crawford:** Don't assume advanced background. Mention group velocity and dispersion, but don't require mastery.

---

## Recommended Reading Order (for instructor/author)

1. **Start with Feynman:** For conceptual clarity and voice.
2. **Move to Halliday & Resnick:** For complete derivations.
3. **Reference OpenStax:** For worked examples and practical applications.
4. **Consult Alonso & Finn:** For pedagogical sequencing (graphical first, algebra second).
5. **Dip into Crawford:** For depth on resonance, energy, and mechanism.

---

## Open Questions and Gaps in Standard Treatments

1. **Atomic-scale breakdown of continuum assumption:** At what wavelength (or amplitude) does the continuum approximation fail? This is rarely discussed in intro texts.

2. **Nonlinear regime:** When amplitude approaches wavelength, the linear wave equation fails. What happens? Shock formation is mentioned but rarely explained.

3. **Dissipation and quality factor:** How does damping change the resonance curve? Why is the quality factor $Q = f_0 / \Delta f$ important? Usually omitted.

4. **Dispersive media:** Water waves, light in glass—where phase velocity ≠ group velocity. Why does this matter? Rarely covered in intro physics.

5. **Quantum waves:** The connection to matter waves (de Broglie, Schrödinger) is profound but typically deferred to modern physics. A forward reference might be valuable.

---

## Final Harvest Summary

**Strongest elements to include:**
- Cold open with tsunami and depth-dependent wave speed
- Derivation of wave equation from Newton's second law
- Energy calculation: integrate over wavelength
- Standing waves from superposition of counter-propagating waves
- Resonant frequencies from boundary conditions
- Worked example: guitar string tuning

**Strongest pedagogical moves:**
- Physical intuition first (coupling + inertia → speed)
- Graphical snapshots before algebra
- Boundary conditions as physics, not formalism
- Scale shift (string → seismic → gravitational)

**Register and voice:**
- Conversational, not condescending
- Explain "why" before "how"
- Acknowledge limitations and gaps
- Use memorable images (seagull, guitar, tsunami)

