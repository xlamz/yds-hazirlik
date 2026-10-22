# Owleno — Codex instructions

Read `docs/project-memory/README.md` before making project changes. Keep durable product facts and shared decisions there; keep tool-specific behavior here.

## Working rules

- Explain the current state and plan before important changes. Wait for the user's approval before implementing them.
- Do not commit, push, publish, change GitHub settings, or alter the database schema unless the user specifically authorizes that action.
- Protect the live `owleno.com` application. Work on a `codex/*` branch and do not push it unless asked.
- Inspect current code and deployment assumptions before editing. Do not claim tests passed unless they were run.
- Explain technical choices in clear Turkish. State uncertainty and alternatives.
- Never place credentials, API keys, or private user data in the repository.

## Shared collaboration

- Treat GitHub as the shared code hand-off point with Claude. Check branch and commit state before editing; do not assume the other tool's working tree is synchronized.
- Keep durable decisions in `docs/project-memory/README.md` and record the date and rationale for material changes.
- Ask the user to review a concrete diff before any commit or publication.
