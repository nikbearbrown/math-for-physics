# Fact-Check: Algebra and Equations in Physics

- **Date:** 2026-05-30
- **Source file:** `chapters/02-algebra-and-equations-in-physics.md`
- **Assertions flagged:** 5
- **Breakdown by category:** EVIDENCE/SPECIALIST (historical attributions + PER findings): 4 · AI-ONLY (on-page derivations): 1

## ⚠️ Critical — Requires Immediate Expert Review

None found. (No OUTDATED, CONTRADICTED, or COMBINATION findings.)

## Full Findings

### Finding 1 — "algebra" from al-jabr (al-Khwārizmī, c. 820)

- **Category — Verdict:** EVIDENCE/SPECIALIST — CONFIRMED
- **Assertion type:** POSITIVE (etymology + named-work attribution)
- **Sentence:** "The word *algebra* itself comes from the Arabic *al-jabr* — 'restoring' or 'balancing' — from al-Khwarizmi's ninth-century treatise." (also "al-Khwarizmi's *al-jabr* — balancing — made into a rule," and the Sources entry dating the treatise c. 820)
- **Claim checked:** "algebra" derives from *al-jabr*; the term means restoration/completion; from al-Khwārizmī's treatise written c. 820 (9th century).
- **Site visited:** Wikipedia "Al-Jabr" and "Muhammad ibn Musa al-Khwarizmi"; Britannica "The Compendious Book on Calculation by Completion and Balancing," via WebSearch.
- **Finding:** Confirmed. *Al-Kitāb al-mukhtaṣar fī ḥisāb al-jabr wa-l-muqābala* was written in Baghdad c. 813–833 (commonly c. 820). "Algebra" descends from *al-jabr*. Minor nuance: strictly, *al-jabr* = "restoration/completion" (transposing subtracted terms across the equation) and *al-muqābala* = "reduction/balancing" (cancelling like terms). The chapter glosses *al-jabr* as "'restoring' or 'balancing'," lightly conflating the two paired operations — but "balancing" is a fair informal reading and the balance metaphor the chapter builds on is sound.
- **Expert review needed:** No.
- **Suggested reference:** MacTutor biography of al-Khwārizmī; Britannica entry on the treatise. Already in Sources.
- **Notes:** Consider, optionally, attributing "balancing" to *muqābala* for precision — but this is a refinement, not a correction.

### Finding 2 — Symbolic-vs-numeric PER finding (Torigoe & Gladding)

- **Category — Verdict:** SPECIALIST — CONFIRMED (research finding); citation precision PARTIAL
- **Assertion type:** EMPHATIC (the framing research claim)
- **Sentence:** "intro-physics students reliably do *worse* on the symbolic version of a problem than on a numerically identical one." (Sources cite Torigoe & Gladding, "Symbols are not numbers" / "How numbers help students solve physics problems," 2011, both `[verify]`)
- **Claim checked:** That students score worse on symbolic than on numerically identical problems, per Torigoe & Gladding.
- **Site visited:** ResearchGate / AIP Conference Proceedings 951, 200 (2007) "Symbols: Weapons of Math Destruction"; Quantum Progress blog summary, via WebSearch.
- **Finding:** The substantive finding is CONFIRMED: Torigoe & Gladding gave parallel numeric and symbolic exam questions and found mean scores on numeric questions substantially higher (~50% higher in the initial study) than matching symbolic ones, attributing the gap to misunderstanding of variables rather than calculation skill. The exact citation is slightly imprecise: their key papers are 2006, 2007 (AIP Conf. Proc. 951, 200, "Symbols: Weapons of Math Destruction"), and later work ~2011. The chapter's title "Symbols are not numbers" is a paraphrase, not the exact published title.
- **Expert review needed:** No (finding solid); optional citation tidy.
- **Suggested reference:** E. T. Torigoe & G. E. Gladding, "Symbols: Weapons of Math Destruction," *AIP Conf. Proc.* 951, 200 (2007); E. T. Torigoe, "How numbers help students solve physics problems" (PhD work / 2011). Recommend appending the 2007 AIP citation.
- **Notes:** The `[verify]` flags should be resolved as "finding confirmed, exact title/year of one cited paper imprecise."

### Finding 3 — Galileo's square–cube law (Two New Sciences, 1638)

