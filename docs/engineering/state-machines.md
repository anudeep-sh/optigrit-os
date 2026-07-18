# State Machines

## Purpose

State machines define the valid lifecycle of business entities.

Every state transition should be intentional, auditable and enforced by business rules.

Business entities should never move between arbitrary states.

---

# Course

Draft

↓

Under Review

↓

Published

↓

Archived

Allowed Transitions

Draft → Under Review

Under Review → Draft

Under Review → Published

Published → Archived

Archived → Published

---

# Teaching Schedule

Draft

↓

Scheduled

↓

Active

↓

Completed

↓

Archived

Rules

Completed schedules cannot return to Draft.

Archived schedules remain queryable.

---

# Lecture

Scheduled

↓

Started

↓

Completed

or

↓

Cancelled

Rules

Completed lectures cannot be restarted.

Attendance may only be recorded after a Lecture starts.

---

# Assessment

Draft

↓

Published

↓

Open

↓

Closed

↓

Evaluated

↓

Results Published

Rules

Questions cannot change after Open.

Evaluation begins only after Closed unless configured otherwise.

---

# Submission

In Progress

↓

Submitted

↓

Evaluated

↓

Published

Rules

Submitted work cannot be modified unless resubmission is explicitly allowed.

---

# Enrollment

Pending

↓

Approved

↓

Active

↓

Completed

or

↓

Withdrawn

Rules

Completed enrollments become read-only.

---

# Contribution

Submitted

↓

Under Review

↓

Approved

↓

Merged

or

↓

Rejected

Rules

Merged contributions cannot return to review.

Rejected contributions remain visible in history.

---

# Notification

Created

↓

Queued

↓

Delivered

↓

Read

or

↓

Expired

Rules

Delivery attempts remain auditable.

Read status is irreversible.

---

# Principle

Every business entity should explicitly define:

- Valid states
- Allowed transitions
- Transition rules
- Transition events

No implementation should invent additional states without updating this document.
