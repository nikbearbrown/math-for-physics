# Bookmap: Sound (OpenStax University Physics 17, Attenborough × Feynman Voice)

## Overview of Source Material

OpenStax University Physics Section 17 ("Sound") is a comprehensive treatment of sound waves, acoustic phenomena, and resonance in tubes. The source is structured as a series of micro-sections (17.1 "Sound Waves," 17.2 "Speed of Sound," 17.3 "Intensity and Sound Level," 17.4 "Interference," 17.5 "Sources of Sound," 17.6 "Beat Frequency," 17.7 "Doppler Effect," 17.8 "Shock Waves") followed by conceptual questions and numerical problems. The pedagogy is standard textbook: define terms, derive formulas, apply to examples.

This bookmap extracts the load-bearing ideas, the opportunities for scene-setting, and the conceptual levers a textbook author can use.

---

## What Each Section Actually Teaches

### Section 17.1 — Sound Waves
**Core teaching:** Sound is a longitudinal pressure wave. Molecules oscillate parallel to wave propagation (unlike transverse waves). A speaker moving back and forth compresses the air in front of it (compressions) and creates lower-pressure zones behind it (rarefactions). Both the pressure model $\Delta P = \Delta P_{\max} \sin(kx - \omega t + \phi)$ and the displacement model $s = s_{\max} \cos(kx - \omega t + \phi)$ are correct; they describe the same phenomenon two ways.

**What the text does well:** Clear diagrams showing speaker, compressions, rarefactions. Good use of the wave equation $\frac{\partial^2 y}{\partial x^2} = \frac{1}{v^2} \frac{\partial^2 y}{\partial t^2}$ as the governing principle. Mentions that sound travels through all media (except vacuum) and that the human ear detects frequencies from 20 Hz to 20 kHz.

**Missed opportunity:** The section doesn't explain *why* longitudinal waves are the natural mode in fluids (no shear strength). It also doesn't anchor sound in an everyday observation before diving into mathematics. It could open with "You hear your friend's voice across a noisy room because sound bends around obstacles, something light does not. Why?" and then explain diffraction and wavelength. Instead it starts with "The physical phenomenon of sound is a disturbance of matter transmitted from its source outward."

**For a Feynman writer:** The puzzle to open on is why we can *hear* sound, not just *see* it traveling. That requires understanding the longitudinal wave mechanism and the frequency range. A better opening: "Why can you hear a sound from behind a closed door but not see the light from the room?" Answer involves wavelength and diffraction, which in turn requires knowing that sound is longitudinal and travels in a medium (unlike light, which is transverse and travels through vacuum). This connects to later chapters and forces the student to engage with why sound is special.

---

