---
description: Create a GitHub issue (bug or feature) following project conventions
---

Create a GitHub issue based on the following request:

**User Request:** $ARGUMENTS

Follow the GitHub Workflow guidelines from `AGENTS.md` for:
- Issue type detection (bug vs feature)
- Title prefixes
- Labels
- Assignment to current user

Use `gh issue create` with HEREDOC syntax for the body.

ALWAYS use the Issue Template.

## Images

If the user attached an image to this chat:
1. Look at the image content and incorporate findings into the issue description
2. Inform the user they need to manually add the image to the issue (gh CLI cannot upload images)

Return the created issue URL.
