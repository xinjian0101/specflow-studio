# SpecFlow Studio Roadmap

Last reviewed: 2026-06-20

This roadmap separates repository presentation from implemented product behavior. A milestone is complete only when its exit criteria are met and documented.

## Phase 0 — Foundation

- [x] Define project positioning and non-goals.
- [x] Establish a public README and repository metadata guidance.
- [x] Record the initial product principles and planned workflow.
- [ ] Add contribution, security, and conduct policies.
- [ ] Create architecture decision record templates.
- [ ] Select the initial license after dependency review.

**Exit criteria:** project scope, governance, licensing direction, and first architecture proposal are publicly reviewable.

## Phase 1 — Workspace prototype

- [ ] Create the Tauri desktop shell.
- [ ] Add project creation and local workspace selection.
- [ ] Implement Idea and Clarification screens.
- [ ] Save and reopen project metadata.
- [ ] Add basic validation and error states.

**Exit criteria:** a user can create, save, close, and reopen a local project without data loss.

## Phase 2 — Specification and planning

- [ ] Define versioned specification schemas.
- [ ] Build structured specification and plan editors.
- [ ] Add acceptance-criteria and ambiguity checks.
- [ ] Add version history and readable diffs.
- [ ] Publish schema documentation and examples.

**Exit criteria:** specifications and plans are validatable, portable, and reviewable in Git.

## Phase 3 — Task graph and exports

- [ ] Add dependency-aware task management.
- [ ] Implement generic Markdown export.
- [ ] Implement at least three tool adapters.
- [ ] Preview exact generated files before writing.
- [ ] Add export fixtures and regression tests.

**Exit criteria:** the same approved project can be exported reproducibly to supported tool formats.

## Phase 4 — Packaging and preview release

- [ ] Add automated tests and packaging workflows.
- [ ] Publish Windows, macOS, and Linux preview builds.
- [ ] Add accessibility and keyboard-navigation review.
- [ ] Publish screenshots based on the real application.
- [ ] Open a structured preview-feedback cycle.

**Exit criteria:** signed or checksummed preview artifacts and release notes are publicly available.

## Phase 5 — Stable release

- [ ] Resolve preview blockers.
- [ ] Freeze the first stable project schema.
- [ ] Document migration and backup behavior.
- [ ] Publish security and support policies.
- [ ] Release version 1.0 with reproducible build instructions.

## Decision log

Major architecture, data-format, privacy, and licensing decisions will be captured as ADRs under `docs/adr/` once implementation begins.