# Notification

## Definition

A Notification informs a user that an event requiring awareness or action has occurred.

Notifications are event-driven and should always reference the originating business object.

---

## Categories

- Informational
- Reminder
- Warning
- Action Required
- Success
- Failure

---

## Owns

- Recipient
- Notification Type
- Title
- Message
- Priority
- Delivery Channels
- Read Status
- Source Reference

---

## Never Owns

Business data.

Notifications only reference business objects.

---

## Relationships

Domain Event

↓

Notification

↓

User

---

## Invariants

Notifications are immutable after delivery.

Duplicate notifications should be prevented.

Every notification references a source event.

---

## Future

Notification batching.

Digest notifications.

Priority learning.

User preference optimization.

AI-generated notification summaries.
