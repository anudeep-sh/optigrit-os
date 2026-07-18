# Academic Period

## Definition

An Academic Period represents a bounded interval within an academic calendar.

It provides the temporal context for planning, enrollment and reporting.

---

## Examples

- Academic Year
- Semester
- Trimester
- Quarter
- Summer Term

---

## Owns

- Name
- Start Date
- End Date
- Status
- Parent Calendar

---

## Relationships

Calendar
1 ─────► N Academic Periods

Academic Period
1 ─────► N Teaching Schedules

Academic Period
1 ─────► N Enrollments

---

## Invariants

Academic Periods do not overlap within the same Calendar unless explicitly configured.

Completed periods become read-only.

Historical references remain valid.

---

## Future

Rolling academic periods.

Institution-specific templates.

Automatic period transitions.
