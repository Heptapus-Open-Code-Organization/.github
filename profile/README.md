# Heptapus Open Code Organization

Heptapus Open Code Organization exists to gather people who want to build, study, improve, and
maintain open-code systems.

We focus on projects that make computing more understandable, inspectable, and reusable: operating
systems, developer tools, education-oriented infrastructure, quantum/classical computing
experiments, and other systems where the source should be readable, discussable, and improvable by
a community.

## Community & Rules

Please read these before opening issues, pull requests, discussions, or project proposals:

| Document | Purpose |
|---|---|
| [Code of Conduct](https://github.com/Heptapus-Open-Code-Organization/.github/blob/main/CODE_OF_CONDUCT.md) | Community behavior, engineering ethics, unacceptable conduct, and enforcement. |
| [Contributing Guide](https://github.com/Heptapus-Open-Code-Organization/.github/blob/main/CONTRIBUTING.md) | How to start work, open issues, submit pull requests, and propose projects. |
| [Security Policy](https://github.com/Heptapus-Open-Code-Organization/.github/blob/main/SECURITY.md) | How to report vulnerabilities and handle security-sensitive work. |

Every repository may also have its own README, license, contribution notes, issue templates, and
architecture documents. Repository-specific rules override the organization defaults when they are
more precise.

## What We Aim To Do

- Build open-code projects with clear architecture, documentation, and reproducible workflows.
- Contribute to existing open-code ecosystems instead of working in isolation.
- Bring together developers, researchers, students, maintainers, designers, technical writers, and
  curious builders.
- Treat software as a shared craft: readable code, honest roadmaps, useful issues, and respectful
  review.
- Support experimental work while being clear about maturity, risks, and limitations.

## What Open Code Means Here

For us, open code means more than publishing a repository. It means:

- the code can be read and discussed;
- decisions are documented where possible;
- contribution paths are visible;
- issues describe real work, not vague wishes;
- maintainers are honest about what works, what is missing, and what is unsafe to rely on.

Some projects may use OSI open-source licenses. Others may use source-available or research-oriented licenses. Each repository must state its own license clearly.

## How We Work

We try to keep collaboration visible and traceable:

- roadmap-level work belongs in issues, work packages, project boards, or ADR-style notes;
- claims about hardware, performance, security, or production readiness need evidence;
- large technical decisions should explain why an option was chosen and what was deferred;
- pull requests should be small enough to review honestly;
- maintainers should close the loop by documenting what changed, what was verified, and what is
  still missing.

We welcome experimental projects, but experiments must be labeled as experiments. A prototype can
be valuable without pretending to be production software.

## Current Work

- [**QOS**](https://github.com/Heptapus-Open-Code-Organization/QOS): a Rust-based bare-metal
  operating system project with a first-class quantum control-plane direction.

More projects will be added as the organization grows.

## Community Principles

- Be precise, but be kind.
- Prefer evidence over ego.
- Make work visible: write issues, notes, ADRs, tests, and verification logs.
- Credit people accurately.
- Do not overstate project maturity.
- Keep security, privacy, and user trust in the foreground.
- Welcome beginners without lowering engineering standards.

## How To Join The Work

1. Pick a repository and read its README.
2. Check its license and maturity notes.
3. Look for issues labeled `good first issue`, `help wanted`, `type:wp`, or project-specific
   work-package labels.
4. Comment before taking a large issue so maintainers can confirm scope.
5. Open a focused pull request with verification notes.

If you want to propose a new project under this organization, prepare a short brief: purpose,
license, maintainers, expected users, current status, security considerations, and what kind of
contributors you are looking for.

## Maintainer Expectations

Maintainers are expected to:

- keep project status honest;
- use issue labels and milestones consistently;
- document architecture decisions when they affect contributors;
- protect contributors from harassment or bad-faith review;
- respect licenses and attribution;
- avoid merging hidden risky behavior, especially in infrastructure-like code.

## Contact

Use the relevant repository's issues or discussions for normal project work. Use the
[Security Policy](https://github.com/Heptapus-Open-Code-Organization/.github/blob/main/SECURITY.md)
for vulnerability reports or sensitive safety concerns.
