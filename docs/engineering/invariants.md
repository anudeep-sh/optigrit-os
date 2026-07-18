# System Invariants

System invariants are truths that should remain valid regardless of implementation details.

Breaking an invariant is considered an architectural change.

---

# Academic

A Subject exists independently of Courses.

A Course always belongs to exactly one Subject.

Learning Assets are reusable.

Courses are reusable.

Knowledge is versioned.

Knowledge is never duplicated without justification.

---

# Planning

Teaching Schedules reference Courses.

Teaching Schedules never own Courses.

Lesson Plans belong to Teaching Schedules.

Planning records intent.

---

# Teaching

Lectures belong to Teaching Schedules.

Attendance belongs to Lectures.

Teaching Notes belong to Lectures.

Teaching records reality.

---

# Learning

Progress belongs to learners.

Progress is append-only.

Learning history should never be lost.

---

# Assessment

Submissions belong to learners.

Evaluation history is immutable.

Published Results remain auditable.

---

# Communication

Discussions preserve academic context.

Announcements remain referenceable.

Notifications should be idempotent.

---

# Analytics

Analytics consume events.

Analytics never become the source of truth.

---

# AI

Every AI action should be explainable.

Every AI recommendation should be reversible.

Every AI output should identify its source.

Teachers retain final authority.
