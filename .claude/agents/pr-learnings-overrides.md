# Inherits: .agent-base/.claude/agents/pr-learnings.md
# PR Learnings Overrides — repo-specific

## Scan Focus

When scanning PR history, pay special attention to:

- Fix-after-fix chains (multiple commits fixing the same issue)
- Missing error handling that caused production incidents
- Security issues that were caught late in review
- Performance regressions from N+1 patterns or unbounded queries
