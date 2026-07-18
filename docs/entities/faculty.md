# Faculty

## Definition

A Faculty member is an educator responsible for planning, delivering or evaluating learning experiences.

Faculty represent academic roles rather than authentication accounts.

---

## Owns

- Faculty Identifier
- Department
- Designation
- Academic Expertise
- Teaching Assignments

---

## Relationships

Faculty
1 ─────► N Teaching Schedules

Faculty
1 ─────► N Lectures

Faculty
1 ─────► N Assessments

Faculty
1 ─────► N Course Contributions

---

## Invariants

Faculty may contribute to multiple Courses.

Faculty ownership does not imply Course ownership.

Teaching history remains permanently associated with Faculty.

---

## Future

Expertise graph.

Faculty workload optimization.

AI teaching assistant preferences.

Contribution analytics.
