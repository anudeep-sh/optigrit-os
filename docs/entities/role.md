# Role

## Definition

A Role defines a collection of permissions granted within an Institution.

Roles describe capabilities rather than job titles.

---

## Examples

- Institution Administrator
- Faculty
- Teaching Assistant
- Learner
- Parent
- Department Head
- Reviewer

---

## Owns

- Name
- Description
- Permission Set
- Status

---

## Relationships

Institution Membership
N ─────► N Roles

Role
1 ─────► N Permissions

---

## Invariants

Roles are institution-scoped.

Permissions are additive unless explicitly denied.

Role definitions are versioned.

---

## Future

Custom roles.

Delegated administration.

Temporary roles.

Role templates.
