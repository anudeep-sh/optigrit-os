# Aggregates

## Purpose

Aggregates define transactional consistency boundaries.

Business rules that must always remain consistent belong within the same Aggregate.

Aggregates should be designed around business invariants rather than database relationships.

---

## Course Aggregate

### Aggregate Root

Course

### Contains

- Sections
- Learning Assets (references)
- Learning Outcomes (references)
- Course Versions

### Responsibilities

- Maintain course structure.
- Preserve content ordering.
- Validate publication requirements.
- Manage course lifecycle.

### Business Rules

A published Course must contain at least one Section.

Section ordering must remain unique.

Learning Assets are referenced, not owned.

---

## Teaching Schedule Aggregate

### Aggregate Root

Teaching Schedule

### Contains

- Lesson Plan
- Planned Lectures

### Responsibilities

- Manage teaching plans.
- Generate lectures.
- Validate scheduling.

### Business Rules

Schedules cannot overlap for the same faculty unless explicitly permitted.

Completed schedules become immutable.

---

## Lecture Aggregate

### Aggregate Root

Lecture

### Contains

- Attendance
- Teaching Notes
- Classroom Activities

### Responsibilities

- Record classroom execution.
- Maintain attendance consistency.
- Capture teaching outcomes.

### Business Rules

Attendance belongs only to one Lecture.

Teaching Notes cannot exist without a Lecture.

---

## Assessment Aggregate

### Aggregate Root

Assessment

### Contains

- Questions
- Evaluation Rules
- Rubrics

### Responsibilities

- Define evaluation.
- Control publication.
- Validate attempts.

### Business Rules

Published Assessments cannot modify evaluation behaviour.

Rubrics remain versioned.

---

## Submission Aggregate

### Aggregate Root

Submission

### Contains

- Files
- Evaluation
- Feedback

### Responsibilities

- Preserve learner work.
- Maintain evaluation history.

### Business Rules

Evaluation history is immutable.

Submission timestamps are authoritative.

---

## Principle

Prefer small Aggregates.

Cross-Aggregate consistency should be achieved using Domain Events.
