# Inherits: .agent-base/.claude/agents/pr-description.md
# PR Description Overrides — repo-specific

## Repo-Specific Risk Flags

Always mention in the Risk section when applicable:

- **New dependencies** — must justify, pin exact version, `npm audit` / equivalent clean
- **Auth/security changes** — must be reviewed by security-aware reviewer
- **Database schema changes** — migration risk, backward compatibility
- **API contract changes** — breaking change risk, versioning
