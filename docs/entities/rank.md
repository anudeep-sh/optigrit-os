# Rank

## Definition

A Rank represents a participant's relative position within a Contest based on its scoring rules.

Ranks are derived data and should always be reproducible.

---

## Owns

- Position
- Score
- Penalty
- Tie Break Information
- Calculated Time

---

## Relationships

Contest
1 ─────► N Ranks

Rank
N ─────► 1 Participant

---

## Invariants

Ranks are calculated from contest results.

Manual modification is prohibited.

Tie-breaking follows contest rules.

Historical rankings remain available after contest completion.

---

## Future

Department rankings.

Organization rankings.

Global rankings.

Skill-based rankings.
