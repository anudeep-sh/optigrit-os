# Attendance

## Definition

Attendance records learner participation in a Lecture.

Attendance belongs to the Teaching domain because it represents classroom execution.

---

## Attendance Types

- Present
- Absent
- Late
- Excused
- Partial

---

## Owns

- Lecture
- Student
- Attendance Status
- Recorded Time
- Recorded By
- Remarks

---

## Never Owns

Lecture Schedule.

Course.

Progress.

Attendance contributes to analytics but does not determine academic performance.

---

## Invariants

Attendance always belongs to one Lecture.

Attendance records remain historically accurate.

Bulk updates should preserve audit history.

---

## Future

Automatic attendance.

Face recognition integrations.

Location verification.

Bluetooth/NFC attendance.

Attendance confidence scoring.
