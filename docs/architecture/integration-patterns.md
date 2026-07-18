# Integration Patterns

## Purpose

Services interact through well-defined contracts.

The chosen integration pattern depends on business requirements rather than technical preference.

---

## Synchronous APIs

Use when an immediate response is required.

Examples

- Authentication
- Permission validation
- Course retrieval

---

## Domain Events

Use when multiple services react independently.

Examples

- Course Published
- Lecture Completed
- Result Published

---

## Background Jobs

Use for long-running operations.

Examples

- AI generation
- Report creation
- Data imports
- Bulk notifications

---

## Scheduled Jobs

Use for predictable recurring work.

Examples

- Reminder generation
- Analytics aggregation
- Calendar synchronization

---

## Principles

Prefer asynchronous communication when immediate consistency is unnecessary.

Avoid cyclic service dependencies.

Design integrations to tolerate retries.
