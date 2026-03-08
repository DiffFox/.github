# DiffFox

> Smart eyes on every diff.

DiffFox is building AI-native GitHub workflows, starting with pull request review and evolving toward a reusable private GitHub App.

## What We Build

- AI review for pull request diffs
- GitHub-native comment workflows for manual retriggers
- relay-friendly model access through a custom Responses API endpoint
- repository-level review configuration for flexible rollout

## Repositories

| Repository | Purpose |
| --- | --- |
| [`DiffFox`](https://github.com/DiffFox/DiffFox) | Main codebase for the GitHub App, Actions MVP, review logic, CI, and tests |
| [`DiffFox_docs`](https://github.com/DiffFox/DiffFox_docs) | Product planning, roadmap, setup notes, and prototype discussion documents |

## Recommended Pinned Repositories

If you pin repositories on the organization homepage, the recommended order is:

1. [`DiffFox`](https://github.com/DiffFox/DiffFox)
2. [`DiffFox_docs`](https://github.com/DiffFox/DiffFox_docs)

`DiffFox` should stay first because it is the main product repository.
`DiffFox_docs` should stay second because it gives planning and onboarding context.

## Current Stage

DiffFox has already validated the first GitHub Actions MVP and is now moving toward a reusable GitHub App path with:

- automatic PR review triggers
- manual review commands
- success and failure comment writeback
- manifest-based App setup
- repository-level configuration

## Start Here

- Product and planning docs: [`DiffFox_docs`](https://github.com/DiffFox/DiffFox_docs)
- Implementation and code: [`DiffFox`](https://github.com/DiffFox/DiffFox)

## Focus

The near-term goal is simple:

> turn a working PR review MVP into a stable, installable private GitHub App.
