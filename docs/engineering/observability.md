# Observability

## Purpose

Observability enables engineers to understand the behaviour of the platform in production.

The goal is to detect and resolve issues before they impact users.

---

## Pillars

### Logs

Capture meaningful business and technical events.

Avoid logging sensitive personal information.

---

### Metrics

Measure system health and business outcomes.

Examples

- API latency
- Queue depth
- AI response time
- Lecture completion rate

---

### Traces

Track requests across service boundaries.

Enable diagnosis of distributed workflows.

---

## Principles

Every production issue should be diagnosable.

Logs should include correlation identifiers.

Critical business events should be observable from end to end.

Operational dashboards should surface actionable information rather than raw telemetry.
