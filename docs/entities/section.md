# Section

## Definition

A Section is a logical grouping of Learning Assets within a Course.

Sections organize content for delivery without affecting curriculum or academic structure.

This entity is distinct from an academic Section (e.g., Section A, Section B).

---

## Owns

- Title
- Description
- Order
- Visibility
- Completion Rules

---

## Relationships

Course
1 ─────► N Sections

Section
1 ─────► N Learning Assets

---

## Invariants

Section ordering is unique within a Course.

Removing a Section does not delete its Learning Assets.

Learning Assets may be referenced by multiple Sections where appropriate.

---

## Future

Conditional sections.

Adaptive sequencing.

AI-generated sections.

Competency-based organization.
