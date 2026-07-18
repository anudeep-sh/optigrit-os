# API Guidelines

## Purpose

This document defines the principles for designing APIs across OptiGrit.

Consistency is more valuable than personal preference.

---

## Principles

APIs expose business capabilities, not database operations.

Prefer business language over technical language.

Examples

Good

- Publish Course
- Start Lecture
- Submit Assessment

Avoid

- Update Course Status
- Modify Lecture Row
- Save Submission Record

---

## Resource Design

Resources should represent business concepts.

Examples

- Courses
- Lectures
- Assessments
- Enrollments

Avoid exposing implementation details.

---

## Commands vs Queries

Commands change state.

Queries return information.

Queries must not produce side effects.

---

## Idempotency

Commands that may be retried must be idempotent.

Repeated requests should not create duplicate business actions.

---

## Versioning

Breaking changes require a new API version.

Backward-compatible additions should not require version changes.

---

## Error Responses

Errors should explain:

- What failed.
- Why it failed.
- How the caller may recover.

Avoid exposing internal implementation details.
