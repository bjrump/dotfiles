---
description: Run all pre-commit checks (build, test, lint, format)
---

Run all pre-commit verification steps from `AGENTS.md`.

## Backend (in `backend/` directory)

1. `go build ./...` - Verify compilation
2. `go test ./...` - Run all tests

## Frontend (in `frontend/` directory)

1. `bun run build` - Check for build errors
2. `bun run lint` - Code quality
3. `bun run format:check` - Code style

## Output

Report pass/fail status for each step. If any step fails, show the relevant error output.
