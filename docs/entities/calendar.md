# Calendar

## Definition

A Calendar defines significant academic dates that influence planning and scheduling.

It provides institutional time boundaries rather than teaching activities.

---

## Owns

- Academic Year
- Terms
- Holidays
- Working Days
- Special Events
- Examination Windows

---

## Relationships

Institution
1 ─────► 1 Calendar

Calendar
1 ─────► N Academic Periods

Teaching Schedules reference the Calendar when generating planned activities.

---

## Invariants

Calendars are institution-specific.

Published Calendars remain versioned.

Historical Calendars remain available.

---

## Future

Regional holiday integration.

Conflict detection.

Automatic calendar generation.
