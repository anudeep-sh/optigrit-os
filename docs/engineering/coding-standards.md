# Coding Standards

## Purpose

Consistent code is easier to understand, review and maintain.

Coding standards exist to improve readability rather than enforce personal preferences.

---

## General Principles

- Prefer clarity over cleverness.
- Write code for future maintainers.
- Avoid premature optimization.
- Keep functions focused on a single responsibility.
- Eliminate dead code promptly.

---

## Naming

Business concepts should use business terminology.

Examples

Good

- Course
- Lecture
- Assessment
- Progress

Avoid technical or ambiguous names.

Examples

- DataObject
- Manager
- Helper
- MiscUtils

---

## Functions

Functions should:

- Perform one task.
- Be easy to read.
- Have descriptive names.
- Avoid hidden side effects.

---

## Classes

Classes should represent meaningful business concepts.

Avoid large utility classes with unrelated responsibilities.

---

## Comments

Code should be self-explanatory.

Comments should explain *why*, not *what*.

---

## Error Handling

Handle expected failures explicitly.

Unexpected failures should be logged with sufficient context.

---

## Code Reviews

Every review should verify:

- Business correctness.
- Readability.
- Test coverage.
- Performance implications.
- Security implications.
