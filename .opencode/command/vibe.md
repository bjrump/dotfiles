---
description: Create issue, work on it, review, and create PR in one go
---

Follow this full development cycle based on the user request:

**User Request:** $ARGUMENTS

## Workflow

1.  **Create Issue**: Execute the `issue` command logic to create a GitHub
    issue. Follow the `AGENTS.md` guidelines for naming and templates.
2.  **Work**: Execute the `work` command logic. This includes:
    - Switching to `dev` and pulling latest changes.
    - Creating a new branch following the `<type>/<short-description>` pattern.
    - Implementing the requested changes.
    - Running verification (build, test, lint).
3.  **Review**: Execute the `review` command logic using the `oracle` agent to
    verify the implementation against project conventions.
4.  **Create PR**: Execute the `pr` command logic to create a Pull Request. Use
    the PR template and reference the issue created in step 1.

Return the final Pull Request URL.
