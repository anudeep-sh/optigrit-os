# ADR-0006

## Title

Separate Subject From Course

---

## Status

Accepted

---

## Context

Educational institutions define Subjects as part of their curriculum.

Teaching teams continuously improve how those Subjects are delivered.

Treating Subject and Course as the same concept prevents independent evolution.

---

## Decision

A Subject defines **what** is taught.

A Course defines **how** it is is taught.

Multiple Courses may exist for the same Subject.

Teaching Schedules always reference Courses, never Subjects directly.

---

## Consequences

Curriculum remains stable.

Teaching quality evolves independently.

Institutions preserve curriculum while encouraging instructional innovation.

---

## Alternatives Considered

Single Subject-Course entity.

Rejected because it tightly couples curriculum management with instructional design.
