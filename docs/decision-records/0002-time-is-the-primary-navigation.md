# ADR-0002

## Title

Time Is the Primary Navigation Model

---

## Status

Accepted

---

## Date

2026-06-15

---

## Context

Most Learning Management Systems organize navigation around modules.

Examples include:

- Courses
- Assessments
- Attendance
- Reports
- Resources

While technically logical, this does not match how teachers think during a working day.

Teachers rarely ask:

> "Which module should I open?"

Instead they ask:

- What am I teaching now?
- What is my next lecture?
- Which students need attention today?
- What work is pending this week?

The platform should reflect the user's mental model rather than the system's implementation.

---

## Decision

Time becomes the primary navigation model.

Instead of organizing the product around features, OptiGrit organizes the daily experience around teaching activities.

Examples:

Today

Tomorrow

This Week

Upcoming

Completed

History

Modules remain implementation details.

Time becomes the user experience.

---

## Consequences

### Positive

Teachers require less navigation.

Better contextual awareness.

Natural workflow.

Reduced cognitive load.

### Negative

Requires stronger contextual routing.

Requires cross-domain aggregation.

Requires richer scheduling services.

---

## Alternatives Considered

Module-first navigation.

Rejected.

Reason:

It optimizes software architecture rather than educator workflows.

---

## Long-Term Impact

Every future feature should integrate into the teacher's timeline before introducing additional navigation structures.
