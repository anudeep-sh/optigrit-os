# Repository Structure

## Purpose

This document defines the logical organization of the OptiGrit codebase.

The repository structure should reflect business domains rather than technical layers.

Developers should be able to locate functionality based on business ownership.

---

## Principles

- Organize code around business domains.
- Keep domain logic independent of infrastructure.
- Minimize coupling between domains.
- Shared libraries should remain small and stable.
- Business terminology should be consistent across the repository.

---

## Suggested Structure

```
src/
├── domains/
│   ├── knowledge/
│   ├── planning/
│   ├── teaching/
│   ├── learning/
│   ├── assessment/
│   ├── communication/
│   ├── analytics/
│   └── identity/
│
├── shared/
│   ├── auth/
│   ├── database/
│   ├── events/
│   ├── logging/
│   ├── storage/
│   └── utils/
│
├── infrastructure/
│
├── api/
│
└── bootstrap/
```

---

## Domain Structure

Each domain should own:

- APIs
- Services
- Business Rules
- Domain Events
- Commands
- Repositories
- Tests

A domain should not directly modify another domain's data.

---

## Principles

Shared code should exist only when genuinely shared.

Avoid creating "common" or "miscellaneous" modules without clear ownership.

Repository structure should evolve with the business, not with frameworks.
