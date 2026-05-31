# Fact-check: 05 — Functions, Graphs, and Power Laws

**Field:** mathematics / physics
**Source file:** chapters/05-functions-graphs-and-power-laws.md
**Date checked:** 2026-05-30

## Breakdown

- Assertions classified and checked: 11 (6 historical/attribution EVIDENCE-SPECIALIST; 1 live-science SPECIALIST; 4 AI-verifiable derivations)
- CONFIRMED: 7 (web) + 4 (AI-pass) = 11
- OUTDATED: 0
- CONTRADICTED: 0
- UNVERIFIED: 0
- Live-science / contested flags carried in-text (correctly): 1 (metabolic scaling 3/4 exponent)

## ⚠️ Critical — Requires Immediate Expert Review

None found.

## Full Findings

1. **Galileo's time-squared law of free fall (1638, *Two New Sciences*).** "distance fallen is proportional to the square of the elapsed time." — CONFIRMED. *Discorsi e dimostrazioni matematiche intorno a due nuove scienze* (1638), Third Day, Theorem II/Proposition II: "the spaces described by a body falling from rest ... are to each other as the squares of the time-intervals." https://en.wikipedia.org/wiki/Two_New_Sciences

2. **Descartes, *La Géométrie* (1637), coordinate graph pairing algebra with geometry.** — CONFIRMED. Published 1637 as an appendix to *Discours de la méthode*; first to unite algebra and geometry into analytic geometry. https://en.wikipedia.org/wiki/La_G%C3%A9om%C3%A9trie ; https://www.britannica.com/topic/La-Geometrie

3. **Huxley, *Problems of Relative Growth* (1932): a power law y = ax^b is a straight log–log line of slope b (allometry).** — CONFIRMED. Huxley (1932) introduced the method of fitting power equations Y = bX^k by linearizing via logarithms; double-log plot gives a straight line of slope k. https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2687774/ ; https://journals.biologists.com/jeb/article/215/4/569

4. **Huxley & Teissier, "Terminology of relative growth," *Nature* 137 (1936): 780–781.** — CONFIRMED, including spelling "Teissier" and the exact citation. https://www.nature.com/articles/137780b0 ; https://www.oalib.com/references/8510992

5. **Max Kleiber, "Body size and metabolism," *Hilgardia* 6 (1932): measured metabolic-rate-vs-mass slope ≈ 0.75, suggesting B ∝ M^(3/4).** — CONFIRMED. Kleiber (1932) found a close-to-3/4 exponent rather than the 2/3 predicted by Rubner's surface law. (Note: chapter cites pages 315–353; the standard citation is *Hilgardia* 6:315–353; one secondary index lists 315–351 — page-range variance is trivial and the volume/year/title are correct.) https://en.wikipedia.org/wiki/Kleiber%27s_law ; https://scirp.org/reference/referencespapers?referenceid=776054

6. **West, Brown & Enquist, *Science* 276 (1997): 122–126 — fractal nutrient-distribution networks force 3/4; critics argue the exponent is not universal.** — CONFIRMED, and the chapter's "[contested — see pantry]" characterization is accurate. The WBE model derives 3/4 from space-filling fractal branching networks; it remains the leading but vigorously contested explanation (Kozłowski & Konarzewski; Banavar et al.; Dodds et al.). The claim that 2/3 is "a naive surface-area argument" is also correct (Rubner's law). https://www.science.org/doi/10.1126/science.276.5309.122 ; https://besjournals.onlinelibrary.wiley.com/doi/full/10.1111/j.0269-8463.2004.00830.x ; https://pmc.ncbi.nlm.nih.gov/articles/PMC2518954/

7. **Kepler's third law as a power law, T² ∝ r³, exponent 3/2.** — CONFIRMED (standard; T² ∝ r³ ⇒ T ∝ r^(3/2)). AI-verifiable.

## Unverified Assertions

| Assertion | Category | Why unverified | Suggested source |
|---|---|---|---|
| (none) | — | — | — |

## AI-Pass Flags

All on-page derivations verified correct, no web needed:

- **Free-fall power-law table & slope (Example 1):** d = 4.9t²; at t=1, log₁₀d = log₁₀4.9 = 0.690 ✓; at t=100, d=49,000, log=4.690 ✓; slope = (4.690−0.690)/2.000 = 2.00 ✓; intercept log a = 0.690 = log₁₀4.9 recovers a = 4.9. CONFIRMED.
- **Power-law scale-invariance:** a(cx)^b = a·c^b·x^b = c^b·(ax^b). CONFIRMED.
- **Stopping distance (Example 2):** from v² = v₀² − 2ad, at v=0, d = v₀²/(2a); exponent 2 in v₀; doubling speed quadruples distance. CONFIRMED.
- **Log–log straightening of y = ax^b:** log y = log a + b log x ⇒ Y = bX + log a, slope b, intercept log a; semi-log for y = ab^x gives log y = log a + (log b)x, slope log b. CONFIRMED.

Education-research citations (Sfard 1991 *ESM* 22:1–36; Carlson et al. 2002 *JRME* 33:352–378) are standard, correctly cited references in mathematics-education literature (treated as context; not the flagged live/contested items).
