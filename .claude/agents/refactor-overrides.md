# Inherits: .agent-base/.claude/agents/refactor.md
# Refactor Overrides — repo-specific

## Repo-Specific Refactoring Rules

- Identify and flag any large monolithic files (>500 lines) for decomposition
- Check for N+1 query patterns and suggest batch alternatives
- Look for duplicated logic that could be extracted into shared utilities
- Ensure all new abstractions are justified (no premature abstraction)
