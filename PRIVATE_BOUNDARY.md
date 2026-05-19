# Private Boundary

This repository exists to prove capability without publishing the private engine.

## Private by default

The following remain private unless explicitly reviewed and sanitized:

- `dark-factory` source code
- `ai-os` source code
- exact private prompts
- exact model-routing heuristics
- local filesystem paths
- credentials, tokens, environment variables, and secrets
- full private run artifacts
- full private backlog exports
- private issue comments that include implementation details
- private PR diffs
- private screenshots containing source code or local machine details

## Public-safe by default

The following are generally safe to publish:

- high-level architecture diagrams
- sanitized run summaries
- sanitized claim/evidence tables
- public `memory-mcp` documentation references
- proof schemas
- examples with synthetic data
- redacted validation output
- case studies that describe outcomes without exposing implementation

## Sanitization checklist

Before publishing a proof artifact, confirm:

- [ ] No secrets, tokens, credentials, API keys, or private URLs.
- [ ] No private source code snippets unless intentionally approved.
- [ ] No exact proprietary prompts.
- [ ] No sensitive local paths or machine identifiers.
- [ ] No private personal data.
- [ ] No implementation detail that materially enables cloning the private engine.
- [ ] Claims are matched to evidence and do not overstate autonomy or reliability.
- [ ] Limitations are stated where relevant.

## Approved proof shape

Use this pattern:

```text
Claim -> Sanitized evidence -> Validation summary -> Human involvement -> Limitations -> Next proof target
```

## Disallowed proof shape

Avoid this pattern:

```text
Claim -> Full private implementation -> Exact prompts -> Full run artifacts -> Private diffs
```

## Principle

Publish enough for trust. Keep enough private for leverage.
