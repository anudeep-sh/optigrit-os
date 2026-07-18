# Discussion

## Definition

A Discussion is a structured academic conversation associated with a learning context.

Unlike Chat, which is conversational, Discussions are persistent, searchable and intended to build knowledge over time.

---

## Purpose

Discussions encourage collaborative learning by allowing students and faculty to ask questions, share ideas and resolve doubts within the context of a Course, Lecture or Assessment.

---

## Owns

- Title
- Description
- Context Reference
- Author
- Replies
- Reactions
- Tags
- Status
- Visibility

---

## Never Owns

- User Profiles
- Courses
- Assessments
- Learning Assets

---

## Relationships

Course
1 ─────► N Discussions

Lecture
1 ─────► N Discussions

Assessment
1 ─────► N Discussions

Discussion
1 ─────► N Replies

---

## Lifecycle

Open

↓

Active

↓

Resolved

↓

Archived

---

## Invariants

Every Discussion belongs to exactly one context.

Replies preserve chronological order.

Deleted replies remain recoverable through audit history.

Resolved Discussions remain searchable.

---

## Future

AI-generated answer suggestions.

Duplicate question detection.

Automatic topic classification.

Knowledge extraction into FAQs.
