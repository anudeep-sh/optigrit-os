# Task

## Definition

A Task is an actionable activity assigned to one or more learners.

Tasks focus on completing work rather than measuring performance.

Unlike Assessments, Tasks may or may not contribute to grading.

---

## Task Types

- Practice
- Reading
- Assignment
- Research
- Project
- Lab
- Reflection
- Custom

---

## Owns

- Title
- Description
- Instructions
- Due Date
- Priority
- Completion Rules
- Attachments

---

## Relationships

Course
1 ─────► N Tasks

Task
1 ─────► N Learner Assignments

Task
1 ─────► N Submissions

---

## Invariants

Tasks always belong to a learning context.

Tasks may exist without evaluation.

Completion is tracked independently from grading.

---

## Future

Recurring tasks.

AI-generated tasks.

Dependency-based tasks.

Personalized task recommendations.
