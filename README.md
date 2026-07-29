# AI-Native PDLC Maturity Model

A maturity model for the Product Development Life Cycle (PDLC) — specifically, the Product Management function — in the age of AI-assisted work. Part of the same family as the [AI-Native SDLC Maturity Model](https://github.com/superdtf-0882/ai-native-sdlc-maturity-model), sharing that model's D1–D3 (market discovery, persona development, positioning & competitive intelligence) by direct reference rather than a duplicated copy.

## What this is

12 dimensions (D1–D12), each scored on a five-level ladder (A–E) sharing one family-wide vocabulary — Nascent / Modeled / Continuous / Integral / Telemetric — locked across every model in this family. D1–D4 originate from or converge with the SDLC model; D5–D11 are PM-native, with no SDLC equivalent; D12 is this model's own feedback-loop-velocity dimension.

See `ai_native_pdlc_maturity_model.md` for the full matrix — the source of truth for D4–D12. D1–D3 are sourced from [`shared_intelligence_layer.md`](https://github.com/superdtf-0882/ai-native-sdlc-maturity-model/blob/main/shared_intelligence_layer.md) in the SDLC repo, not duplicated here.

## Other files

- `short_form.yml` — one-sentence-per-cell compression of D4–D12, for consumption by external sites (e.g. aimaturitymodels.com's Whole-Model View); D1–D3 reuse the SDLC repo's own entries directly rather than a re-compressed copy. Not a source of truth, regenerate if it diverges.
- `deep_dives/` — narrative-style Per-Dimension Deep-Dive content (one file per dimension, D1–D12), for aimaturitymodels.com's Deep-Dive pages. D1–D3 reuse the SDLC repo's own `deep_dives/d1.md`–`d3.md` content directly, each with an added paragraph naming this model's own delta; D4–D12 are authored fresh from this matrix. Derived content, not independently versioned.

## Origin

This model originated as section 5 of a working draft authored directly by David Facer, alongside the SDLC and Prioritization models in the same family. It sat as a ready-to-commit draft (`v0.9`) pending two conditions: the family-wide level vocabulary locking (resolved 2026-07-24) and a sequencing gate on this practice's own AI-native SDLC maturity reaching a stated threshold (`OI-040`, resolved 2026-07-27). Both conditions cleared, this repo is the model's first locked release, `v1.0.0`.

Full governance history — the sequencing gate, the vocabulary lock, the D1–D3 reconciliation into a shared canonical source — lives in a private governance corpus, not reproduced here.

## License

CC BY 4.0 — see `LICENSE.md`. © 2026 David Facer.
