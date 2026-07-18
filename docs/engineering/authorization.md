# Authorization

## Purpose

Authorization determines what an authenticated user is allowed to do.

Authentication answers **who** the user is.

Authorization answers **what** they may do.

---

## Model

Authorization is based on:

- Institution Membership
- Assigned Roles
- Permissions
- Business Context

---

## Examples

A Faculty member may:

- Publish course content they own.
- Conduct assigned lectures.
- Evaluate learner submissions.

A Department Head may additionally:

- Review teaching performance.
- Approve course changes.

---

## Principles

Permissions should be explicit.

Business services enforce authorization.

User interfaces improve usability but never provide security.

---

## Future

Support for attribute-based access control (ABAC).

Delegated administration.

Time-bound permissions.
