# Figures and visual references — Units and Measurement

**For chapter illustrations, diagrams, and visual teaching aids.**

---

## Figures referenced in the chapter

### Figure 1: Mars Climate Orbiter trajectory mismatch

**[FIGURE: Two trajectories overlaid on a schematic of Mars. One (correct, dashed line) shows the spacecraft entering the Martian atmosphere at a shallow angle and settling into orbit. The other (actual, solid line) shows the spacecraft entering at a steeper angle and burning up in the atmosphere. The difference is labeled as ~111 km (60 nautical miles). A callout box reads: "Unit mismatch: SM_FORCES outputs in lbf·s; navigation software expects N·s. Conversion factor: multiply by 4.448."]**

What students should notice:
- The spacecraft is on a slightly different path throughout the 9-month journey, not just at the end.
- Small errors in trajectory accumulate over long distances.
- The error is not in the physics — the equations are correct — but in the units.
- A single multiplication by a conversion factor would have prevented the disaster.

---

### Figure 2: Evolution of the meter's definition

**[FIGURE: Timeline showing four definitions of the meter:
1. (1791) 1/10,000,000 of the distance from equator to North Pole — illustrated with a globe and a distance arc.
2. (1889) Distance between two engraved lines on a platinum-iridium bar — illustrated with a bar in a vault.
3. (1960) 1,650,763.73 wavelengths of orange light from krypton-86 — illustrated with a laser or light source emitting orange light, with wavelengths marked.
4. (1983) Distance light travels in 1/299,792,458 of a second — illustrated with light traveling along a ruler, a clock showing the time interval, and the equation: distance = speed × time.
Each definition is labeled with its source and the reason for the change below it.]**

What students should notice:
- Each redefinition increased precision and reproducibility.
- The trend is from macroscopic (polar arc) to microscopic (atomic) to fundamental (light speed).
- Later definitions are more universal (you can reproduce a light wavelength or the speed of light anywhere, not just in Paris).
- The current definition ties length to a fundamental constant of nature.

---

### Figure 3: The Grand K and uncertainty over time

**[FIGURE: A line graph showing the mass of the International Prototype Kilogram (Grand K) in micrograms relative to its initial definition, plotted from 1889 to 2018. The y-axis ranges from 0 to −50 μg. The line shows a gradual, irregular decline, with occasional flat sections (when the Grand K was stored in the vault and not measured) and steeper declines in years after comparisons (when contamination or loss was discovered). The graph ends at −50 μg in 2018. A shaded region around the line represents measurement uncertainty. A callout box reads: "The definition of the kilogram was *drifting*. By 2019, this was unacceptable."]**

What students should notice:
- The drift is small in absolute terms (50 μg is nothing) but large relative to the definition (it is the definition).
- The drift is irregular, not smoothly linear, suggesting multiple causes.
- Uncertainty increases with each comparison because you cannot know exactly what the composition or structure of the cylinder changed.
- This scenario — where a physical standard drifts — is one reason physicists prefer to define units by immutable constants.

---

### Figure 4: The seven SI base units and their definitions (post-2019)

**[FIGURE: A circular diagram or table showing each of the seven base units with their symbols and defining constants:
- **Length (meter, m):** Defined by the speed of light in vacuum: exactly 299,792,458 m/s. Illustration: light traveling along a scale.
- **Mass (kilogram, kg):** Defined by Planck's constant: exactly 6.62607015 × 10^−34 J·s. Illustration: a Kibble balance with a weight on one side and a coil in a magnetic field on the other.
- **Time (second, s):** Defined by the cesium-133 atomic oscillation frequency: exactly 9,192,631,770 Hz. Illustration: a cesium atom oscillating, with tick marks representing 9 billion cycles.
- **Temperature (kelvin, K):** Defined by the Boltzmann constant: exactly 1.380649 × 10^−23 J/K. Illustration: a thermometer or atoms in motion.
- **Electrical current (ampere, A):** Defined by the elementary charge: exactly 1.602176634 × 10^−19 C. Illustration: electrons flowing through a wire.
- **Amount of substance (mole, mol):** Defined by Avogadro's number: exactly 6.02214076 × 10^23. Illustration: a collection of atoms or molecules.
- **Luminous intensity (candela, cd):** Defined by the luminous efficacy of monochromatic radiation at a specific frequency. Illustration: a light source emitting light of a specific wavelength.
All definitions are labeled "Before 2019: physical artifact" or "Post-2019: fundamental constant."]**

