---
description: Work on a GitHub issue (investigate, implement, verify - no PR)
---

Work on the following GitHub issue:

**Issue:** $ARGUMENTS

## Workflow

1. **Read the issue** using `gh issue view`
2. **Go to and pull dev branch** using `git checkout dev` and `git pull`
3. **Understand** scope and requirements
4. **Create todo list** with atomic implementation steps
5. **Implement** following codebase patterns
6. **Verify** using pre-commit requirements from `AGENTS.md`:
   - Backend: `go build ./...` and `go test ./...`
   - Frontend: `bun run build`, `bun run lint`, `bun run format:check`

## Important

- Do NOT create a PR - user will review first
- Do NOT commit unless explicitly asked
- Follow existing codebase conventions
- Reference `AGENTS.md` for patterns and anti-patterns
