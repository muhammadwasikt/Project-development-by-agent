# Development Workflow

## Phase 0 — Analysis

Before coding:

- Analyze entire project
- Understand architecture
- Identify dependencies
- Identify risks

No coding allowed before analysis.

---

## Phase 1 — Planning

Create or update:

docs/PROJECT_PLAN.md

For every feature define:

- Purpose
- Scope
- Dependencies
- Risks
- Test strategy

Coding cannot start until plan is updated.

---

## Phase 2 — Impact Analysis

Before modifying existing functionality:

Document:

### Current Behavior

Describe existing behavior.

### Proposed Behavior

Describe new behavior.

### Impact

List affected files.

### Risks

List possible regressions.

---

## Phase 3 — Implementation

Only after:

- Analysis complete
- Plan updated
- Impact analysis completed

Implementation rules:

- Reuse existing architecture
- Avoid duplication
- Keep modules isolated
- Preserve backward compatibility

---

## Phase 4 — Validation

Verify:

### Functional Tests

Feature works correctly.

### Regression Tests

Existing functionality still works.

### Edge Cases

- Empty input
- Invalid input
- Offline mode
- Permission denied
- Slow device

---

## Phase 5 — Documentation

Update:

- PROJECT_PLAN.md
- FUNCTION_REGISTRY.md
- DEV_LOG.md

Update KNOWLEDGE_BASE.md only if architecture or system behavior changes.

---

## Phase 6 — Final Report

Provide:

- Files modified
- Risks
- Validation results
- Documentation updates
