# Security Response Process

This document expands `SECURITY.md` into an operational maintainer process.

## Reporting Channels

Preferred channels:

1. Repository-specific private vulnerability reporting, when enabled.
2. Private maintainer contact if the report cannot be filed through GitHub.
3. Public issue only for non-sensitive security hardening requests.

Do not ask reporters to publish secrets, exploit chains, private logs, or credential material in
public issues.

## Initial Triage

Within the first maintainer response:

- [ ] acknowledge receipt;
- [ ] identify affected repository;
- [ ] identify whether the report is public or private;
- [ ] assign at least one responsible maintainer;
- [ ] classify rough severity;
- [ ] decide whether immediate containment is needed.

## Severity Guide

### Critical

- credential theft or leaked active secret;
- remote code execution in a supported deployment;
- malicious code/backdoor in repository or release artifact;
- vulnerability with active exploitation.

### High

- privilege boundary bypass;
- unsafe parsing of untrusted input in infrastructure-like code;
- serious supply-chain compromise;
- security claim shown to be false in a way that can harm users.

### Medium

- denial of service;
- non-default unsafe behavior;
- missing validation with limited impact;
- unclear but plausible security risk.

### Low

- documentation hardening;
- defense-in-depth;
- experimental-only issue with low user impact.

## Secret Leak Response

If a token, password, private key, or credential is posted:

1. Remove/redact public content when possible.
2. Rotate or revoke the secret immediately.
3. Check recent access logs if available.
4. Open a private follow-up for impact review.
5. Document that rotation happened without republishing the secret.

## Fix Process

- Keep exploit details private until safe to disclose.
- Prefer small, reviewable patches.
- Add regression tests or verification logs where possible.
- Credit reporters when they want credit.
- Publish a summary after fix if useful and safe.

## Disclosure Summary Template

```md
## Summary

Brief description without unnecessary exploit detail.

## Affected

- Repository:
- Versions/commits:
- Configurations:

## Impact

What could happen.

## Resolution

What changed.

## Reporter Credit

Credit if requested.

## Follow-up

Remaining hardening tasks.
```

