# Identity

## Definition

Identity represents authentication and authorization within the platform.

It answers the question:

"Who is accessing OptiGrit?"

Identity is separate from educational roles such as Learner or Faculty.

A single Identity may participate in multiple Institutions with different roles.

---

## Owns

- Identity Identifier
- Authentication Provider
- Email
- Phone Number
- Verification Status
- Account Status
- Last Login

---

## Never Owns

- Academic Records
- Courses
- Progress
- Assessments
- Teaching Assignments

Identity authenticates users. Business domains authorize actions.

---

## Relationships

Identity
1 ─────► N Institution Memberships

Identity
1 ─────► N Sessions

---

## Invariants

Identity exists independently of Institutions.

Authentication and authorization remain separate concerns.

Removing Institution access does not remove Identity.

---

## Future

Single Sign-On.

Multi-factor Authentication.

Passkeys.

Federated Identity.
