# File

## Definition

A File represents binary content managed by the platform.

Files are infrastructure objects referenced by business entities.

They should never contain business logic.

---

## Supported Types

- Documents
- Images
- Videos
- Audio
- Archives
- Source Code
- Certificates

---

## Owns

- Storage Identifier
- File Name
- MIME Type
- Size
- Checksum
- Upload Time
- Owner
- Access Policy

---

## Relationships

Files may be referenced by:

- Courses
- Resources
- Tasks
- Messages
- Announcements
- Assessments
- User Profiles

---

## Invariants

Files are immutable after upload.

Replacing a File creates a new object.

Business entities reference Files rather than embedding binary content.

---

## Future

Content deduplication.

Virus scanning.

Lifecycle policies.

Automatic media optimization.
