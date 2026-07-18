# Service Map

## Purpose

This document defines the logical service boundaries of the OptiGrit platform.

These boundaries describe ownership, not deployment.

---

## Identity Service

Owns

- Identity
- Authentication
- Sessions
- Institution Membership

---

## Institution Service

Owns

- Institution
- Academic Structure
- Calendar

---

## Knowledge Service

Owns

- Subjects
- Courses
- Sections
- Learning Assets
- Resources
- Learning Outcomes

---

## Planning Service

Owns

- Teaching Schedules
- Lesson Plans

---

## Teaching Service

Owns

- Lectures
- Attendance
- Teaching Notes

---

## Learning Service

Owns

- Enrollments
- Learning Sessions
- Progress
- Competencies

---

## Assessment Service

Owns

- Assessments
- Question Banks
- Submissions
- Results

---

## Communication Service

Owns

- Chats
- Discussions
- Notifications
- Announcements

---

## Analytics Service

Owns

- Metrics
- Dashboards
- Recommendations

Consumes events from all other services.

---

## AI Service

Provides AI capabilities to all services.

Owns no primary business entities.
