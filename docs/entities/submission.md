# Submission

## Definition

A Submission represents a learner's response to an Assessment.

It captures what was submitted, when it was submitted and how it was evaluated.

---

## Owns

- Learner
- Assessment
- Submission Time
- Submission Content
- Attempt Number
- Evaluation Status
- Score
- Feedback

---

## Lifecycle

Created

↓

Submitted

↓

Evaluated

↓

Published

↓

Archived

---

## Invariants

A Submission always belongs to one learner.

A Submission always belongs to one Assessment.

Submission history must be preserved.

Evaluations should remain traceable.

---

## Future

Versioned submissions.

Collaborative submissions.

Offline submissions.

AI-assisted evaluation metadata.
