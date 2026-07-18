# Error Handling

## Purpose

Errors are part of normal system behaviour.

Every failure should be understandable, recoverable where possible, and observable.

---

## Categories

### Validation Errors

The request violates business rules.

Examples

- Missing required fields.
- Invalid state transition.
- Duplicate enrollment.

---

### Authorization Errors

The user is authenticated but lacks permission.

---

### Not Found

The requested business object does not exist or is inaccessible.

---

### Conflict

The request conflicts with the current business state.

Examples

- Publishing an already published course.
- Submitting after an assessment has closed.

---

### Infrastructure Errors

Failures caused by external dependencies.

Examples

- Storage unavailable.
- AI provider unavailable.
- Email service failure.

---

## Principles

Business failures should be expected.

Infrastructure failures should be retried when safe.

Every unexpected failure should be logged with sufficient context for investigation.
