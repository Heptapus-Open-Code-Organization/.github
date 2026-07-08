# Governance

Heptapus Open Code Organization is organized around maintainership, transparent review, and
project-level autonomy.

## Roles

### Organization Owner

The organization owner is responsible for:

- GitHub organization settings;
- repository creation and transfer approval;
- team/member permissions;
- final decisions when maintainers cannot resolve a governance issue;
- protecting the organization from abuse, license risk, or security risk.

### Organization Maintainer

Organization maintainers help operate the whole organization:

- review membership applications;
- review project proposals;
- maintain organization policies and issue templates;
- coordinate labels, boards, and recurring operations;
- enforce the Code of Conduct when needed.

### Project Maintainer

Project maintainers run a specific repository:

- review issues and PRs;
- maintain roadmap and documentation;
- keep project maturity claims honest;
- define repository-specific contribution rules;
- escalate security or conduct concerns.

### Contributor

Contributors participate through issues, PRs, docs, testing, design, research, security review, or
project discussion.

## Initial GitHub Teams

The initial organization teams are:

| Team | Purpose | Default repository access |
|---|---|---|
| `Organization Maintainers` | Organization governance, membership, policies, and operations. | `maintain` on `.github`. |
| `QOS Maintainers` | Maintainers responsible for the QOS repository. | `maintain` on `QOS`. |
| `Contributors` | General contributors who need direct contribution access after trust is established. | `push` on `QOS` when appropriate. |
| `Security Reviewers` | Trusted reviewers for security-sensitive reports and risky changes. | `triage` on `.github` and `QOS`. |

Access should remain least-privilege. Public issue and pull request contribution does not require
organization membership.

Organization defaults are configured for least privilege: default repository permission is `none`,
and members cannot create repositories unless an owner/maintainer creates or delegates that path.

## Decision Process

Small changes can be decided by the relevant project maintainer.

Large changes should have:

- an issue or proposal;
- clear scope and non-goals;
- acceptance criteria;
- verification plan;
- maintainer agreement;
- architecture notes or ADRs when long-term design is affected.

Use `docs/DECISION_PROCESS.md` for governance proposals, policy changes, and decision logging.
Important organization-level decisions should be recorded in `docs/DECISION_LOG.md`.

## Access Control

Access follows least privilege and should be granted through teams where possible.

Use `docs/ACCESS_CONTROL.md` for:

- access request flow;
- team permission expectations;
- offboarding;
- recommended organization security settings.

Use `docs/REPOSITORY_CREATION.md` before creating or transferring new repositories.

## Membership Decisions

Membership applications are reviewed through GitHub issues in the `.github` repository.

Review outcomes:

- `accepted`: applicant can be invited or assigned a contributor path;
- `declined`: application is not accepted now;
- `needs-private-followup`: public issue is insufficient or private context is needed;
- `needs-review`: waiting for maintainer action.

Declines should be brief and respectful. Maintainers do not need to debate private risk decisions
in public.

## Project Admission

A project can be accepted when it has:

- a clear purpose;
- license clarity;
- maintainers;
- expected users;
- contribution model;
- maturity/status statement;
- security and safety considerations;
- fit with the organization mission.

Accepted projects should start with the required repository baseline in `OPERATIONS.md`.

## Removal / Archival

A project may be archived, transferred, or removed from active status if:

- it has no maintainer capacity;
- its license or ownership is unclear;
- it violates organization policy;
- it creates unmanaged security or safety risk;
- it no longer fits the organization mission.

Archived projects should state why they are archived and whether future maintainers are welcome.
