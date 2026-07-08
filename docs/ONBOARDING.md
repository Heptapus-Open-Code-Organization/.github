# Onboarding

This document gives maintainers a repeatable path for accepted members.

## Accepted Member Flow

1. Add `accepted` label to the membership issue.
2. Leave a welcome comment.
3. Decide the access level:
   - no org access yet; start with public issues/PRs;
   - org membership only;
   - repository-level access through a team;
   - maintainer access after trust is established.
4. Point the member to a first repository or issue.
5. Link the Code of Conduct, Contributing Guide, and project docs.
6. Close the membership issue when the next step is clear.

## Welcome Comment Template

```md
Welcome to Heptapus Open Code Organization.

Thanks for applying and for sharing your contribution areas. Your application is accepted.

Suggested first steps:

- Read the Code of Conduct: https://github.com/Heptapus-Open-Code-Organization/.github/blob/main/CODE_OF_CONDUCT.md
- Read the Contributing Guide: https://github.com/Heptapus-Open-Code-Organization/.github/blob/main/CONTRIBUTING.md
- Pick a first issue labeled `good first issue`, `help wanted`, `type:wp`, or `type:gap`.
- Comment on the issue before starting if the scope is large.

Initial suggested area:

- <repo / issue / area>

Maintainers will use least-privilege access. Public contribution through issues and PRs does not
require elevated repository permissions.
```

## Decline Comment Template

```md
Thank you for applying to Heptapus Open Code Organization.

We are not accepting this application right now. This may be due to current maintainer capacity,
scope fit, missing context, or another organization-level concern.

You are still welcome to contribute publicly through issues and pull requests where repository
rules allow it.
```

## Private Follow-up Template

```md
Thank you for applying.

This application needs private maintainer follow-up before a decision can be made. Please do not
post private information, credentials, private contact details, or sensitive security context in
this public issue.
```

## First Contribution Paths

- **Code**: pick a scoped issue with acceptance criteria and verification notes.
- **Docs**: improve setup docs, issue clarity, architecture notes, or status wording.
- **Testing/QA**: reproduce issues, add logs/screenshots, validate hardware/VM matrix entries.
- **Design/UX**: propose UI improvements with screenshots, flows, and constraints.
- **Research/Architecture**: write ADR drafts, compare options, clarify trade-offs.
- **Security Review**: review parsing, driver, syscall, token, and networking boundaries.

