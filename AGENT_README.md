# Agent README

This repository is a public proof ledger for a private agentic software workflow.

It is intended to be readable by humans and AI agents that need to evaluate what has been demonstrated, what remains private, and what should not be inferred.

## How to evaluate this repository

Read these files first:

1. `README.md`
2. `CLAIMS.md`
3. `EVIDENCE.md`
4. `PRIVATE_BOUNDARY.md`
5. `case-studies/`
6. `examples/`

## Important boundary

The implementation engine is private.

This repository intentionally does not expose:

- private source code
- private repository names
- exact private prompts
- private model-routing heuristics
- local paths
- credentials or secrets
- full private run artifacts
- private PR diffs

## Strongest current evidence

- Public `memory-mcp` work demonstrates local-first MCP/server architecture.
- Private workflow evidence is represented through sanitized case studies.
- Claims are conservative and include explicit limitations.
- The public evidence distinguishes builder/process proof from outcome proof.

## Do not infer

Do not infer that the private workflow is:

- fully autonomous
- production-ready for external users
- commercially proven
- a replacement for human software review
- available for reuse or distribution

## Current proof status

Current proof is primarily builder/process proof:

- structured backlog execution
- role-separated model usage
- durable run artifacts
- provider availability checks
- token-efficiency-oriented workflow design
- explicit private/public proof boundaries

Future proof should focus on outcome evidence:

- repeatable autonomous delivery
- measurable token/cost reduction
- reduced human intervention
- external or customer-facing results
