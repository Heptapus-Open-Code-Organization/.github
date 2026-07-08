# Decision Log

This log records organization-level governance decisions.

## 2026-07-08 - GitHub-first organization operations

Decision: Run membership applications, project proposals, community requests, and operational
tracking through GitHub issues in the `.github` repository.

Reason: Keeps the organization transparent, auditable, and easy for contributors to understand.

Follow-up: Add issue forms, labels, operations docs, and recurring triage issues.

## 2026-07-08 - Initial team model

Decision: Create initial teams:

- `Organization Maintainers`
- `QOS Maintainers`
- `Contributors`
- `Security Reviewers`

Reason: Access should be granted by role/team rather than ad hoc individual permissions.

Follow-up: Document least-privilege access policy and review organization settings.

## 2026-07-08 - Least-privilege organization defaults

Decision: Set default repository permission to `none` and disable member-created repositories.

Reason: Organization membership should not automatically grant repository access or repository
creation rights. Access should flow through project proposals, access requests, and maintainer
teams.

Follow-up: Keep 2FA strongly recommended; evaluate enforcement after maintainer readiness is
confirmed.
