# Owleno — Claude instructions

Read `docs/project-memory/README.md` at the start of work. This document contains shared project context; keep Claude-specific usage notes here.

## Working rules

- Explain the current state and plan before important changes. Wait for the user's approval before implementing them.
- Do not commit, push, publish, change GitHub settings, or alter the database schema unless the user specifically authorizes that action.
- Protect the live `owleno.com` application. Coordinate through Git branches and check the latest remote state before editing.
- Inspect current code and deployment assumptions before editing. Do not claim tests passed unless they were run.
- Explain technical choices in clear Turkish. State uncertainty and alternatives.
- Never place credentials, API keys, or private user data in the repository.

## Shared collaboration

- Use GitHub as the shared code hand-off point with Codex. Do not assume Codex can be invoked from this Claude session; use a reviewable branch, commit, or pull request for hand-off.
- Keep durable decisions in `docs/project-memory/README.md` and record the date and rationale for material changes.
- Ask the user to review a concrete diff before any commit or publication.