### Section 17.2 — Speed of Sound
**Core teaching:** Speed of sound in a medium is $v = \sqrt{\text{elastic property} / \text{inertial property}}$. For fluids: $v = \sqrt{B/\rho}$ (bulk modulus / density). For solids: $v = \sqrt{Y/\rho}$ (Young's modulus / density). For ideal gases: $v = \sqrt{\gamma RT_K / M}$. Sound travels faster in rigid materials (high $B$ or $Y$) and slower in dense materials (high $\rho$). Temperature affects gas sound speeds.

**What the text does well:** Derivation from Newton's second law and continuity equation (mass conservation). Specific values for different media (water, steel, air at different temperatures). The insight that speed is nearly independent of frequency is mentioned but not explored deeply.

**Missed opportunity:** The text doesn't explain the physical intuition. Why does a stiffer material transmit sound faster? Because neighboring molecules are held tightly together, so a compression is quickly transmitted to them. Why does density slow sound down? Because more massive molecules are harder to accelerate. This intuition could be developed with a brief analogy: "A spring compressed tightly transmits a push faster than a spring compressed loosely; a mass on the spring moves slower the heavier it is. Sound is the same: $v = \sqrt{\text{stiffness}/\text{mass}}$." The text gives the formula and the numbers but not the mechanical picture.

**For a Feynman writer:** Open with a puzzle: "A heavier gas should slow sound down, right? Helium is lighter than air, so sound should be faster in helium. But what about a very light but very springy material vs. a very dense but very stiff material? Which wins?" Then solve it with $v = \sqrt{B/\rho}$. The table of speed values (water faster than air, steel faster than water) becomes a puzzle to explain, not just a lookup. This engages curiosity before formula.

---

### Section 17.3 — Intensity and Sound Level
**Core teaching:** Intensity $I = \langle P \rangle / A$ is power per area (W/m²). For a spherical wave spreading outward, $I_2 = I_1(r_1/r_2)^2$ (inverse square law). The intensity of sound is related to pressure amplitude: $I = (\Delta P_{\max})^2 / (2\rho v)$. Human hearing spans roughly $10^{-12}$ W/m² (threshold) to $10^0$ W/m² (pain), a trillion-to-one range. The sound intensity level is the decibel scale: $\beta = 10 \log_{10}(I/I_0)$ where $I_0 = 10^{-12}$ W/m².

**What the text does well:** Careful definition of the decibel and explanation of logarithmic response. Table of common sounds and their intensities. Discussion of how the ear's sensitivity varies with frequency (equal-loudness curves, phons vs. decibels). Recognition that decibels are a convenience, not a physical law.

**Missed opportunity:** The text doesn't adequately explain *why* the ear is logarithmic. Weber-Fechner law is mentioned but not connected to the evolutionary purpose: animals need to detect a huge range of stimuli, from whispers to nearby explosions, with a single sense organ. If ears were linear, they could not do this. The logarithmic response is an evolutionary adaptation. This context makes the choice of the decibel scale feel natural, not arbitrary. Also, the text could do more with the reference intensity $I_0 = 10^{-12}$ W/m² — why this specific value? Because it corresponds to the quietest sound a healthy human ear can detect at 1 kHz (the frequency the ear is most sensitive to). This grounds the reference in biology, not mathematics.

**For a Feynman writer:** Open: "If ears worked like voltmeters — reporting intensity linearly — we could hear a whisper or an explosion, but not both. A whisper is a trillion times quieter than a jet engine. If a scale had to span that range linearly, the difference between a whisper and a library would be a rounding error." Then explain that the ear is logarithmic, and the decibel scale matches the ear. Make the scale feel like a discovery, not a definition.

---

### Section 17.4 — Interference
**Core teaching:** Sound waves can interfere constructively (in-phase, amplifies) or destructively (out-of-phase, cancels). When two identical waves with a path-length difference $\Delta r = n\lambda$ (integer multiple of wavelength) arrive at a point, they interfere constructively. When $\Delta r = (n + 1/2)\lambda$ (odd multiple of half-wavelength), they interfere destructively. Noise-canceling headphones use destructive interference to cancel ambient noise.

**What the text does well:** Clear diagrams showing two speakers producing constructive and destructive interference at different locations. Worked example with students and a sound-level meter finding the first null (destructive interference).

**Missed opportunity:** The section doesn't explain why noise cancellation is hard in practice. It works well for low-frequency, steady sounds (airplane engines) but poorly for high-frequency or changing sounds (voices, traffic). The reason is that the phase relationship between the microphone and the speaker varies with distance, and the delay between measurement and cancellation is not negligible. This is a real-world constraint that makes the concept concrete. Also, the section doesn't connect interference to resonance, which is the broader application of this principle.

**For a Feynman writer:** Open with a practical puzzle: "Modern headphones can make an airplane cabin nearly silent. But the same headphones fail to cancel a person's voice. Why?" This motivates the study of wave interference without announcing "Today we learn about interference." The answer involves wavelength (long wavelengths like low-frequency engine noise are easier to cancel in confined spaces than short wavelengths like voice), phase lag (the microphone picks up noise, passes it to a processor, inverts it, and plays it back through a speaker; all this takes microseconds, which is a noticeable fraction of a period for high-frequency sounds), and spatial variation (the ideal cancellation point is at the microphone; other locations in the ear canal may have imperfect cancellation).

---

### Section 17.5 — Sources of Sound
**Core teaching:** Standing waves in tubes determine the resonant frequencies. A tube closed at one end resonates at $f_n = nv/(4L)$ for $n = 1, 3, 5, \ldots$ (odd harmonics only). A tube open at both ends resonates at $f_n = nv/(2L)$ for $n = 1, 2, 3, \ldots$ (all harmonics). The difference in harmonic content explains why a clarinet (closed at one end) and a flute (open at both ends) sound different even when playing the same fundamental frequency. Wind instruments vary the tube length (by opening/closing finger holes or sliding a tube) to change the fundamental frequency.

**What the text does well:** Clear derivation from boundary conditions. Diagrams showing the standing wave patterns in each case. Emphasis on the asymmetry between the two cases. Practical application to real instruments (clarinet, saxophone, flute, trombone, tuba).

**Missed opportunity:** The section doesn't deeply explore timbre — the harmonic content and its relationship to instrument shape. It mentions that a complex sounding box (piano, violin) has many resonances, but it doesn't explain how the resonances interact with the driving frequency. It also doesn't discuss the end correction, which is small but matters for precision tuning. And it doesn't explain temperature dependence of frequency: when a clarinet is taken from a cool room to a warm one, $v$ increases, so $f = v/(4L)$ increases, and the instrument plays sharp. This is a real practical issue musicians face.

**For a Feynman writer:** Open with a musical mystery: "A piano and a violin play the same note. Your ear says immediately that it's not the same sound. What's different?" The pitch (fundamental frequency) is the same. The loudness (intensity) might be similar. But the timbre is unmistakably different. This requires understanding that the overtones (multiples of the fundamental) have different relative intensities in each instrument. Then tie it to the standing wave patterns in the instrument's resonant structures. This makes the abstract concept of harmonics and overtones concrete and musically meaningful.

---

### Section 17.6 — Beat Frequency
**Core teaching:** When two slightly different frequencies interfere, they produce beats. If the two frequencies are $f_1$ and $f_2$, the beat frequency is $f_{\text{beat}} = |f_2 - f_1|$. Beats are used to tune musical instruments: as the beat frequency decreases, the two instruments are getting closer in frequency.

**What the text does well:** Clear derivation using trigonometric identities. Practical application to piano tuning.

**Missed opportunity:** The section is short and doesn't explore the physics deeply. Why does beating occur? Because when two waves are nearly in-phase, they reinforce (constructive interference) and the combined amplitude is large. When they are nearly out-of-phase, they cancel (destructive interference) and the combined amplitude is small. This creates a modulation in the combined waveform, with the modulation frequency equal to the frequency difference. This is the same interference principle as in section 17.4, just with nearly-equal rather than vastly-different frequencies. The section could connect beats to interference conceptually.

**For a Feynman writer:** Open: "Piano tuners listen for beats. As they tighten a string, the beats slow down and eventually stop. Why does a beat frequency tell you when two sounds match?" This grounds beats in a practical task (tuning) before explaining the math. The answer is that beats are the audible signature of two frequencies coming into phase alignment — the beat frequency is how fast that phase relationship cycles.

---

### Section 17.7 — Doppler Effect
**Core teaching:** When a source moves toward an observer, the observed frequency is higher: $f_o = f_s(v/(v - v_s))$. When a source moves away, the observed frequency is lower: $f_o = f_s(v/(v + v_s))$. When an observer moves toward a stationary source, $f_o = f_s(v + v_o)/v$. When moving away, $f_o = f_s(v - v_o)/v$. The general formula combining both motions is $f_o = f_s(v \pm v_o)/(v \mp v_s)$.

**What the text does well:** Clear derivation for each case from first principles (wavelength change due to source motion, frequency observation due to observer motion). Physical explanation: the source moving toward you bunches up the wavefronts, shortening the wavelength and raising the frequency. Practical applications: police radar, medical ultrasound (blood velocity), astronomical redshift (galaxy recession).

**Missed opportunity:** The section doesn't adequately explain the asymmetry between source and observer motion. This asymmetry is not a flaw; it's a feature. It tells us that the medium (air) defines a preferred reference frame. Motion relative to the medium matters. This insight prepares students for special relativity, where the speed of light plays the role of the wave speed, and the asymmetry between source and observer is even more striking (relativity fixes it, but that's a deeper story). Also, the section doesn't explore what happens at high speeds — the "What could this mean?" question when $v_s$ approaches or exceeds $v$.

**For a Feynman writer:** Open with an ambulance, because students hear it constantly: "An ambulance approaches, and the siren pitch drops as it passes. But the siren itself is emitting a constant frequency. What changes?" This is an everyday puzzle with a surprising answer: it's the wavelength that changes, not the frequency of the source. The observer sees a shorter wavelength when the source approaches (wavefronts bunched up), so the frequency increases. This is the physical mechanism, and it's more interesting than the formula.

---

### Section 17.8 — Shock Waves
**Core teaching:** When a source exceeds the speed of sound, it creates a shock wave — a cone of constructive interference trailing the object. The shock wave angle is determined by $\sin \theta = v/v_s = 1/M$ where $M = v_s/v$ is the Mach number. A sonic boom is the intense sound produced as the shock wave sweeps past an observer on the ground. The common misconception is that the sonic boom occurs once, when the aircraft "breaks the sound barrier." In fact, the boom is continuous as the aircraft flies supersonically.

**What the text does well:** Clear geometric derivation of the shock wave cone angle. Distinction between a shock wave (the pressure disturbance) and a sonic boom (the sound heard on the ground). Historical note on the SR-71 Blackbird Mach 2.85 record. Explanation of how pressures in a sonic boom can be destructive.

**Missed opportunity:** The section doesn't explore the bow wake concept broadly — the fact that shock waves occur whenever an object moves faster than waves can propagate in a medium. The example of a boat's V-shaped wake would help. The mention of Cerenkov radiation (a charged particle moving faster than light travels through a medium, emitting a cone of light) would prepare for later topics and show the universality of the principle. Also, the section doesn't discuss the physics of what happens *at* the shock wave — the pressure and temperature jump — which is where the destructiveness comes from.

**For a Feynman writer:** Open with Felix Baumgartner (which the source does not do, but which is irresistible): "In October 2012, a man jumped from 39 kilometers up and, as he fell, his body created a visible shock wave — a cone of compressed air around him. He had exceeded the speed of sound. Mach 1.25. What does it mean for an object to 'break the sound barrier,' and why does it create such a dramatic effect?" This is an extreme example, but it makes shock waves real and visible. From there, the student understands that shock waves are not exotic — they are the inevitable consequence of moving faster than waves can propagate.

---

## Ideas Harvest for a Textbook Author

### Opening Cold-Shots (Scene-Setting Moments)

1. **The Ambulance Siren (Most Accessible)** — Everyone has heard this. The siren drops pitch as it passes. This is the Doppler effect in real time, heard by the human ear. Opens the student to curiosity: "How can the pitch change if the siren is the same frequency?"

2. **Felix Baumgartner's Jump (Most Dramatic)** — October 14, 2012, visible shock wave. The jump exceeds Mach 1.25 at 37 km altitude. Connects sound physics to an extreme real-world event. Motivates the study of supersonic flow and shock waves.

3. **Piano Tuning (Most Practical)** — Piano tuners listen for beats and tune until the beats disappear. This is beat frequency in action. Shows that sound physics has a job: tuning musical instruments.

4. **Why You Can Hear Around a Corner (Most Conceptual)** — Sound diffracts around obstacles; light does not (or does, weakly). This is because sound wavelengths are large compared to everyday obstacle sizes. Opens to a deeper question: why are sound wavelengths so large compared to light? Answer: sound travels much slower in air than light travels in vacuum, and wavelength = speed / frequency.

5. **The Whisper Heard Across a Noisy Room (Most Intimate)** — Your friend whispers something, and you hear it despite the background noise. Why? Because your ear has evolved to detect a specific frequency band (around 1–5 kHz, where human speech lives) with exquisite sensitivity. This ties sound physics to biology and evolution.

### Specification Moves (Vague Terms Made Precise)

1. **"Sound" is not unique. It is one example of a wave.** Specification: Sound is a longitudinal pressure wave traveling through a medium at a speed determined by the medium's elastic modulus and density. Not all waves are sound; light is a wave but not sound. Sound is mechanical; light is electromagnetic.

2. **"Loudness" is not the same as "intensity."** Specification: Intensity is the physical quantity $I = P/A$ (W/m²). Loudness is the perception of intensity by the human ear. They are related by the Weber-Fechner law: perceived loudness $\propto \log(I)$. This is why we use the decibel scale.

3. **"Pitch" is not the same as "frequency."** Specification: Frequency is the physical quantity $f$ (Hz). Pitch is the perception of frequency by the human ear. For pure tones, pitch and frequency are closely linked, but they diverge for complex tones (where overtones shift the perceived pitch).

4. **"Music" is not a natural category; it is a cultural one.** Specification (narrow): A musical note is a sound of a specific frequency (e.g., A4 = 440 Hz). A musical chord is a combination of frequencies with small-integer ratios (e.g., a major triad is 1:1.26:1.5). But this is only true in Western music; other cultures have different interval systems.

5. **"Sonic boom" is not the sound of breaking the barrier; it is the sound of the shock wave.** Specification: A sonic boom is the intense sound produced as a shock wave sweeps past an observer. The shock wave itself is formed when an object exceeds the speed of sound. The boom is continuous, not instantaneous.

### Conceptual Levers (Principles That Do Heavy Lifting)

1. **The Wave Equation as Universal Principle** — The same equation $\partial^2 u / \partial t^2 = v^2 \partial^2 u / \partial x^2$ governs sound, light, waves on strings, seismic waves, quantum wave functions, gravitational waves. What differs is what oscillates ($u$) and what the wave speed depends on. This is the deepest principle in the chapter.

2. **Elastic Property vs. Inertial Property** — All wave speeds follow $v = \sqrt{\text{elastic property} / \text{inertial property}}$. In sound: $v = \sqrt{B/\rho}$. In light: $v = \sqrt{1/(\mu_0 \epsilon_0)}$ (the permittivity and permeability of the medium replace bulk modulus and density). This pattern recurs throughout physics.

3. **Boundary Conditions Determine Resonances** — A tube closed at one end has different resonances than a tube open at both ends because the boundary conditions are different. This principle extends to quantum wells, resonant cavities for lasers, and more. The shape of the container constrains what waves can "fit" inside.

4. **Logarithmic Perception** — The human ear responds logarithmically to intensity. This is not unique to hearing; vision, smell, and touch all respond logarithmically. This is an evolutionary principle: organisms need to detect signals across many orders of magnitude. The decibel scale is a mathematical expression of this biological fact.

5. **The Medium Sets the Reference Frame** — The Doppler effect is asymmetric between source motion and observer motion because the medium (air) defines a preferred reference frame. Motion relative to the medium matters. This is a precursor to understanding special relativity, where there is no preferred frame and the asymmetry is resolved.

### Trade-Offs Worth Naming

1. **Linear Acoustics vs. Nonlinear Acoustics** — The formulas we use assume that pressure amplitudes are small compared to ambient pressure. This assumption breaks down at very high intensities (near shock waves), where new physics emerges (shock formation, steepening of waveforms). A chapter on sound can stay in the linear regime without mentioning this, but a complete understanding requires knowing the limit.

2. **Point Sources vs. Extended Sources** — The inverse square law assumes the sound comes from a point. Real speakers, instruments, and the human voice are extended sources. This affects the intensity pattern and the definition of the intensity level scale.

3. **Free Field vs. Enclosed Spaces** — The speed of sound is the same in open air and in a concert hall, but the intensity distribution and the perceived timbre differ dramatically due to reflections and resonances in the hall. A chapter focused on sound fundamentals can ignore room acoustics, but real musical experience is shaped by it.

4. **Frequency Dependence** — Most of the chapter treats sound speed as independent of frequency. This is true in most practical scenarios but fails at extreme frequencies (ultrasound) and in certain media (dispersive media like some solids). Knowing when an assumption is valid is part of expert reasoning.

### Gaps and Tensions in the Source

1. **Timbre is mentioned but not fully explained.** The source says that the mix of overtones determines timbre, but doesn't explore how the instrument's resonances and the player's control of amplitude produce different harmonic mixes. A deeper treatment would show how a violinist's technique (how they excite the string and how they use the bow) shapes the harmonic content.

2. **The relationship between standing waves and timbre is implicit.** A tube closed at one end has only odd harmonics (by geometry), so a clarinet naturally emphasizes odd harmonics. But how does this relate to the listener's perception of "woodiness" or "brightness"? This requires some perceptual psychology, which is outside the scope of a physics chapter, but the connection is worth noting.

3. **Temperature effects on instrument tuning are real but treated lightly.** The formula $v = 331 \sqrt{T_K/273}$ shows that sound speed increases with temperature. For a musician, this means an instrument played in a warm room plays sharp and in a cold room plays flat. This is a real effect that professionals manage constantly. The chapter could deepen this by working through a specific example.

4. **The Doppler effect at high speeds is glossed over.** The formula $f_o = f_s(v/(v - v_s))$ predicts infinite frequency as $v_s \to v$ and negative frequency for $v_s > v$. These are signs that the physics changes fundamentally at supersonic speeds. The chapter acknowledges shock waves but doesn't deeply explore the transition.

### Adjacent Concepts Worth Exploring Elsewhere

1. **Acoustical impedance $Z = \rho v$:** Determines how much sound is reflected vs. transmitted at a boundary between two media. A key concept for understanding ultrasound in medical imaging.

2. **Acoustic resonance in enclosed spaces:** Concert halls, car interiors, musical instruments. How the shape and materials of a space affect the frequencies that are amplified or damped.

3. **Bioacoustics:** How animals (bats, dolphins, birds, insects) use sound for communication and echolocation. An applications area that shows how the physics of sound enables biology.

4. **Fourier analysis:** The decomposition of complex sounds into sinusoidal components (harmonics). Essential for understanding timbre but typically presented in a math course.

5. **Psychoacoustics:** How the human brain interprets sound. Pitch perception, loudness perception, spatial localization. The bridge between physics and neuroscience.

---

## Attenborough × Feynman Voice Specific Notes

**Attenborough element (narrative, scene, wonder):**
- Ground the Doppler effect in the ambulance siren, something the student has actually heard.
- Use Felix Baumgartner's jump as a moment of awe — a human body creating a visible shock wave.
- Describe the piano tuner listening to beats as an artisan at work, using physics as a tool.

**Feynman element (clarity, first principles, playful):**
- Explain why sound is faster in water than air by reference to elastic modulus and density, not by rote.
- Derive the shock wave cone angle from geometry, not from memorizing a formula.
- Challenge the student's intuition early ("A heavier gas should slow sound down, right? Wrong.").
- Admit the limits of the linear approximation and sketch what happens beyond it.

**Closure element (book's ending):**
- This is the final chapter. The student has learned mechanics from units through sound. The wave equation unifies all of it. Sound is the bridge to the next course (E&M, optics, quantum).
- The opening with Baumgartner, the deepening with Doppler, the payoff with shock waves — all show how a single principle (the wave equation) governs phenomena from everyday to extreme.
- End on a note of wonder: "In your next course, you will learn that light is also a wave. The same Doppler formula, the same interference patterns, the same resonances — all will reappear. The machinery does not change. Only the substance that oscillates."

---

## Recommended Primary Sources for Verification

1. **OpenStax University Physics, Vol. 1** — Chapter 17 (source for this chapter); provides derivations, formulas, worked examples, and problems.
2. **Kinsler et al., *Fundamentals of Acoustics*** — Advanced treatment; derives speed of sound from first principles.
3. **NIST Reference on Physical Constants** — Verified values for sound speed in various media.
4. **ISO 226:2003** — Standard equal-loudness contours and phon scale.
5. **Felix Baumgartner Red Bull Stratos** — Official video and data; documented Mach 1.25 at 37 km altitude.
6. **SR-71 Blackbird Speed Record** — July 28, 1976; Mach 2.85; confirmed in aviation history sources.

---

## Opportunities for Extension (Toward Interdisciplinarity)

- **Medicine:** Ultrasound imaging uses the same physics of sound and resonance. Doppler ultrasound measures blood flow.
- **Geology:** Seismic P-waves and S-waves are sound waves in rock. Used to map Earth's interior.
- **Astronomy:** Redshift of distant galaxies due to Doppler effect. A key piece of evidence for cosmic expansion.
- **Neuroscience:** The human ear converts sound into electrical signals. The cochlea performs a Fourier transform (decomposes complex sounds into frequencies).
- **Music:** The construction of instruments, tuning systems, harmonic series, and psychoacoustics.
- **Engineering:** Noise reduction, acoustic design of buildings, sonar and radar (both use wave principles).

Any of these could be woven into a deeper chapter if scope permits.