What students should notice:
- Each definition uses a constant of nature, not a physical object.
- The constants are written to full precision, reflecting their now-exact values.
- The constants span an enormous range of scales (Planck's constant is tiny; Avogadro's number is huge).
- All seven units are now defined at the quantum or fundamental level, reflecting modern physics.

---

### Figure 5: Dimensional consistency check — two formulas for a circle

**[FIGURE: Two side-by-side analyses.
**Left: Circumference formula, $C = 2\pi r$**
- Illustration: a circle with radius $r$ marked.
- Dimensional analysis:
  - $[C] = L$ (circumference is a length)
  - $[2\pi r] = 1 \times L = L$ (pure number times length is length)
  - Conclusion: Dimensions match. This *could be* the circumference.

**Right: Area formula, $A = \pi r^2$**
- Illustration: the same circle, with the area shaded.
- Dimensional analysis:
  - $[A] = L^2$ (area is length squared)
  - $[\pi r^2] = 1 \times L^2 = L^2$ (pure number times length squared is length squared)
  - Conclusion: Dimensions match. This *could be* the area.

Both analyses are labeled with checkmarks, indicating both pass the dimensional consistency test. A callout reads: "Dimensional analysis tells you which formula *could* be correct, not which one *is* correct. To know for sure, you need to memorize or derive it."]**

What students should notice:
- Dimensions are built from the seven base dimensions (length, mass, time, etc.).
- Algebraic operations on dimensions follow the same rules as algebraic operations on numbers.
- A formula can pass the dimensional test and still be wrong (e.g., if you forgot a factor of π).
- Dimensional consistency is a necessary but not sufficient condition.

---

### Figure 6: Accuracy vs. precision — Target diagrams

**[FIGURE: Four circles arranged in a 2×2 grid, each representing a bull's-eye target. Each circle has the true value marked at the center (a red dot or bulls-eye), and a cluster of black dots representing repeated measurements.

**Top-left (High accuracy, high precision):** The black dots cluster tightly around the center. Caption: "High accuracy, high precision. Measurements cluster near the true value."

**Top-right (Low accuracy, high precision):** The black dots cluster tightly in one corner, far from the center. Caption: "Low accuracy, high precision. Measurements cluster together but far from the true value (e.g., a broken thermometer that is consistently off)."

**Bottom-left (High accuracy, low precision):** The black dots are scattered throughout the target, with no tight clustering, but they average to near the center. Caption: "High accuracy, low precision. Measurements scatter widely but average to the true value."

**Bottom-right (Low accuracy, low precision):** The black dots are scattered throughout the target, far from the center and with no tight clustering. Caption: "Low accuracy, low precision. Measurements scatter widely and average far from the true value (worst case)."]**

What students should notice:
- Accuracy and precision are independent.
- A systematic error (like a thermometer that is always 5° off) gives low accuracy but can still have high precision.
- Random errors (like variations in how you read a ruler) give low precision but can still be accurate on average.
- The best situation is high accuracy and high precision.

---

### Figure 7: Significant figures in measurement

