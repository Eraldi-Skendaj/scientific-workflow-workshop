# Facilitator guide

## Browser-first principle

Run the workshop on GitHub.com. Do not require local Git, an IDE, language runtimes, extensions, or package installation.

## Before the event

1. Confirm attendees can view the public repository.
2. Choose the write-enabled exercise path:
   - grant standard GitHub accounts write access to the shared repository;
   - have standard accounts create copies with **Use this template**; or
   - provide an organization-owned copy inside an Enterprise Managed Users enterprise.
3. Confirm GitHub Copilot cloud agent and GitHub Copilot code review are enabled in the write-enabled repository.
4. Enable Issues, Actions, and pull requests.
5. Confirm attendees can create branches, issues, and pull requests.
6. Confirm the validation workflow can run.
7. Create one completed backup pull request for each workshop.
8. Prepare screenshots or a short recording for network contingencies.

## Foundations reset

Before each delivery:

- close or label participant pull requests from the previous delivery;
- confirm the baseline files on `main` are unchanged;
- keep one prepared pull request available for the review demonstration.

## Copilot reset

Before each delivery:

- confirm `workshop/cloud-agent-task.md` matches the baseline;
- confirm the current tests pass on `main`;
- keep a completed cloud-agent pull request available in case live sessions do not finish;
- confirm Copilot appears in the pull request Reviewers section.

## Timing guidance

Cloud-agent work is asynchronous. Start the agent task early, then teach prompt quality, evidence, and review while the session runs. Never wait silently for the agent.

Each workshop has 70 minutes of planned content inside a 90-minute room block. End the scripted content at 70 minutes. The remaining room time is recovery and transition buffer, not additional material.

## Safety language

Use synthetic data only. GitHub and Copilot support the workflow but do not replace organizational requirements, validation, security controls, scientific judgment, or formal approvals.
