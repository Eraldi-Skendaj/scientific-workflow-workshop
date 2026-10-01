# Human review checklist

## Requirement fit

- Does the proposal implement the stated objective?
- Is every changed file necessary?
- Did unrelated behavior remain unchanged?

## Scientific and terminology review

- Do severity values match the supplied terminology exactly?
- Are assumptions visible?
- What still requires a domain expert?

## Evidence

- Does the expected output match the requirement?
- Do automated checks cover the changed behavior?
- Did the workflow complete successfully?
- Are the SAS, R, and Python examples consistent?

## Copilot review

- Is each Copilot comment supported by the repository evidence?
- Would applying the suggestion preserve the requirement and constraints?
- Does the comment identify a real defect, a possible risk, or only a preference?

## Decision

- Ready for further validation
- Request changes
- Reject the proposal

Record the reason. Never treat a passing check or Copilot comment as the final scientific decision.
