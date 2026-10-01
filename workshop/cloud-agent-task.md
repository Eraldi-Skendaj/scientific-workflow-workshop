# Workshop change request: include life-threatening events

## Objective

Update the adverse-event summary so it includes records classified as either `SEVERE` or `LIFE THREATENING`.

## Relevant repository context

- `requirements/analysis-requirements.md`
- `reference/controlled-terminology.md`
- `analysis/ae_summary.py`
- `analysis/ae_summary.R`
- `analysis/ae_summary.sas`
- `checks/expected-output.md`
- `tests/test_ae_summary.py`

## Constraints

- Use only the synthetic repository data.
- Preserve the existing output columns and their order.
- Keep the change limited to this requirement.
- Do not treat automated tests as scientific validation.
- Surface assumptions and unresolved questions in the pull request.

## Acceptance criteria

- The requirement includes both severity values.
- All three analysis examples implement the same filter.
- Expected output lists four records: subjects `003`, `004`, `006`, and `007`.
- Automated tests expect four records and both severity values.
- `python3 scripts/validate.py` passes.
- The pull request explains what still requires human review.

## Review focus

- Exact controlled terminology
- Output-column stability
- Expected record count
- Consistency across SAS, R, Python, requirements, checks, and tests