- **Category — Verdict:** EVIDENCE — CONFIRMED
- **Assertion type:** POSITIVE (named-work attribution + argument)
- **Sentence:** "Galileo (*Two New Sciences*, 1638) asked why nature cannot build a giant simply by scaling an animal up uniformly. … area $\propto L^2$, volume $\propto L^3$ … stress $\propto L$ … This is *why* an elephant cannot have a gazelle's slender legs."
- **Claim checked:** Galileo articulated the square–cube scaling of bone strength vs weight in *Dialogues Concerning Two New Sciences* (1638).
- **Site visited:** Wikipedia "Square–cube law"; Grokipedia square–cube entry; UVA Galileo lecture notes, via WebSearch.
- **Finding:** Confirmed. *Two New Sciences* (1638) presents the square–cube argument: on the Second Day, Galileo argues bone strength scales with cross-sectional area (∝ L²) while weight scales with volume (∝ L³), so larger animals need disproportionately thicker bones — exactly the chapter's three-line proportionality argument. The Peterson (2002) AJP source on Galileo's discovery is also confirmed (see Finding 5).
- **Expert review needed:** No.
- **Suggested reference:** Galileo, *Dialogues Concerning Two New Sciences* (1638). Already in Sources.
- **Notes:** —

### Finding 4 — Atwood, incline, equilibrium, spring-scaling derivations (on-page)

- **Category — Verdict:** AI-ONLY — CONFIRMED
- **Assertion type:** Derivation / self-evident algebra
- **Sentence:** Atwood result $a=(m_2-m_1)g/(m_1+m_2)$ and its two limits + units check; $v^2=v_0^2+2as \Rightarrow a=(v^2-v_0^2)/2s$; incline $a=g(\sin\theta-\mu\cos\theta)$ and slip condition $\tan\theta>\mu$; spring scaling $T(4m)=2T(m)$; two-string equilibrium $T_1=w/(\cos\theta_1+\sin\theta_1\cot\theta_2)$; recipe scaling 600×1.5=900 g.
- **Claim checked:** The on-page algebra.
- **Site visited:** None (AI-VERIFIABLE).
- **Finding:** All correct. Atwood: adding the two Newton equations cancels T and yields the boxed result; m₁=m₂ ⇒ a=0; m₁→0 ⇒ a→g; numerator force / denominator mass = LT⁻² ✓; and the "always < g" reading (m₂−m₁ < m₁+m₂) is valid. Incline: dividing by m gives a=g(sinθ−μcosθ), slip when sinθ>μcosθ ⇔ tanθ>μ ✓. Spring: T∝√m ⇒ ×4 mass ⇒ ×2 period ✓. Equilibrium: substitution from T₁sinθ₁=T₂sinθ₂ into the vertical balance yields the stated T₁ ✓ (with cot θ₂ = cosθ₂/sinθ₂). Recipe: 6/4=1.5, 600×1.5=900 ✓.
- **Expert review needed:** No.
- **Suggested reference:** —
- **Notes:** Internally consistent; the worked sample value a=2.45 m/s² for m₁=3, m₂=5 is correct: (2)(9.8)/8 = 2.45.

### Finding 5 — Peterson, "Galileo's Discovery of Scaling Laws," AJP 70, 575 (2002)

- **Category — Verdict:** EVIDENCE — CONFIRMED
- **Assertion type:** Citation (Sources list), flagged `[verify]`
- **Sentence:** Sources: "M. A. Peterson, 'Galileo's Discovery of Scaling Laws,' *American Journal of Physics* 70, 575 (2002)."
- **Claim checked:** Author, title, journal, volume 70, page 575, year 2002.
- **Site visited:** NASA ADS (2002AmJPh..70..575P); arXiv physics/0110031, via WebSearch.
- **Finding:** Confirmed exactly. Mark A. Peterson (Mount Holyoke), *Am. J. Phys.* 70(6), 575 (2002). The `[verify]` can be resolved.
- **Expert review needed:** No.
- **Suggested reference:** As cited. Already in Sources.
- **Notes:** —

## Unverified Assertions

None. (Tourniaire & Pulos 1985 and D'Arcy Thompson 1917 are standard, uncontested bibliographic references not requiring a web visit; the "additive bug is the single most documented error in proportional reasoning" is a literature characterization supported by the Tourniaire & Pulos review and is reasonable, not flagged.)

## AI-Pass Flags (internal consistency / math)

- No math or internal-consistency errors found.
- The `[contested — see pantry]` marker (numbers-scaffold-meaning vs symbol-first pedagogy) is a genuine open debate, correctly labeled — no action.
