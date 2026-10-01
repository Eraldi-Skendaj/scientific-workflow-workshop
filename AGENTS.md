# Workshop Agent Instructions

## Scope

This repository is a synthetic teaching environment for statistical programmers and data scientists.

## Rules

- Never add real patient, clinical-trial, customer, or proprietary data.
- Keep changes limited to the files named in the issue.
- Preserve the output columns and ordering unless the issue explicitly requests otherwise.
- Treat `reference/controlled-terminology.md` as the source of truth for severity values.
- Update the requirement, implementation, expected-output documentation, and tests together when behavior changes.
- Do not claim that passing automated tests constitutes scientific validation.
- Surface assumptions and unresolved questions in the pull-request description.

## Validation

Run:

```bash
python3 scripts/validate.py
```

## Pull-request expectations

Every pull request should explain:

1. What requirement changed.
2. Which files changed and why.
3. What checks were run.
4. What still requires human verification.
