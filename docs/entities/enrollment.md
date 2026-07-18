# Enrollment

## Definition

An Enrollment establishes that a Learner is participating in a specific learning context.

Enrollment connects Learners to educational experiences without embedding learning state.

---

## Enrollment Contexts

- Course
- Teaching Schedule
- Contest
- Program
- Learning Path

---

## Owns

- Enrollment Date
- Status
- Enrollment Source
- Completion Date

---

## Lifecycle

Requested

↓

Approved

↓

Active

↓

Completed

↓

Withdrawn

---

## Invariants

Enrollment belongs to one Learner.

Enrollment belongs to one learning context.

Historical enrollments remain available after completion.

---

## Future

Bulk enrollment.

Conditional enrollment.

Self-enrollment.

Enrollment recommendations.
