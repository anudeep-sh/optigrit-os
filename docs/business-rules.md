# Business Rules

## Purpose

This document captures the non-negotiable business rules that define how OptiGrit behaves.

Unlike implementation details, these rules represent product behavior and should remain consistent regardless of technology choices.

---

# Institution

- Every piece of academic data belongs to exactly one Institution.
- Institutions are completely isolated from one another.
- Institutions own their content and analytics.

---

# Subject

- A Subject represents curriculum.
- Subjects exist independently of Courses.
- Multiple Courses may teach the same Subject.

---

# Course

- A Course defines how a Subject is taught.
- Courses are versioned.
- Published Courses become immutable.
- A Course must contain at least one Section before publication.
- Learning Assets are referenced, not copied.

---

# Learning Assets

- Learning Assets are reusable.
- A Learning Asset may belong to multiple Courses.
- Updating a Learning Asset does not modify historical Course Versions.

---

# Planning

- Teaching Schedules are created from Courses.
- One Course may produce many Teaching Schedules.
- Planning always precedes Teaching.

---

# Teaching

- Lectures belong to exactly one Teaching Schedule.
- Attendance belongs to a Lecture.
- Teaching may continue even if learners miss individual Lectures.

---

# Learning

- Learning Progress is derived from learner activity.
- Progress is never edited manually.
- Completion depends on configurable completion criteria.

---

# Assessment

- Assessments belong to Courses.
- Questions belong to Question Banks.
- Question Banks are reusable.
- Submissions become immutable after submission unless resubmission is enabled.
- Published Results are immutable.

---

# Analytics

- Analytics never modify business data.
- Analytics are generated from business events.
- Analytics explain behaviour rather than define it.

---

# AI

- AI never becomes the source of truth.
- AI never modifies academic records directly.
- AI recommendations remain optional.
- Humans remain accountable for academic decisions.

---

# Communication

- Discussions belong to learning contexts.
- Notifications communicate events.
- Chat does not become institutional knowledge automatically.

---

# General

Every business action should be:

- Traceable.
- Auditable.
- Explainable.
- Recoverable where appropriate.
