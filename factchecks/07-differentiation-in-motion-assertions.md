# Fact-check: 07 — Differentiation in Motion

**Field:** mathematics / physics
**Source file:** chapters/07-differentiation-in-motion.md
**Date checked:** 2026-05-30

## Breakdown

- Assertions classified and checked: 9 (4 historical/attribution EVIDENCE-SPECIALIST; 1 SPECIALIST education-research; 4 AI-verifiable derivations/numerics)
- CONFIRMED: 4 (web) + 1 (context) + 4 (AI-pass) = 9
- OUTDATED: 0
- CONTRADICTED: 0
- UNVERIFIED: 0
- Priority-debate flag carried in-text (correctly): 1 (Huygens/Newton centripetal priority)

## ⚠️ Critical — Requires Immediate Expert Review

None found.

## Full Findings

1. **Newton, *Principia* (1687), Book I — geometric analysis of centripetal motion; coined "centripetal."** — CONFIRMED. Newton coined "centripetal" force (vis centripeta) by analogy with Huygens's "centrifugal"; *Principia* (1687) develops the circular-motion analysis. https://en.wikipedia.org/wiki/History_of_centrifugal_and_centripetal_forces

2. **Huygens, *De vi centrifuga* (written 1659, pub. 1703) and *Horologium Oscillatorium* (1673) — v²/r result by a geometric limiting argument; the Huygens/Newton priority is debated.** — CONFIRMED, and the in-text "[debated — see pantry]" flag is accurate. Huygens coined "centrifugal force" in *De vi centrifuga* (1659; pub. posthumously 1703) and treated it in *Horologium Oscillatorium* (1673); he gave a mathematical study of the gravity–speed–radius relation that Newton later recast with inertia + centripetal force. https://en.wikipedia.org/wiki/History_of_centrifugal_and_centripetal_forces ; https://www.encyclopedia.com/science/encyclopedias-almanacs-transcripts-and-maps/christiaan-huygens-makes-fundamental-contributions-mechanics-astronomy-horology-and-optics

3. **Gibbs & Wilson, *Vector Analysis* (1901) — î, ĵ, k̂ notation and componentwise differentiation of vector functions.** — CONFIRMED with a nuance. The book (Wilson 1901, from Gibbs's Yale lectures) standardized vector notation/vocabulary and *popularized* î, ĵ, k̂. The î, ĵ, k̂ symbols *originate* with Hamilton (quaternion units); Gibbs/Wilson popularized them. Chapter's claim (notation + componentwise differentiation) is defensible as the standardizing/popularizing source. https://en.wikipedia.org/wiki/Vector_Analysis

4. **Euler, *Mechanica* (1736) — recasting mechanics in analytic/component form.** — CONFIRMED. *Mechanica sive motus scientia analytice exposita* (1736), two volumes, founded analytical mechanics, replacing Newton's geometric methods with analytical ones. https://en.wikipedia.org/wiki/Mechanica

## Unverified Assertions

| Assertion | Category | Why unverified | Suggested source |
|---|---|---|---|
| (none) | — | — | — |

## AI-Pass Flags

All on-page derivations and numerics verified correct, no web needed:

- **Componentwise derivative legitimacy:** limit of a vector difference quotient distributes over fixed î,ĵ,k̂ ⇒ derivative of each component. CONFIRMED.
- **Projectile independence:** x=(v₀cosθ₀)t, y=(v₀sinθ₀)t−½gt² ⇒ vₓ=v₀cosθ₀ (constant), v_y=v₀sinθ₀−gt; at apex v_y=0 but vₓ≠0. CONFIRMED.
- **Centripetal derivation:** r⃗=r cos(ωt)î+r sin(ωt)ĵ ⇒ v⃗=−rω sin î+rω cos ĵ; |v⃗|=rω (using sin²+cos²=1); a⃗=−ω²r⃗; a_c=ω²r=v²/r (since v=rω). CONFIRMED.
- **Jet numerics (Example 1):** r=134²/9.8=17,956/9.8≈1,833 m ✓; 8g: 17,956/78.4≈229 m ✓.
- **Satellite (Example 2):** r⃗=(5.0t+2.0)î+3.0t²ĵ ⇒ v⃗=5.0î+6.0t ĵ, a⃗=6.0ĵ. CONFIRMED.
- **Closing speed (Example 3):** ds/dt=(40·(−20)+30·(−15))/√(40²+30²)=(−800−450)/50=−25 m/s. CONFIRMED.

Education-research claim: "independence-of-perpendicular-components misconception documented in physics-education research (Halloun & Hestenes lineage)" — Halloun & Hestenes (1985, *Am. J. Phys.*) is a real, standard PER reference on mechanics misconceptions (treated as context; correctly characterized in-kind).
