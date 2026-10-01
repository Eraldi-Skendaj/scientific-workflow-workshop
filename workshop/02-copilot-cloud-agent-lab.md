# Copilot cloud agent and code review lab

## Goal

Use GitHub.com to delegate a bounded repository change, inspect the resulting pull request, request GitHub Copilot code review, and make a human decision.

## Part 1: Prepare the task

Work in pairs. Create one issue and one cloud-agent session per pair.

Choose the correct repository first:

- If your facilitator granted write access, use this shared repository.
- With a standard GitHub account, you can select **Use this template** and work in your own copy.
- With an Enterprise Managed User account, use an organization-owned copy inside your enterprise. Copilot cloud agent is not available in personal repositories owned by managed users.

1. Open `workshop/cloud-agent-task.md`.
2. Create a new issue using the **Analysis change** template.
3. Add your GitHub username to the issue title so the task is unique.
4. Transfer the objective, context, constraints, acceptance criteria, and review questions into the issue.
5. Read the issue once as if another person had to execute it. Improve any ambiguous instruction.

## Part 2: Delegate in the browser

1. Start a GitHub Copilot cloud agent session from the issue or the GitHub agents experience provided by the facilitator.
2. Ask Copilot to research the repository and produce a plan before changing files.
3. Inspect the proposed plan:
   - Does it name all affected files?
   - Does it preserve the output structure?
   - Does it include validation?
   - Does it preserve unresolved human-review questions?
4. Refine the instructions if the plan is too broad or misses evidence.
5. Ask Copilot to implement the approved plan and create a pull request.

## Part 3: Review the pull request

1. Read the pull-request description before the diff.
2. Compare the changed requirement, code, expected output, and tests.
3. Confirm that the validation workflow ran.
4. Request **GitHub Copilot code review** from the Reviewers section.
5. Classify each Copilot comment:
   - useful and actionable;
   - plausible but requires human verification;
   - not relevant or incorrect.
6. Apply or delegate a fix only after you agree with the comment.
7. Leave a human review summarizing what is ready and what still requires scientific or validation review.

## Success criteria

- The issue is bounded and evidence-rich.
- The cloud-agent plan was inspected before implementation.
- The pull request connects requirement, code, checks, and tests.
- Copilot code-review comments were evaluated rather than accepted automatically.
- The final decision remains human.

Do not merge unless the facilitator asks you to.
