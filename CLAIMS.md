# Claims Ledger

This file tracks public claims about the agentic workflow and the current evidence posture for each claim.

## Status key

| Status | Meaning |
|---|---|
| `demonstrated-private` | Evidence exists in private repositories, PRs, issues, or run artifacts |
| `demonstrated-public` | Evidence exists in public repositories or public proof artifacts |
| `planned` | Designed or backlogged, but not yet demonstrated |
| `unproven` | Not enough evidence yet |

## Claims

| ID | Claim | Status | Evidence summary |
|---|---|---:|---|
| C001 | The workflow uses structured backlog issues as execution contracts. | demonstrated-private | Private workflow repositories include issues that define goals, acceptance criteria, and workflow constraints. |
| C002 | The workflow can produce validated pull requests from backlog items. | demonstrated-private | Private merged PRs include build/test validation summaries and issue-oriented completion reports. |
| C003 | The workflow separates implementation from review/judgment responsibilities. | demonstrated-private | Private workflow-engine work includes reviewer/judge concepts and persisted AI-judge outcome handling. |
| C004 | The workflow is being optimized for token-efficient execution. | demonstrated-private | Private backlog includes context assembly, evidence packets, local-model fallback, and inefficiency reporting work. |
| C005 | The workflow detects provider/harness availability before starting doomed runs. | demonstrated-private | Private workflow-engine provider availability preflight work has been implemented and merged. |
| C006 | The public memory layer demonstrates local-first MCP architecture. | demonstrated-public | Public `memory-mcp` README describes PostgreSQL/pgvector storage, hybrid retrieval, context packets, MCP tools, Docker persistence, and docs. |
| C007 | The workflow has not yet proven full autonomous delivery. | unproven | Current evidence still includes human operator review, manual merge, and active system refinement. |
| C008 | The workflow has not yet proven commercial/customer outcome value. | unproven | No public customer case study, external benchmark, or business result has been published. |

## Current strongest claim

The strongest defensible claim today is:

> David Ovitz is actively building and dogfooding a private AI-assisted software factory with structured backlog execution, role-separated model usage, durable run artifacts, provider availability checks, and token-efficiency-oriented workflow design.

## Claims not made

This repository does **not** currently claim that:

- the private engine is production-ready for external users
- the system is fully autonomous
- the system consistently reduces cost by a quantified percentage
- the system can replace human software review
- private implementation details are available for reuse
