# Course

## Definition

A Course is a reusable learning experience.

It represents how a subject should be taught through a structured collection of learning assets.

A Course is independent of semesters, faculty, schedules and academic calendars.

It is designed once and delivered many times.

---

## Why It Exists

Educational content should improve over time.

Faculty should build upon existing work instead of recreating it every semester.

A Course allows institutions to preserve and continuously improve educational knowledge.

---

## Owns

- Metadata
- Sections
- Learning Assets
- Learning Outcomes
- Prerequisites
- Estimated Duration
- Version History

---

## Never Owns

- Students
- Faculty
- Attendance
- Teaching Schedule
- Semester
- Results
- Progress

Those belong to other domains.

---

## Relationships

Subject
    1 ─────► N Course

Course
    1 ─────► N Sections

Section
    1 ─────► N Learning Assets

Teaching Schedule
    N ─────► 1 Course

---

## Lifecycle

Draft

↓

Review

↓

Published

↓

Improved

↓

Archived

Courses should almost never be deleted.

Knowledge should be versioned.

---

## Invariants

A published Course must contain at least one Section.

Learning Assets are ordered.

Every Course belongs to exactly one Subject.

A Course may be delivered many times simultaneously.

---

## Future

Collaborative editing.

Faculty contributions.

Institution approval workflow.

AI-assisted course improvements.

Automatic prerequisite validation.
