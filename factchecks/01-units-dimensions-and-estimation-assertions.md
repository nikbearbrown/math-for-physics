# Fact-Check: Units, Dimensions, and Estimation

- **Date:** 2026-05-30
- **Source file:** `chapters/01-units-dimensions-and-estimation.md`
- **Assertions flagged:** 5
- **Breakdown by category:** EVIDENCE/SPECIALIST (historical attributions): 3 · STAT/CURRENT (units, external figures): 2

## ⚠️ Critical — Requires Immediate Expert Review

None found. (No OUTDATED, CONTRADICTED, or COMBINATION findings. One Fermi-figure assertion is UNVERIFIED but already self-flagged and correctly hedged in the prose.)

## Full Findings

### Finding 1 — Buckingham Π-theorem (1914) and its priority (Bertrand 1878, Vaschy 1892)

- **Category — Verdict:** EVIDENCE/SPECIALIST — CONFIRMED
- **Assertion type:** EMPHATIC/POSITIVE (named result + provenance claim)
- **Sentence:** "the '$\Pi$-theorem' is named for Buckingham (1914), but Joseph Bertrand proved special cases in 1878 and Aimé Vaschy gave a general statement in 1892. The result is named for the popularizer, not the originator." (also the statement at line 50, flagged `[verify — Buckingham 1914]`, and the Sources entry)
- **Claim checked:** Buckingham's landmark paper is 1914; Bertrand proved special cases in 1878; Vaschy gave a general statement in 1892; the theorem is named for the populariser rather than the originator.
- **Site visited:** Wikipedia "Buckingham π theorem" (history section) and NIST "The Life of (Buckingham) Pi" (nist.gov/blogs/taking-measure/life-buckingham-pi), via WebSearch.
- **Finding:** Confirmed in full. Bertrand (1878) treated special cases of electrodynamics/heat-conduction problems but contained all the basic ideas; Vaschy (1892) gave the first formal generalization; Federman and Riabouchinsky restated it independently in 1911; Buckingham's 1914 *Physical Review* paper became the landmark reference and gave the theorem its popular name. Some sources call it the "Vaschy–Buckingham theorem." Buckingham's *Phys. Rev.* 4, 345 (1914) citation matches standard references.
- **Expert review needed:** No.
- **Suggested reference:** NIST, "The Life of (Buckingham) Pi"; Wikipedia "Buckingham π theorem." Both already reflected in the chapter's Sources.
- **Notes:** The chapter's provenance lesson is accurate. `[verify — Buckingham 1914]` and the Sources `[verify]` on Vaschy/Bertrand can be considered resolved.

### Finding 2 — Mars Climate Orbiter units failure (1999, $327M, lbf/N)

- **Category — Verdict:** EVIDENCE/STAT — CONFIRMED
- **Assertion type:** POSITIVE (historical/factual account, cold open + return)
- **Sentence:** "On 23 September 1999 … the Mars Climate Orbiter fired its engine … broke apart. The mission cost roughly $327 million. … One program … reported the small thruster impulses in *pound-force-seconds*. The navigation software at the Jet Propulsion Laboratory read those numbers as *newton-seconds*. A pound-force is about 4.45 newtons …"
- **Claim checked:** Date 23 Sept 1999; ~$327M mission cost; impulse-unit mismatch between pound-force (US customary) and newton (SI); 1 lbf ≈ 4.45 N.
- **Site visited:** Wikipedia "Mars Climate Orbiter"; NASA Science mission page; Everyday Astronaut (corroborating $327M), via WebSearch.
- **Finding:** Confirmed. Communication lost 23 Sept 1999 on orbital insertion; failure attributed to a unit mismatch — Lockheed Martin software output thruster force/impulse in US customary (pound-force) units, JPL navigation software assumed SI (newtons). Cost widely reported at $327 million. The conversion 1 lbf = 4.448222 N (≈ 4.45 N) is a standard exact-definition-based physical constant (AI-VERIFIABLE, CONFIRMED — no web needed). The chapter's nuance — that both units share the same dimension $MLT^{-1}$, so a pure dimensional check would NOT have caught it — is correct.
- **Expert review needed:** No.
- **Suggested reference:** NASA, *Mars Climate Orbiter Mishap Investigation Board Phase I Report* (1999) — already in Sources.
- **Notes:** One source phrased the misread unit as "newtons per square meter," but the authoritative framing (impulse / force in N vs lbf) matches the chapter. No correction needed.

### Finding 3 — Buckingham Π / linear-algebra and uncertainty-propagation derivations

- **Category — Verdict:** AI-ONLY — CONFIRMED
- **Assertion type:** Derivation / self-evident algebra (not flagged as classification target; recorded for completeness)
- **Sentence:** Pendulum dimensional derivation ($T_p = C\sqrt{\ell/g}$); uncertainty-propagation rule via $\ln q = m\ln A + n\ln B \Rightarrow dq/q = m\,dA/A + n\,dB/B$; Example 1 density conversion (2.7 g/cm³ → 2700 kg/m³); Example 2 sphere volume (5.8% relative uncertainty, $V=73.6\pm4.3$ cm³); Example 3 molecules-in-a-room (~$10^{27}$).
- **Claim checked:** The on-page algebra/arithmetic.
- **Site visited:** None (AI-VERIFIABLE per instructions).
- **Finding:** All checked and correct. Pendulum exponents (c=0, b=−½, a=½) are right. Log-differential propagation rule is correct, including the |n| weighting and the quadrature form. Density: 2.7 × (1/1000) × 10⁶ = 2700 kg/m³ ✓. Sphere: δd/d = 0.1/5.2 = 1.92% ≈ 1.9%, ×3 = 5.8% ✓; (π/6)(5.2)³ = (π/6)(140.6) = 73.6 cm³ ✓; 0.058×73.6 = 4.27 ≈ 4.3 cm³ ✓. Room: 50/0.024 ≈ 2083 ≈ 2×10³ mol; ×6×10²³ ≈ 1.25×10²⁷ ≈ 1×10²⁷ ✓ (order claimed, leading digit disclaimed).
- **Expert review needed:** No.
- **Suggested reference:** —
- **Notes:** Internally consistent. Molar volume 0.024 m³ ≈ 24 L/mol is appropriate for room conditions (~24.0 L at 20 °C, 1 atm).

## Unverified Assertions

| # | Sentence (abbrev.) | Category | Why unverified | Suggested action |
|---|---|---|---|---|
| 1 | Fermi "landing on roughly 10 kilotons, the right order of magnitude" at the first nuclear test, July 1945 | EVIDENCE | The historical record confirms Fermi estimated ~10 kt by the paper-drop method, but the *actual* Trinity yield is ~21–25 kt (DOE official 21 kt), so 10 kt is ~half — same order of magnitude but a factor ~2 low. The chapter already carries `[verify]` and hedges ("The exact figure he cited varies across retellings; treat it as approximate"). | Verified as accurate-with-caveat: Fermi's ~10 kt estimate is real (Reines/standard accounts); calling it "the right order of magnitude" is defensible (10 vs 21 kt are the same order). The existing hedge is sufficient; no prose change required. Source: "Fermi at Trinity," arXiv:2103.05784 / *Nuclear Technology* (2021). |

## AI-Pass Flags (internal consistency / math)

- No errors found. Dimensional bookkeeping ($[F]=MLT^{-2}$, impulse $=MLT^{-1}$), all worked arithmetic, and the propagation derivation are internally consistent.
- The two `[contested — see pantry]` markers (sig-figs pedagogy; linear vs quadrature uncertainty combination) are genuine open pedagogical/metrological debates, correctly labeled as contested rather than asserted — no action.
