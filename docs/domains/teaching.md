# Teaching Domain

## Purpose

The Teaching domain represents the execution of education.

Knowledge defines what can be taught.

Planning defines what should be taught.

Teaching records what actually happened.

Teaching is always bound to time.

It cannot exist without context.

---

# Core Concepts

- Lecture
- Attendance
- Classroom Activity
- Discussion
- Announcements
- Teaching Notes
- Classroom Resources
- Live Session

---

# Responsibilities

The Teaching domain is responsible for:

- Conducting lectures
- Recording attendance
- Delivering learning material
- Facilitating classroom discussions
- Sharing announcements
- Capturing teaching observations
- Recording deviations from lesson plans

---

# Invariants

A Lecture always belongs to a Teaching Schedule.

Attendance always belongs to a Lecture.

Teaching Notes belong to a Lecture.

Announcements may belong to a Lecture or a Course.

Teaching never owns Courses.

Teaching never owns Students.

Teaching references them.

---

# Design Principles

Teaching should optimize for speed.

A teacher should be able to start a lecture in seconds.

Administrative actions should never interrupt classroom flow.

If information can be captured later without affecting integrity, defer it.

Teaching interfaces should prioritize focus over completeness.

---

# Future Evolution

AI-assisted lecture preparation.

Automatic attendance.

Real-time teaching recommendations.

Context-aware classroom summaries.

Automatic lecture documentation.

Teaching quality analytics.
