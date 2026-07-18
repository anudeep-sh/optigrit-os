# Course Version

## Definition

A Course Version is a snapshot of a Course at a specific point in time.

Versioning preserves educational history while allowing continuous improvement.

---

## Owns

- Version Number
- Publication Status
- Change Summary
- Published Date
- Author

---

## Relationships

Course
1 ─────► N Course Versions

Teaching Schedule
N ─────► 1 Course Version

---

## Invariants

Published versions are immutable.

Historical Teaching Schedules always reference the version used during delivery.

New versions never overwrite historical content.

---

## Future

Branching.

Draft versions.

Version comparison.

Approval workflow.
