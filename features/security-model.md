# Security Model

This documentation is public. It should explain safe evaluation without leaking implementation details.

## Public-Safe Claims

- ClaudeLimit Planner is a hosted SaaS for Claude Code and Codex quota planner.
- The documentation is independent from private production infrastructure.
- Readers should verify live behavior before making procurement or rollout decisions.
- Sensitive data should stay out of public examples and public GitHub issues.

## Practical Guardrails

- Do not treat quota planning as a substitute for code review.
- Keep high-risk patches behind human approval.
- Leave rollback time in every quota window.
- Avoid scheduling all critical work in the final reset window.

## Data Boundaries

Do not include:

- API keys, tokens, payment secrets, webhook secrets, or account identifiers.
- Private repositories, private customer names, private analytics, or local machine paths.
- Internal Cloudflare, database, registrar, or payment-provider configuration.
- Screenshots that reveal private sessions, accounts, or browser profiles.

## Safe Link

Use the public SaaS link with UTM:

- https://claudelimitplanner.space/?utm_source=github&utm_medium=documentation&utm_campaign=claudelimit_planner_docs&utm_content=security_safe_link
