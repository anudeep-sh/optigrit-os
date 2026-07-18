# Learner

## Definition

A Learner is an individual participating in one or more educational programs within an Institution.

A Learner represents an educational identity, independent of authentication or user accounts.

---

## Owns

- Learner Identifier
- Academic Status
- Enrollment History
- Academic Context
- Program Membership
- Batch Membership
- Section Membership

---

## Never Owns

- Authentication Credentials
- Permissions
- Messages
- Learning Content

These belong to Identity and other domains.

---

## Relationships

Learner
1 ─────► N Enrollments

Learner
1 ─────► N Learning Sessions

Learner
1 ─────► N Progress Records

Learner
1 ─────► N Submissions

---

## Invariants

A Learner belongs to one Institution.

Academic history is never deleted.

Changes to academic structure preserve historical records.

---

## Future

Cross-institution learner identity.

Lifelong learning profile.

Portable academic portfolio.
