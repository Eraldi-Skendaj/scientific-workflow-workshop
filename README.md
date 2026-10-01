# Scientific workflow GitHub workshop

This synthetic repository supports two browser-first workshops:

1. **GitHub Foundations for Scientific Work**
2. **GitHub Copilot for Data Scientists**

The example follows a small adverse-event summary through requirements, code, tests, a pull request, GitHub Copilot cloud agent, and GitHub Copilot code review.

This is an independent teaching repository. It is not affiliated with, sponsored by, or approved by any company, research sponsor, healthcare organization, or regulatory body.

## Choose how to use the workshop

This repository is public. Anyone can view or clone it.

```bash
git clone https://github.com/abrown152/scientific-workflow-workshop.git
```

For browser exercises, use the path that matches your account:

- **Shared repository:** If a facilitator granted you write access, create a uniquely named branch and pull request here.
- **Personal copy:** With a standard GitHub account, select **Use this template** to create your own copy and complete both labs there.
- **Enterprise Managed Users:** Managed user accounts can view and clone this public repository but cannot interact with or fork repositories outside their enterprise. Use an organization-owned copy provided inside your enterprise.

Direct contributions to this repository require collaborator access. Public visibility alone does not grant write permission.

## Important

- All data is synthetic.
- Do not add patient data, credentials, secrets, proprietary study data, or regulated content.
- Workshop changes are proposals for learning purposes. They are not validated clinical-analysis outputs.
- Human review remains required even when Copilot creates or reviews a pull request.
- Do not add customer names, event names, company logos, internal links, or other identifying information.

## Repository map

| Path | Purpose |
|---|---|
| `requirements/` | The expected analytical behavior |
| `analysis/` | Equivalent SAS, R, and Python examples |
| `data/` | Synthetic input data |
| `reference/` | Controlled terminology used by the exercise |
| `checks/` | Human-readable expected output |
| `tests/` | Automated checks for the Python example |
| `workshop/` | Participant and facilitator instructions |

## Current baseline

Requirement `AE-3` includes only events classified as `SEVERE`. The advanced workshop introduces a change request to include `LIFE THREATENING` events as well.

## Validate the repository

The browser-based workshop does not require a local environment. GitHub Actions runs the validation workflow on pull requests.

If you do run the repository locally:

```bash
python3 scripts/validate.py
```

## Workshop paths

- [Foundations browser lab](workshop/01-foundations-browser-lab.md)
- [Copilot cloud agent and code review lab](workshop/02-copilot-cloud-agent-lab.md)
- [Review checklist](workshop/review-checklist.md)
- [Facilitator guide](workshop/facilitator-guide.md)
