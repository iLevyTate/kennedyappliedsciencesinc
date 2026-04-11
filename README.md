Page for Kennedy Applied Sciences, Inc.

## Messaging Guardrails

Use these rules for website copy, metadata, social snippets, and sales-facing text in this repo.

### Allowed Claim Patterns

- "Designed to support [regulatory-aligned] environments"
- "Supports [workflow] when paired with appropriate organizational controls"
- "Can reduce [risk/exposure] for [specific use case]"
- "Intended to run locally / prioritize local processing"
- "Alignment targets such as [framework]" (not equivalent to certification)

### Disallowed Phrases

- "HIPAA compliant", "HIPAA certified", or similar certification claims
- Guarantees such as "never", "always", "zero risk", "guaranteed", "cannot fail"
- Absolute technical/legal outcomes such as "no data ever leaves", "fully secure", or "ensures compliance"
- Implying government endorsement of compliance status

### Review Checklist Before Publish/Commit

1. Replace absolutes with qualified wording (`designed to`, `supports`, `can`, `intended to`).
2. Ensure regulated claims include scope and conditions (implementation, configuration, contracts, controls).
3. Confirm no certification language is used unless verifiable and explicitly documented.
4. Keep one concise qualifier near regulation-heavy sections.
5. Run a final risky-term sweep in `index.html` for:
   - `compliant`, `certified`, `guarantee`, `never`, `always`, `zero`, `cannot`, `ensure`