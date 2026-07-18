# Read Models

## Purpose

Read Models provide optimized representations of business data for querying.

They are projections of the source of truth.

Read Models never own business state.

---

## Characteristics

- Optimized for reads.
- Denormalized where appropriate.
- Disposable.
- Rebuildable.
- Eventually consistent.

---

## Examples

### Teacher Dashboard

Upcoming Lectures.

Pending Evaluations.

Unanswered Discussions.

Attendance Summary.

---

### Student Dashboard

Current Courses.

Upcoming Tasks.

Progress Summary.

Recent Announcements.

---

### Institution Dashboard

Enrollment Trends.

Teaching Workload.

Course Coverage.

Assessment Completion.

---

### Analytics Dashboard

Risk Indicators.

Learning Trends.

Teaching Performance.

Institution Metrics.

---

## Rules

Read Models never modify business entities.

Read Models are regenerated from events.

Business logic must never depend on Read Models.
