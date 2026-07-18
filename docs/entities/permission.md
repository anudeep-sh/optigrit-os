# Permission

## Definition

A Permission authorizes a specific business action within the platform.

Permissions are expressed as actions rather than pages or menus.

---

## Examples

- course.publish
- course.edit
- lecture.start
- attendance.mark
- assessment.evaluate
- analytics.view
- institution.manage

---

## Owns

- Permission Key
- Description
- Domain
- Status

---

## Relationships

Role
1 ─────► N Permissions

---

## Invariants

Permissions are globally unique.

Business logic validates permissions.

User interfaces never determine authorization.

---

## Future

Attribute-based access control.

Policy engine integration.

Permission auditing.
