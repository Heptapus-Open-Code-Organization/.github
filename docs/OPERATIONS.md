# Operations Handbook

This handbook describes what Heptapus Open Code Organization needs to stay operational.

## Operating Model

The organization runs through GitHub-first workflows:

- organization profile and policies live in `Heptapus-Open-Code-Organization/.github`;
- membership applications, project proposals, and community requests are GitHub issues;
- project work lives in repository issues, pull requests, milestones, and docs;
- security-sensitive reports follow `SECURITY.md` and may move to private channels;
- repository-specific rules override organization defaults when they are more precise.

## Operational Pillars

1. **Governance**
   - clear maintainer roles;
   - transparent acceptance/decline process for members and projects;
   - public policies for conduct, contribution, security, and project maturity.
2. **Community Intake**
   - membership application form;
   - project proposal form;
   - community request form;
   - labels and review states.
3. **Project Execution**
   - each project has README, license, contribution notes, issue templates, and roadmap;
   - issues include scope, non-goals, acceptance criteria, verification, and references;
   - large architectural choices are documented.
4. **Review & Quality**
   - PR review uses evidence, tests, logs, screenshots, and docs updates;
   - claims about hardware, security, or maturity require verification;
   - maintainers avoid merging hidden risky behavior.
5. **Security & Safety**
   - vulnerability reports are handled responsibly;
   - secrets are never posted in public issues;
   - infrastructure-like projects distinguish experimental and stable status.
6. **Continuity**
   - operational issues track recurring work;
   - maintainer handoff notes are public where possible;
   - inactive projects are archived or marked clearly.

## Weekly Maintainer Routine

- Review new membership applications.
- Review project proposals.
- Triage community/process issues.
- Check open security-sensitive reports or private follow-ups.
- Review stale issues and PRs in active repositories.
- Update project boards, labels, or milestones where they drift.
- Confirm README/project status claims still match reality.

## Monthly Maintainer Routine

- Review accepted/declined membership and project proposal patterns.
- Audit organization labels and issue templates.
- Check repository licenses and contribution guides.
- Review security policy and incident notes.
- Check whether any project should be archived, revived, or re-scoped.
- Publish a short organization status note if there is meaningful progress.

## Required Repository Baseline

Each organization repository should have:

- `README.md`;
- `LICENSE`;
- contribution guide or link to org `CONTRIBUTING.md`;
- code of conduct or link to org `CODE_OF_CONDUCT.md`;
- security policy or link to org `SECURITY.md`;
- issue templates;
- labels for area, type, priority, and status;
- clear maturity/status statement;
- maintainer list or ownership note;
- verification instructions.

## Operational Backlog

Track organization operations in the `.github` repository with labels:

- `ops`: operational setup or recurring process;
- `governance`: roles, policy, decision-making;
- `membership`: applications and member process;
- `project-proposal`: project intake;
- `security`: security policy and incidents;
- `docs`: organization documentation;
- `needs-review`: requires maintainer action.

