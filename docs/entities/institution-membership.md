# Institution Membership

## Definition

Institution Membership connects an Identity to an Institution.

It defines the user's participation within that Institution independently of academic responsibilities.

---

## Owns

- Institution
- Identity
- Membership Status
- Joined Date
- Exit Date
- Assigned Roles

---

## Relationships

Identity
1 ─────► N Institution Memberships

Institution
1 ─────► N Institution Memberships

Institution Membership
1 ─────► N Roles

---

## Invariants

An Identity may belong to multiple Institutions.

Membership history is preserved.

Institution removal does not remove Identity.

---

## Future

Cross-institution switching.

Organization federation.

Shared institutional access.
