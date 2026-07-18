# Teaching Schedule

## Definition

A Teaching Schedule defines the planned delivery of a Course for a specific academic context.

It answers:

- Which Course will be taught?
- Who will teach it?
- To whom will it be taught?
- When will it be taught?

A Teaching Schedule represents intent. It does not record what actually happened during teaching.

---

## Owns

- Course Reference
- Faculty Assignment
- Academic Context
- Start Date
- End Date
- Planned Lectures
- Teaching Frequency
- Lesson Plan
- Schedule Status

---

## Never Owns

- Attendance
- Teaching Notes
- Lecture Discussions
- Student Progress
- Assessment Results

These belong to execution domains.

---

## Relationships

Course
1 ─────► N Teaching Schedule

Teaching Schedule
1 ─────► N Lecture

Teaching Schedule
N ─────► 1 Faculty

Teaching Schedule
N ─────► 1 Section

---

## Lifecycle

Draft

↓

Scheduled

↓

Active

↓

Completed

↓

Archived

---

## Invariants

Every Teaching Schedule references exactly one Course.

A Teaching Schedule belongs to one academic context.

Lectures are generated from the Teaching Schedule.

Changes to future lectures do not modify completed lectures.

---

## Future

AI-generated schedules.

Holiday-aware planning.

Automatic workload balancing.

Conflict detection.

Intelligent rescheduling.
