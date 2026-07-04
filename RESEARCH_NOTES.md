# RESEARCH_NOTES

**Domain:** Deeptech / General AI infrastructure
**Upstream:** https://github.com/ollama/ollama
**Fork:** https://github.com/sureshsolannki-ai/ollama
**Priority:** High
**Baseline date:** 2026-07-04

## Use case fit

Local LLM runtime for offline/edge deployments — critical for spotty rural connectivity in Akshaya Dhara flows and for chamelion-agent air-gapped verifier tools.

## Planned adaptation notes

Package chosen small models (Qwen/Gemma) as ollama Modelfiles; benchmark cold-start on low-end hardware; keep off identity/consent paths.

## Boundaries

- Advisory tier only unless explicitly upgraded via an approved gate.
- Do not conflate model output with sensor evidence — respect T3/T4/T5 evidence discipline.
- Do not enable Aadhaar/registry/beneficiary/payout paths from this repo.
- No server secrets or forbidden identity fields persisted from adaptation work here.

_This file is a research baseline. It is not a design decision, roadmap commitment, or claim of registry approval._
