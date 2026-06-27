# AGENTS.md

## Project Context
This repository is an actively developed software project. AI coding agents (Codex, Copilot, Claude Code, etc.) must follow these rules when modifying the codebase.

## Core Principles
- Preserve existing business logic and system behavior.
- Avoid large-scale refactors unless explicitly requested.
- Prefer minimal, incremental changes.
- Do not introduce new architecture patterns without necessity.

## Code Standards
- Follow existing code style in the repository.
- Keep functions small, readable, and single-responsibility.
- Match naming conventions already used in the codebase.

## Development Rules
- Always inspect existing implementation before making changes.
- Reuse existing utilities and patterns instead of creating new ones.
- Ensure backward compatibility.

## Testing Guidelines
- Do not remove or weaken existing tests.
- Add tests for new features when applicable.
- Ensure system remains runnable after changes.

## Operational Commands
- Build: follow repository scripts or README
- Run: follow project entry entrypoints
- Test: execute existing test suites

## Safety Constraints
- Do not modify authentication, payment, or core domain logic unless explicitly instructed.
- Avoid silent behavior changes.

## Commit Convention
- Use concise and descriptive commit messages.
- Example: fix: correct login validation flow