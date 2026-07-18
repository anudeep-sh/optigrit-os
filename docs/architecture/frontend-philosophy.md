# Frontend Philosophy

The frontend is not a collection of pages.

It is the visual representation of educational workflows.

Every screen should answer one question:

"What is the user trying to accomplish right now?"

Navigation should follow intent.

Not implementation.

---

## Screen Hierarchy

Institution

↓

Academic Context

↓

Teaching Context

↓

Action

Never begin with modules.

Always begin with context.

---

## Context Persistence

Users should never repeatedly provide information the platform already knows.

If a teacher is viewing a Lecture,

the platform already knows:

Course

Section

Faculty

Semester

Schedule

Navigation should preserve this context.

---

## Progressive Disclosure

Only show information required for the current task.

Reveal complexity gradually.

Reduce visual noise.

Avoid configuration-heavy interfaces.

---

## Performance

Speed influences trust.

Every interaction should feel immediate.

Loading indicators should communicate progress.

Background synchronization should reduce waiting.

The platform should remain usable under poor network conditions.
