# Owleno — shared project memory

Last reviewed: 2026-10-22

This is the durable, tool-neutral project context for Claude and Codex. Update it only after checking the repository and recording confirmed facts. Keep credentials and personal data out of this file.

## Product goal

Owleno is an English-learning platform for general English and exams such as YDS and YÖKDİL. The goal is a high-quality learning experience, a polished and professional interface, an original friendly owl mascot, and restrained gamification.

## Product areas

- Main application and learning journey
- Graphic interface and user experience
- Vocabulary, reading, grammar, and speaking
- Infrastructure, security, and deployment
- Testing and bug investigation
- Copyright and content-source research
- Shared development plan

## Current repository snapshot

- GitHub repository: `https://github.com/xlamz/yds-hazirlik`
- The repository was observed as public on 2026-10-22.
- The observed default branch is `claude/github-pages-z2a9cu`.
- The public root contains `index.html`, `README.md`, `CNAME`, `robots.txt`, `owl3d/`, and `test/`.
- `CNAME` contains `owleno.com`. The live domain displayed a YDS Hazırlık sign-in page when checked on 2026-10-22.
- The README says the single-file app is generated from `yds-app/build.py`, but that source path was not present in the observed public branch. Confirm the canonical source before changing application code.
- The local Codex checkout is on `codex/owleno`, tracking the observed remote default branch. It is a local branch; no push has been made.

## Collaboration and release safety

- GitHub is the common code hand-off point. Claude and Codex do not share a live working tree by default.
- Check the current branch and remote commits before each coding session. Avoid parallel edits to the same files; use feature branches and review diffs.
- Do not push to the default branch or alter GitHub Pages, DNS, Cloudflare, Supabase, or production settings without explicit user approval.
- Treat `owleno.com` as live. Do not change production-facing files until the source/build path and release flow are understood.
- This document is a starting snapshot, not proof of repository deployment configuration or Supabase state.

## Tools and assets

- The user has a Meshy AI subscription and plans to use it for the 3D owl mascot. The Meshy API/MCP credential and API-credit status have not been configured or verified.
- Store credentials only in an approved local secret store or environment variable, never in Git or these shared notes.

## Decision log

Append confirmed decisions with date, decision, rationale, and affected files/services. Keep unresolved questions in a separate “Open questions” section rather than recording guesses as facts.

## Open questions

- Where is the canonical editable source (`yds-app/build.py` or another location), and how is `index.html` generated?
- Which GitHub Pages workflow or branch rule currently publishes `owleno.com`?
- Which Supabase services and schema are used by the live sign-in flow?
- Is the user's Claude workspace Claude.ai Projects, Claude Code, or both? The available integration options differ.
- Does the user want Meshy API access, which uses separate prepaid API credits, or only a manual asset workflow through the Meshy web app?
