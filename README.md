# ClaudeLimit Planner for Developers

[Open hosted SaaS](https://claudelimitplanner.space/?utm_source=github&utm_medium=documentation&utm_campaign=claudelimit_planner_docs&utm_content=readme_primary_home) | [View pricing](https://claudelimitplanner.space/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=claudelimit_planner_docs&utm_content=readme_pricing) | [Start checkout](https://claudelimitplanner.space/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=claudelimit_planner_docs&utm_content=readme_checkout)

> Plan quota windows before AI coding work stalls mid-task.

Last reviewed: 2026-05-18.

## What This Folder Is

This is a docs-only project for ClaudeLimit Planner. It is modeled after the MiroFish developer documentation pattern: a short front door, a clear reading order, practical guides, feature explanations, public references, and developer-oriented architecture notes.

It focuses on:

- what ClaudeLimit Planner is and who should evaluate it
- how the hosted SaaS at claudelimitplanner.space fits into the workflow
- which product surfaces matter first
- what to check before payment, rollout, or team adoption
- how to keep public links tracked with UTM parameters

Scope boundary:

- This repository contains documentation only.
- It does not contain the production SaaS source code.
- It does not include private deployment details, credentials, internal paths, customer records, or analytics exports.
- If product behavior changes, verify the live SaaS before reusing these notes.

## Related Workflow

- [OpenHuman Online](https://openhuman.online/?utm_source=github&utm_medium=readme&utm_campaign=openhuman_public_repos&utm_content=claudelimit_planner) is useful when evaluation depends on durable source notes, meeting context, and human-reviewed assistant memory.

## Read This First

| File | Best for |
| --- | --- |
| [guide/quickstart.md](guide/quickstart.md) | Fastest buyer and evaluator path. |
| [guide/evaluation.md](guide/evaluation.md) | What to check before paying or rolling out. |
| [guide/checkout-and-pricing.md](guide/checkout-and-pricing.md) | Hosted SaaS, default plan, pricing, and checkout links. |
| [guide/troubleshooting.md](guide/troubleshooting.md) | Common blockers and clean next steps. |
| [features/workflow.md](features/workflow.md) | End-to-end product workflow. |
| [features/use-cases.md](features/use-cases.md) | High-intent use cases and buying triggers. |
| [features/security-model.md](features/security-model.md) | Practical safety boundaries. |
| [reference/links.md](reference/links.md) | Public links with UTM tracking. |
| [reference/faq.md](reference/faq.md) | Short answers for common questions. |
| [reference/utm-policy.md](reference/utm-policy.md) | Link tagging rules for this docs project. |
| [developer/architecture.md](developer/architecture.md) | How to explain the SaaS from a developer point of view. |

## What ClaudeLimit Planner Actually Is

ClaudeLimit Planner helps teams forecast Claude Code and Codex quota windows, split coding work into batches, route fallback models, and export capacity plans.

Use ClaudeLimit Planner when you need:

- Quota calendar preview
- Batch scheduler
- Fallback model routing
- Mobile approval hints
- Weekly AI coding capacity brief

The main hosted entry points are:

| Destination | Tracked link |
| --- | --- |
| SaaS home | [claudelimitplanner.space](https://claudelimitplanner.space/?utm_source=github&utm_medium=documentation&utm_campaign=claudelimit_planner_docs&utm_content=readme_links_home) |
| Pricing | [pricing](https://claudelimitplanner.space/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=claudelimit_planner_docs&utm_content=readme_links_pricing) |
| Checkout | [checkout](https://claudelimitplanner.space/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=claudelimit_planner_docs&utm_content=readme_links_checkout) |

## Default Evaluation Path

1. Estimate the work, deadline, repo risk, and reviewer availability.
2. Map Claude, Codex, Gemini, and human-review lanes to available quota windows.
3. Split large AI coding work into recoverable batches with test expectations.
4. Export a weekly capacity brief before the team burns premium model time.

## Minimum Safety Checklist

- Do not treat quota planning as a substitute for code review.
- Keep high-risk patches behind human approval.
- Leave rollback time in every quota window.
- Avoid scheduling all critical work in the final reset window.

## Suggested Reading Order

1. [Quickstart](guide/quickstart.md)
2. [Evaluation](guide/evaluation.md)
3. [Workflow](features/workflow.md)
4. [Use cases](features/use-cases.md)
5. [Security model](features/security-model.md)
6. [Checkout and pricing](guide/checkout-and-pricing.md)
7. [FAQ](reference/faq.md)

## Contributing

Corrections are welcome. Keep this project public-safe: cite public sources, avoid copying long passages from other projects, and never include credentials, customer data, private logs, internal machine paths, or untracked outbound links.
