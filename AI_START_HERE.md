# AI Start Here — Financial Stream Website

## Purpose
Deterministic entrypoint for a fresh session working on `proaiexpert/financialstream.github.io`.

## Required First Actions
1. Fetch current `main` and record SHA.
2. Read `AGENTS.md`.
3. Read `AI_CURRENT_HANDOFF.md`.
4. Read `README.md` when present.
5. Read only task-specific files and canonical documents named by the handoff or owner.
6. Inspect relevant branch/PR metadata when active work is referenced.

## Role Selection
- Strategy or architecture → `Control`.
- Implementation, branch, commit, or push → `Builder`.
- Audit or readiness check → `Reviewer`.
- Merge/publication → `Publisher`, only when explicitly authorized.
- Ambiguous request → `Control`, read-only.

## Project Invariants
- Preserve EN/RU route parity and localized content.
- Preserve forms, Chatbase, calendar, email, and existing integrations unless explicitly changing them.
- Payroll services are not offered and must not be introduced.
- Preserve client-owned access, truthful accounting positioning, canonical/hreflang, and contact flow.
- Never modify `main`, merge, publish, roll back, force-push, delete, or perform destructive operations without explicit owner authorization.

## Risk Routing
- Tier 1: one ChatGPT chat for small scoped work.
- Tier 2: separate Builder and Reviewer chats for production-facing, shared UI/JS, EN/RU, SEO, or medium-risk work.
- Tier 3: Codex only for a real local-runtime, browser automation, complex testing, broad debugging, or large-refactor need.

## First Response Contract
Report repository, role, risk tier, main SHA, files read, current state, task interpretation, branch, permissions, blockers, and next action before editing.

## Handoff Rule
After meaningful merged work, update `AI_CURRENT_HANDOFF.md` in the same approved documentation pass.
