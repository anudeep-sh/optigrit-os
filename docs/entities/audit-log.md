# Audit Log

## Definition

An Audit Log records significant business actions performed within the platform.

Audit Logs provide accountability, traceability and compliance.

---

## Records

- Actor
- Action
- Target Entity
- Timestamp
- Previous State Reference
- New State Reference
- Source

---

## Purpose

Support investigations.

Enable compliance.

Explain historical changes.

Restore confidence in business operations.

---

## Invariants

Audit Logs are append-only.

Audit Logs cannot be modified.

Business entities reference Audit Logs but do not own them.

---

## Future

Advanced search.

Compliance exports.

Anomaly detection.

AI-generated audit summaries.
