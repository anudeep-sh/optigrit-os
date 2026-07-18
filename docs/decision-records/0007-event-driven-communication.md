# ADR-0007

## Title

Prefer Event-Driven Communication Between Services

---

## Status

Accepted

---

## Context

Many business processes span multiple domains.

Forcing services to synchronously coordinate every operation increases coupling and reduces resilience.

---

## Decision

Services publish domain events when significant business changes occur.

Interested services subscribe and react independently.

Direct synchronous communication should be reserved for operations requiring immediate consistency.

---

## Consequences

Positive

- Lower coupling.
- Better scalability.
- Improved fault isolation.
- Easier addition of new capabilities.

Trade-offs

- Eventual consistency.
- More complex debugging.
- Need for idempotent event handlers.

---

## Alternatives Considered

Synchronous service-to-service communication for all interactions.

Rejected due to increased coupling and reduced resilience.
