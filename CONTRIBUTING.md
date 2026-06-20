# Contributing to SpecFlow Studio

Thank you for helping build a transparent, local-first workspace for specification-driven development.

SpecFlow Studio is currently in the foundation phase. Contributions should reduce ambiguity, improve reviewability, or move a documented roadmap item toward a verifiable result. Large feature implementations should be preceded by an issue that records the user problem, constraints, alternatives, and acceptance criteria.

## Before starting

1. Read `README.md`, `ABOUT.md`, and `ROADMAP.md`.
2. Search existing Issues and pull requests for related work.
3. Open a focused proposal before changing schemas, storage formats, export adapters, privacy behavior, or the desktop architecture.
4. Keep claims aligned with shipped behavior. Do not add screenshots, badges, performance numbers, or compatibility statements for features that do not exist yet.

## Useful contribution areas

- Clarification and specification workflow design.
- Versioned schema proposals and migration fixtures.
- Accessibility and keyboard-navigation reviews.
- Local workspace, backup, and recovery design.
- Export-adapter contracts for Codex, Claude Code, Cursor, OpenCode, Gemini CLI, and generic Markdown.
- Deterministic examples, tests, documentation, and architecture decision records.

## Development principles

- Local-first by default.
- Human-readable project artifacts.
- Explicit user approval before files are written or commands are executed.
- Deterministic exports from the same reviewed input.
- Clear error states instead of silent rewriting.
- Vendor-neutral interfaces where practical.

## Branches and commits

Use a short branch name such as `feat/spec-schema`, `fix/export-preview`, or `docs/adr-template`.

Use focused Conventional Commit messages:

- `feat:` user-visible capability
- `fix:` defect correction
- `docs:` documentation only
- `test:` tests and fixtures
- `refactor:` internal restructuring without behavior change
- `chore:` tooling, dependencies, or repository maintenance

## Pull-request requirements

A pull request should include:

- The user problem being solved.
- The intended behavior and explicit non-goals.
- Files, schemas, or interfaces affected.
- Validation steps and test evidence.
- Security, privacy, migration, and compatibility impact.
- Documentation updates where behavior or scope changes.

Keep pull requests reviewable. Separate unrelated refactors, formatting changes, and feature work.

## AI-assisted contributions

AI tools may be used, but the contributor remains responsible for correctness, licensing, security, and test coverage. Disclose substantial generated code or documentation in the pull request and explain how it was reviewed.

## Review and merge

Maintainers may request smaller scope, additional fixtures, migration notes, or an architecture decision record. A change is ready to merge only when its behavior is reproducible and its documentation matches the repository state.

## Conduct

Be specific, technical, and respectful. Critique designs and evidence rather than people. Do not publish secrets, private project data, or vulnerability details in public discussions.