**[FIGURE: A ruler (or scale) showing a pencil or object positioned on it. The ruler has fine markings (e.g., millimeter marks) and larger markings (e.g., centimeter marks).
- A measurement line with arrow endpoints shows the object spans from approximately 3.2 cm to 8.7 cm.
- The length is marked as "approximately 5.5 cm," but the exact value depends on how you read the ruler.
- Below the ruler: "With this ruler (1 mm divisions), the length is 5.5 ± 0.1 cm. This is 2 significant figures. If the ruler had 0.1 mm divisions, you might report 5.50 cm (3 sig figs). Significant figures reflect your precision."
- A callout illustrates the concept: "Reporting 5.527 cm (4 sig figs) would be false precision — your ruler cannot distinguish to that level. Report 5.5 cm (2 sig figs) instead."]**

What students should notice:
- Significant figures depend on the precision of your measuring instrument.
- Trailing zeros in a measurement are significant (5.50 indicates precision to the hundredths place; 5.5 indicates precision to the tenths place).
- Leading zeros are not significant (0.0055 has 2 sig figs, not 4).
- Scientific notation removes ambiguity (5.5 × 10^0 has 2 sig figs; 5.50 × 10^0 has 3 sig figs).

---

### Figure 8: Order-of-magnitude scales — Powers of 10

**[FIGURE: A logarithmic scale (vertical axis, powers of 10 from 10^−44 to 10^26) showing lengths, times, and masses across the universe.

**Length scale (left column):**
- 10^−35 m: Planck length
- 10^−15 m: nucleus
- 10^−10 m: atom
- 10^−6 m: cell
- 10^0 m: human
- 10^6 m: Earth radius
- 10^11 m: Earth-Sun distance
- 10^26 m: observable universe

**Time scale (middle column):**
- 10^−44 s: Planck time
- 10^−21 s: nuclear oscillation
- 10^−10 s: cesium oscillation
- 10^0 s: human timescale
- 10^9 s: human lifetime
- 10^17 s: age of Earth

**Mass scale (right column):**
- 10^−30 kg: electron
- 10^−27 kg: proton
- 10^0 kg: human
- 10^24 kg: Earth
- 10^30 kg: Sun

Vertical alignment shows which scales are relevant to each other. A callout notes: "SI units and metric prefixes handle all of these with a single base unit."**

What students should notice:
- The range of scales in the universe is enormous — from 10^−44 to 10^26, a span of 70 orders of magnitude.
- A single unit system (SI) describes all of these scales with simple prefixes.
- Order-of-magnitude thinking allows you to estimate quantities quickly (e.g., "a human is about 10^0 meters" rather than "exactly 1.73 meters").

---

## Visual reference notes

### Color scheme recommendation for instructors

- **SI base units:** Use a consistent color (e.g., dark blue) to highlight the seven base units whenever they appear.
- **Derived units:** Use a contrasting color (e.g., green) for quantities derived from base units (force, energy, power).
- **Conversion factors:** Use a third color (e.g., orange) to highlight the numbers and ratios used in unit conversions.
- **Uncertainty regions:** Use a light shade (e.g., light gray or pale color) to represent ranges of uncertainty, not sharp values.

### Figures recommended but not yet drafted

1. **The Kibble balance schematic:** A detailed diagram showing a weight on one side of a balance and a coil in a magnetic field on the other, with electrical current flowing through the coil. Labels for magnetic field, coil, current, weight, balance beam.

2. **Cesium-133 energy level diagram:** An atomic physics diagram showing the ground state splitting into two hyperfine levels, with the transition frequency (9,192,631,770 Hz) marked. Illustration of a clock-like apparatus counting the oscillations.

3. **Dimensional analysis flowchart:** A decision tree for checking dimensional consistency:
   - Start with an equation.
   - Identify dimensions of each term.
   - Do all terms on the left have the same dimension?
   - Do all terms on the right have the same dimension?
   - Do left and right have the same dimension?
   - If yes to all: dimensionally consistent. If no to any: equation is wrong.

4. **Metric prefix table (visual):** A horizontal strip showing prefixes from yocto- (10^−24) to yotta- (10^24), with visual representations of scale (e.g., sizes of objects at each scale).

