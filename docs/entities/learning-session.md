# Learning Session

## Definition

A Learning Session represents a continuous period during which a learner actively engages with educational content.

It captures learning behaviour rather than completion.

---

## Owns

- Learner
- Start Time
- End Time
- Active Duration
- Learning Context
- Device Information
- Completion Status

---

## Purpose

Learning Sessions enable behavioural analytics by measuring engagement independently of academic progress.

---

## Relationships

Learner

↓

Learning Session

↓

Learning Assets

---

## Invariants

A Learning Session belongs to one learner.

Sessions cannot overlap for the same learner on the same device.

Inactive time should not contribute to active learning duration.

---

## Future

Attention tracking.

Session quality scoring.

Learning interruption analysis.

Cross-device continuation.
