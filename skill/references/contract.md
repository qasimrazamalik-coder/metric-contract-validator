# Contract

## Capability
Validate KPI definitions for owner, grain, numerator, denominator, filters and change-control metadata.

## Input root
`metrics` with fields: name, owner, grain, numerator, denominator.

## Output
JSON containing `skill` and deterministic findings, ranking, mapping, plan or redaction results.

Reject malformed JSON. Do not infer authorization or fabricate evidence.
