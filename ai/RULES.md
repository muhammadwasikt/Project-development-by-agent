# Production Engineering Rules

## Mission

Build production-grade software only.

The objective is:

- Stability
- Maintainability
- Scalability
- Reliability
- Excellent UX

Never optimize for speed at the cost of quality.

---

# Forbidden

The following are strictly forbidden:

- Dummy code
- Fake implementations
- Mock business logic
- Placeholder functionality
- Unused code
- Dead code
- Duplicate code
- Temporary hacks
- Quick fixes without analysis
- Hidden side effects
- Unused imports
- Unused dependencies
- Hardcoded secrets
- Hardcoded credentials
- Hardcoded business values

---

# Required

Always:

- Use clean architecture
- Follow SOLID principles
- Create reusable components
- Keep code maintainable
- Keep code readable
- Add concise comments only when needed
- Write self-explanatory code

---

# UI/UX Requirements

Applications must be designed for non-technical users.

Requirements:

- Clear navigation
- Clear labels
- Human-friendly language
- Accessible controls
- Proper loading states
- Proper error states
- Empty states
- Responsive layouts
- Dark mode support

Forbidden:

- Developer terminology
- Confusing workflows
- Tiny touch targets
- Hidden actions
- Ambiguous icons

---

# Regression Protection

Never modify functionality without:

1. Understanding current behavior
2. Performing impact analysis
3. Identifying dependencies
4. Assessing regression risk

Existing functionality must remain operational unless explicitly changed.

---

# Self Review

Before finishing any task verify:

- No duplicate code
- No dead code
- No unused imports
- No unused dependencies
- No placeholder code
- No regression risks
- Documentation updated
- Logs updated
- Registry updated

If any item fails:

STOP and fix the issue.
