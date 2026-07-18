# Configuration

## Purpose

Configuration allows environments to differ without changing application behaviour.

Business rules should never depend on environment-specific configuration.

---

## Configuration Sources

- Environment Variables
- Secret Managers
- Infrastructure Configuration
- Feature Flags

---

## Principles

Configuration should be:

- Explicit.
- Documented.
- Version controlled where appropriate.
- Validated during startup.

---

## Secrets

Secrets should never be stored in source control.

Examples

- API Keys
- Database Passwords
- Service Credentials
- Encryption Keys

---

## Validation

Application startup should fail fast if required configuration is missing.

---

## Environment Independence

Development, staging and production should differ only through configuration.
