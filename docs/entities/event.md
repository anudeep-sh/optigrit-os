# Event

## Definition

An Event represents a scheduled occurrence that is not itself part of teaching execution.

Events coordinate institutional activities across the platform.

---

## Examples

- Faculty Meeting
- Orientation
- Workshop
- Seminar
- Holiday Activity
- Department Event

---

## Owns

- Title
- Description
- Schedule
- Organizer
- Participants
- Location
- Visibility

---

## Relationships

Institution
1 ─────► N Events

Calendar
1 ─────► N Events

---

## Invariants

Events are independent of Lectures.

Cancelling an Event preserves its historical record.

Participants are notified through the Communication domain.

---

## Future

Recurring events.

RSVP management.

AI agenda generation.

Calendar synchronization.
