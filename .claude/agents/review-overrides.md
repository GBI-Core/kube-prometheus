# Inherits: .agent-base/.claude/agents/review.md
# PR Review Overrides — repo-specific

## Repo-Specific Review Checks

- Verify all new endpoints/handlers enforce authentication
- Check for hardcoded secrets, API keys, or credentials
- Ensure error handling uses greppable error codes (SOURCE_OPERATION_FAILURE pattern)
- Confirm input validation at API boundaries
- Check that no PII or sensitive data is logged at INFO level or above
