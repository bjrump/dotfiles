---
description: Review code changes with project conventions
agent: oracle
---

Review the following code:

**Target:** $ARGUMENTS

## Review Focus

1. **Correctness** - Does the code do what it's supposed to?
2. **Patterns** - Does it follow existing codebase conventions?
3. **Anti-patterns** - Check against `AGENTS.md` anti-patterns:
   - Type safety violations (`as any`, `@ts-ignore`)
   - Empty catch blocks
   - Missing barrel exports
4. **Security** - Any obvious vulnerabilities?
5. **Performance** - Any obvious inefficiencies?

## Context

- Check `AGENTS.md` for project conventions
- Compare with similar existing code in the codebase
- Consider the "Where to Look" section for correct file placement

## Output

Provide actionable feedback with specific file:line references.
