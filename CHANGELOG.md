# Changelog — AI-Native PDLC Maturity Model

## v1.2.5 — 2026-10-17

**Layout only: text-neutral under STD-MODEL-PARTS v1.1.** Each of D4–D12's tables is written in the model family's common form (§5.1, §5.2): the dimension under its own second-level heading, each level under `### A — Nascent`, its step onward as `**Transition from A to B**` with its `**Verification:**` line, and the sustainment at E as `**Sustainment:**`. Every cell is kept word for word; row E's verification cell, a dash, has no text to keep. The reading rules take the common title, *How to read this model*. No word of any level, transition, verification, sustainment, definition, note or reading rule changed, as the release check's text-neutral test shows against v1.2.4; scores against v1.2.4 are unaffected. Work Item OKF-TOGAF#205.

## v1.2.4 — 2026-10-17

A wording release under the model family's parts standard (STD-MODEL-PARTS v1.1). No level, transition or verification changed, and no score against v1.2.3 is affected.

- The level-names section is the five names and a pointer to the family's one home for them, `family_maturity_levels.md` in the SDLC repository at v1.4.2, in its own section before the reading rules. Its table, its list of the family's models and its closing sentence go.
- D1–D3 stand under their own range heading, `## D1–D3. Shared Intelligence Layer`, with a basis line naming the layer at SDLC v1.4.3, its common-form tag; their text there is the same as at v1.4.0. PDLC's own deltas on D1 and D3 stay.
- The model no longer describes the family's other models: the three group headings go; the opening and the family-position line keep what they say of PDLC, the latter corrected, since D4 is this model's own; D4's, D5's, D11's and D12's notes cite the other models by standard ID (`STD-SDLC-MM`, `STD-PRIORITIZATION-MM`).
- Pre-AI and Exempt are named by their source, the EA model's text at v1.1.2.
- The README links the family's models page, says D1–D3 come from the shared layer at v1.4.3, and states the version rule.
- `tools/release-check.js` and `tools/model-parser.js` are the practice's template's current copies; `short_form.yml` cites this release's text commit.

## v1.2.3 — 2026-10-08

**One line, and nothing else.** The level names line said the names are identical across "(SDLC, PDLC, and Prioritization)": it now names all four models, Enterprise Architecture included, by their current names, as the Portfolio Prioritization model's v1.4.1 does. No level, transition or verification changed. Found by CC in aimaturitymodels.com's full digest while fixing the same line in the Portfolio Prioritization model (OKF-TOGAF#169).

## v1.2.2 — 2026-10-08

**The matrix's own version line, corrected.** v1.2.1 changed two notes in the matrix and left its version line reading 1.2.0. It now names this release, and says what v1.2.1 did. Nothing else changed. Found by an outside reading of aimaturitymodels.com's full digest (OKF-TOGAF#169).

## v1.2.1 — 2026-10-07

**A name, four times, and nothing else.** The standalone model that D5's note and D11's note point to was renamed the AI-Native Portfolio Prioritization Maturity Model at its own v1.4.0 (formerly the AI-Native Product Prioritization Maturity Model). This model's D5 and D11 notes, and the D5 and D11 deep-dives, now use the new name. No level, transition or verification clause changed; scores against v1.2.0 are unaffected.

## v1.2.0 — 2026-07-28

Added `deep_dives/` — narrative-style Per-Dimension Deep-Dive essays for all 12 dimensions, for aimaturitymodels.com's Deep-Dive pages (matching the SDLC model's own precedent). D1–D3 reuse the SDLC repo's ratified Shared Intelligence Layer essays directly, each with one added paragraph naming this model's own delta (D1's portfolio-investment feed into D8; D3's absorption of strategic synthesis; D2 carries no delta and is reused verbatim). D4–D12 are authored fresh, grounded in this matrix's own v1.1.0 locked content including the per-transition verification clauses. No change to any dimension's underlying maturity-state content — this adds narrative essay content, it does not revise the matrix itself.

## v1.1.0 — 2026-07-28

Added a **Verification** clause to every A→B, B→C, and C→D transition across D4–D12 (36 new clauses), matching the family's own precedent — SDLC's D4–D13 each carry an explicit, practical test of whether the destination state was actually reached, not just claimed. Where a transition already carried an informal "The test: ..." sentence (present in some but not all of D5–D11), it's reformatted as an explicit **Verification:** clause with the same substance, not rewritten. Level E's own row is unchanged — its existing "Sustain: ..." text already serves this purpose at the top of the ladder, per the same convention SDLC uses (a sustainment note instead of a further transition).

No change to any dimension's underlying maturity-state content — the Level descriptions and existing transition guidance are unchanged; this adds a missing verification layer, it does not revise what "good" looks like at any level.

## v1.0.0 — 2026-07-27

First locked baseline, repo created. Content originates from David Facer's own working draft (section 5 of the family's original brief, filed verbatim 2026-07-21), held pending two conditions:

1. **Family-wide level vocabulary lock** (resolved 2026-07-24): the draft's placeholder names (Initial / Emerging / Structured / Integrated / Adaptive) are replaced throughout with the locked family vocabulary (Nascent / Modeled / Continuous / Integral / Telemetric), identical to the SDLC and Prioritization models.
2. **Sequencing gate** on this practice's own AI-native SDLC maturity reaching a stated threshold (resolved 2026-07-27): both halves of the gate condition — the SDLC model's own D6 dimension closing, and its D4 dimension incrementing off its floor level — are now met.

Also at lock: D1–D3 (Market discovery & definition, Buyer/user persona development, Positioning & competitive intelligence) are extracted to `shared_intelligence_layer.md` in the SDLC repo — the same canonical, shared source that model's own v1.2.0 already inherits from — rather than carrying a locally-maintained copy. That local copy had drifted from the ratified canonical text (different structure and wording) since the draft predated the Shared Intelligence Layer's own ratification by two days; this lock replaces it with a reference plus this model's own PDLC-specific deltas, rather than reconciling a divergent copy.

D4 (Requirements management) is *not* extracted alongside D1–D3 — it carries its own full ladder, diverging from the SDLC model by design (traceability extends upstream to market/user signal and downstream to portfolio investment; the PM function owns that bridge). D5–D11 are PM-native, with no SDLC equivalent. D12 is this model's own feedback-loop-velocity dimension.

No content changes beyond the two corrections above — the underlying maturity-state definitions are unchanged from the original draft.
