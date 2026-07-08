# Access Control Policy

Access in Heptapus Open Code Organization follows least privilege.

## Principles

- Public contribution through issues and pull requests does not require organization membership.
- Organization membership does not automatically grant write access to every repository.
- Repository write access should be granted through teams whenever possible.
- Security-sensitive access should be rare, reviewed, and removable.
- Stale access should be removed when someone stops maintaining a project.

## Recommended GitHub Organization Settings

Recommended defaults:

- Default repository permission: `none`
- Members can create repositories: disabled by default
- Private vulnerability reporting: enabled per repository where available
- Discussions: enabled for organization/process discussion
- Two-factor authentication: recommended for all maintainers; required when the org can enforce it

Current enforced settings:

- Default repository permission: `none`
- Members can create repositories: disabled
- Organization Discussions: enabled

2FA is strongly recommended for all maintainers. Enforcing it organization-wide should be done only
after confirming every required maintainer can comply, to avoid accidental lockout.

## Team Access Model

| Team | Normal access |
|---|---|
| `Organization Maintainers` | `maintain` on `.github`; governance and operations work. |
| `QOS Maintainers` | `maintain` on `QOS`; project-level review and roadmap. |
| `Contributors` | Repository access only when direct push is intentionally needed. |
| `Security Reviewers` | `triage` or higher only where security review is needed. |

## Access Request Flow

1. Open an access request issue.
2. State repository, requested team/permission, reason, and expected duration.
3. Maintainer reviews least-privilege fit.
4. If accepted, add access through a team.
5. Record the decision in the issue.
6. Review temporary access on the stated end date.

## Offboarding Flow

- [ ] Remove repository/team permissions no longer needed.
- [ ] Reassign open issues/PRs if needed.
- [ ] Rotate shared credentials if the person had access.
- [ ] Update maintainer docs or ownership notes.
- [ ] Leave a respectful public note if appropriate.
