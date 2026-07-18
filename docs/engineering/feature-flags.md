# Feature Flags

## Purpose

Feature Flags enable controlled rollout of functionality without requiring deployments.

They reduce deployment risk and support experimentation.

---

## Use Cases

- Gradual Rollouts
- Beta Features
- Institution-specific Features
- Emergency Disable Switches
- A/B Experiments

---

## Principles

Flags should be temporary.

Every feature flag should have:

- Owner
- Purpose
- Creation Date
- Planned Removal Date

---

## Lifecycle

Created

↓

Enabled for Testing

↓

Limited Rollout

↓

General Availability

↓

Removed

---

## Rules

Feature Flags should not become permanent configuration.

Expired flags should be removed during normal development cycles.

Avoid deeply nested feature flag logic.
