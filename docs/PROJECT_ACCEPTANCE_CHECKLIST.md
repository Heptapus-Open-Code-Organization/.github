# Project Acceptance Checklist

Use this checklist when reviewing a project proposal for Heptapus Open Code Organization.

## Proposal Completeness

- [ ] Project name is clear.
- [ ] Purpose is specific.
- [ ] Expected users are named.
- [ ] Current maturity is stated.
- [ ] Intended license is stated or license help is requested.
- [ ] Maintainers are named.
- [ ] Contribution model is described.
- [ ] Security/safety considerations are described.
- [ ] Existing repo/demo/docs links are included when available.

## Mission Fit

- [ ] The project fits open-code systems, infrastructure, education, research, developer tools,
      quantum/classical computing, or adjacent technical craft.
- [ ] The project benefits from being maintained in a shared organization.
- [ ] The project is not primarily a private/commercial delivery vehicle.
- [ ] The project does not create obvious unmanaged legal, security, or conduct risk.

## Maintainer Capacity

- [ ] At least one maintainer can be responsible for the project.
- [ ] Maintainers understand the organization Code of Conduct.
- [ ] Maintainers understand license and attribution requirements.
- [ ] Maintainers can review issues/PRs within a reasonable cadence.

## Repository Baseline

Before or immediately after acceptance, the project should have:

- [ ] `README.md`
- [ ] `LICENSE`
- [ ] `CONTRIBUTING.md` or link to organization guide
- [ ] `CODE_OF_CONDUCT.md` or link to organization policy
- [ ] `SECURITY.md` or link to organization policy
- [ ] issue templates
- [ ] labels for type, area, priority, status
- [ ] roadmap or first milestone
- [ ] maintainer ownership note
- [ ] verification/build/run instructions
- [ ] clear maturity/status statement

## Acceptance Outcomes

### Accept

Use when the proposal is clear, maintainable, and aligned.

Actions:

- add `accepted`;
- create or transfer repository;
- assign maintainer team;
- open bootstrap issues;
- close proposal when setup is complete.

### Request Revision

Use when the idea may fit but needs more detail.

Actions:

- keep `needs-review`;
- comment with missing fields;
- optionally add `needs-private-followup` if sensitive details are required.

### Decline

Use when the project does not fit or cannot be maintained safely.

Actions:

- add `declined`;
- explain briefly and respectfully;
- close proposal.

## Accepted Project Bootstrap Issues

Open these in the new repository when relevant:

1. `[docs] Complete repository baseline`
2. `[governance] Confirm project maintainers`
3. `[roadmap] Define first milestone`
4. `[security] Confirm security reporting path`
5. `[quality] Add build/test/verification workflow`

