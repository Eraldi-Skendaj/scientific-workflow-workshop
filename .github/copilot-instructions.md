# Copilot instructions for this repository

- This is a synthetic workshop repository for data scientists and statistical programmers.
- Use only files already present in the repository.
- Never add real patient, customer, clinical-trial, or proprietary data.
- Keep changes focused on the issue and avoid unrelated refactoring.
- Preserve `USUBJID`, `AETERM`, and `AESEV` as the output columns and preserve their order.
- Treat `reference/controlled-terminology.md` as authoritative for this exercise.
- Update requirements, analysis implementations, expected output, and tests together when behavior changes.
- During pull request review, compare requirement identifiers in file headers and docstrings with the current requirement and report any mismatch.
- Run `python3 scripts/validate.py`.
- In the pull-request summary, list assumptions and checks that still require human scientific review.
