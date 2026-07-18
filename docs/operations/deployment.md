# Deployment

## Purpose

Deployments should be predictable, repeatable and reversible.

Releasing software should not require manual changes to application code.

---

## Principles

Deploy small changes frequently.

Automate deployments wherever possible.

Rollback procedures should always exist.

---

## Environments

Development

Used for feature development.

---

Staging

Represents production as closely as possible.

Used for validation before release.

---

Production

Serves end users.

Only verified releases should reach production.

---

## Release Requirements

Before deployment:

- Tests pass.
- Migrations reviewed.
- Monitoring configured.
- Rollback plan verified.

---

## Rollback

Every deployment should have a documented rollback strategy.

Rollback procedures should be tested periodically.
