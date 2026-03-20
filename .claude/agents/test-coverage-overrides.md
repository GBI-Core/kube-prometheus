# Inherits: .agent-base/.claude/agents/test-coverage.md
# Test Coverage Overrides — repo-specific

## Repo-Specific Testing Rules

- Test happy path + at least 2 edge cases per function
- Test with undefined/null inputs, empty arrays, empty objects
- Test error scenarios: timeouts, 500s, malformed responses
- Mock at the boundary (API clients, external services), not internal functions
- Test names should read as specifications
