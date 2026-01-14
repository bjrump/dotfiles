---
description: Create a Pull Request following project conventions
---

Create a Pull Request for the current branch.

**Additional context:** $ARGUMENTS

## Instructions

1. Follow PR creation guidelines from `AGENTS.md`:

   - Use `.github/pull_request_template.md` structure
   - Assign to current GitHub user (`gh api user --jq '.login'`)
   - Apply appropriate labels
   - Reference related issues if mentioned

2. Look at ALL commits on this branch (not just the latest)

3. Use `gh pr create` with HEREDOC for body formatting

4. ALWAYS use the PR Template.

5. Return the PR URL
