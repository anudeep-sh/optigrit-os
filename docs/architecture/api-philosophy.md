# API Philosophy

APIs expose business capabilities.

They do not expose database tables.

Every API should represent an educational action.

Good

Publish Course

Enroll Student

Start Lecture

Complete Assessment

Generate Analytics

Poor

Create Row

Update Table

Delete Record

The language of APIs should match the language of educators.

---

## Stability

Public APIs evolve slowly.

Breaking changes are expensive.

Prefer additive evolution.

Avoid removing fields.

Deprecate intentionally.

---

## Idempotency

Every operation that may be retried should be idempotent.

Attendance synchronization.

Notifications.

Payments.

Bulk imports.

AI automations.

Retries should never create duplicate business actions.

---

## Pagination

Every collection should support pagination.

Filtering.

Sorting.

Searching.

Expansion.

Consistency matters more than implementation.

Developers should know what to expect without reading documentation.
