# Result

## Definition

A Result represents the officially published outcome of an Assessment.

Results summarize evaluation but do not replace evaluation history.

---

## Owns

- Final Score
- Grade
- Published Date
- Publication Status
- Remarks

---

## Never Owns

Evaluation logic.

Submission content.

Rubrics.

Assessment definition.

---

## Relationships

Assessment

↓

Submission

↓

Evaluation

↓

Result

---

## Invariants

Published Results are immutable.

Corrections require explicit revision.

Historical Results remain available.

---

## Future

Outcome analytics.

Competency reports.

Institution benchmarking.

AI-generated performance summaries.
