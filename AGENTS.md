# AGENTS.md

## Repo Mission
Coordinate agentic development, enabling autonomous coding agents (Jules, Claude, etc.) to collaborate safely, efficiently, and according to best practices.

## Coding/Style Standards
- Use language best practices (e.g., Python PEP8, JS Standard Style).
- Document public APIs and key business logic.
- Adhere to folder/file naming conventions.

## PR Quality Checklist (agents must verify):
- All code passes linting and type checks.
- All tests must pass; include a coverage summary.
- No TODOs or commented-out code remains.
- PR contains a concise summary of changes, reasoning, and risks.
- No dead code. No breaking changes without approval.
- Security and privacy are reviewed for API/data/auth changes.
- Major logic blocks are commented if non-trivial.

## Build & Test
- Run `make test` or repo default test command.
- Validate through CI pipeline.

## Continuous Improvement & Learnings
- If an agent encounters repeated failures, unexpected complexity, or multi-step troubleshooting, document the issue and the solution here as a new **Agent Learnings** entry, dated.
- Agents should update AGENTS.md via a dedicated PR, titled "Agent Learning: <topic>", or add new dated learnings below.

## Agent Learnings
<!--
2025-11-13: [Example] When deploying to Vertex AI, region config in `deploy.py` is critical. Prior failure was due to missing region.
-->