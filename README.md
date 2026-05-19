# Agentic Workflow Proof

This repository is a public proof ledger for a private agentic software workflow.

The implementation engine is intentionally private. This repository publishes sanitized, claim-oriented evidence about the workflow without exposing private source code, prompts, local paths, credentials, or implementation details.

## Purpose

The goal is to make the work legible to both humans and AI agents:

- what is being built
- what has been demonstrated
- what evidence exists
- what remains unproven
- which proof is public vs. private

## Current claim

David Ovitz is building and dogfooding a private AI-assisted software factory that turns structured backlog issues into validated pull requests using role-separated planning, implementation, review, judging, and durable run artifacts.

## Source systems

| System | Visibility | Role |
|---|---:|---|
| `dwovitz/memory-mcp` | Public | Local-first memory MCP server and public technical credibility surface |
| Private operating-layer repository | Private | Personal operating layer and backlog/workflow coordination surface |
| Private workflow-engine repository | Private | Private agentic software factory engine |
| `dwovitz/agentic-workflow-proof` | Public | Sanitized public proof ledger |

## Repository map

| File | Purpose |
|---|---|
| `CLAIMS.md` | Claim inventory and proof status |
| `EVIDENCE.md` | Evidence ledger mapping claims to public or private artifacts |
| `PRIVATE_BOUNDARY.md` | Rules for what can and cannot be published |
| `case-studies/001-provider-preflight.md` | First sanitized case study |
| `schemas/proof-claim.schema.json` | Draft machine-readable claim schema |
| `schemas/run-proof.schema.json` | Draft machine-readable run proof schema |

## Proof posture

This repository does not claim that the private workflow is commercially proven or fully autonomous. The current proof is primarily builder/process proof: architecture, workflow discipline, validation, artifact design, and evidence-aware AI orchestration.

The stronger future proof target is outcome proof: repeatable autonomous delivery, measurable token/cost reduction, reduced human intervention, and externally understandable run artifacts.
