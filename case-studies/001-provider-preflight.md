# Case Study 001: Provider Availability Preflight

## Claim demonstrated

A private agentic software workflow should detect unavailable or exhausted model/harness providers before starting a run that is likely to fail.

## Why this matters

Agentic development systems are vulnerable to wasted execution when a required role depends on a provider that is unavailable, quota-limited, unauthenticated, misconfigured, or token-exhausted.

A safer workflow checks required providers before beginning expensive work and fails closed when there is no approved fallback.

## Private source system

- Private repository: `dwovitz/dark-factory`
- Evidence type: private issue, private pull request, private tests, private run artifacts
- Public exposure: sanitized summary only

## Sanitized problem statement

The workflow needed a provider/harness availability preflight so a run would not begin when a required role had no usable harness and no approved fallback.

Required provider states included:

- available
- unavailable
- quota or token exhausted
- authentication or configuration failure
- unknown failure

## Sanitized implementation outcome

The private workflow added:

- structured provider availability modeling
- fail-closed startup behavior
- extension points for provider-specific checks
- role-aware required provider checks
- persisted availability snapshots in run artifacts
- run summaries that explain skipped runs or routing degradation

## Validation summary

The private implementation reported successful build and test validation, including focused tests for provider availability states and role-specific unavailable-provider paths.

Public proof status: private evidence exists; sanitized public artifact exists here.

## Human involvement

A human operator still reviewed and merged the resulting private pull request.

This case study does not claim full autonomy.

## Limitations

- Deeper provider-specific quota/model probes remain a future improvement.
- Approved fallback routing is separate follow-up work.
- The public artifact intentionally omits private source code, exact prompts, private file names, and implementation details.

## Proof value

This demonstrates process maturity more than product maturity. It shows that the workflow is being designed around reliability, cost control, and fail-closed behavior rather than only successful happy-path generation.

## Next proof target

Publish a second sanitized case study showing durable AI-judge outcome persistence before publishing or merging decisions.
