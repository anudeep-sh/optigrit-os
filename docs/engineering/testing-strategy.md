# Testing Strategy

## Purpose

Testing provides confidence that the platform behaves correctly as it evolves.

Testing should verify business behaviour rather than implementation details.

---

## Testing Pyramid

### Unit Tests

Verify business rules in isolation.

Examples

- Progress calculation.
- Grade computation.
- Permission validation.

---

### Integration Tests

Verify interactions between components.

Examples

- API to database.
- Event publishing.
- Authentication.

---

### End-to-End Tests

Verify complete user workflows.

Examples

- Course publication.
- Assessment submission.
- Lecture delivery.

---

## Principles

Tests should be:

- Fast.
- Reliable.
- Repeatable.
- Independent.

---

## Business Focus

Prioritize testing:

- Domain rules.
- State transitions.
- Permission enforcement.
- Event generation.
- Data integrity.

Avoid excessive testing of framework behaviour.

---

## Regression Testing

Every production bug should result in a regression test before the fix is merged.
