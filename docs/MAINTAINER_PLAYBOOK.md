# Maintainer Playbook

This playbook turns organization policy into daily maintainer actions.

## Reviewing Membership Applications

1. Check that the applicant accepted the required agreements.
2. Read contribution areas and relevant links.
3. Look for fit with current projects or future project needs.
4. Ask clarifying questions if needed.
5. Apply one of:
   - `accepted`;
   - `declined`;
   - `needs-private-followup`.
6. If accepted, invite the member with the least privilege needed.
7. Point them to a first issue, project, or maintainer contact.

## Reviewing Project Proposals

1. Confirm purpose and users are clear.
2. Confirm license is stated or license help is explicitly needed.
3. Confirm maintainers exist.
4. Confirm security/safety considerations are not empty.
5. Check whether the project duplicates an existing effort.
6. Ask for a minimal roadmap if the project is large.
7. Accept, decline, or request changes.

## Triage Rules

Use labels consistently:

- `needs-review`: maintainer action required;
- `accepted`: approved application/proposal;
- `declined`: not accepted now;
- `needs-private-followup`: move sensitive context private;
- `ops`: organization operations;
- `governance`: policy/roles/decision-making;
- `security`: security-sensitive process or report;
- `docs`: documentation work.

Close issues when the next action is complete and documented.

## Pull Request Review

Before merging, check:

- scope matches the issue or PR description;
- tests/logs/screenshots/manual verification are included where relevant;
- docs are updated for behavior or policy changes;
- no credentials or private data are committed;
- license and attribution are respected;
- risky code is clearly justified and reviewed.

## Inviting Members

Use least privilege:

- start with repository-level access where possible;
- grant organization-level roles only when operationally needed;
- prefer teams over direct individual permissions for repeated roles;
- remove stale access when people leave a project.

## Conduct Issues

For Code of Conduct concerns:

1. Preserve evidence.
2. Reduce immediate harm if needed.
3. Discuss with another maintainer when possible.
4. Apply a proportionate response.
5. Keep public explanations brief and respectful.
6. Do not expose private reporter details.

