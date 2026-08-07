# Security Policy

This policy applies to every repository in the `grep-the-flag`
organization.

## Reporting a vulnerability

Report vulnerabilities **privately** — never through a public issue:

1. **Preferred:** GitHub private vulnerability reporting — *Report a
   vulnerability* under the **Security** tab of the affected repository.
2. **Alternatively:** email `daniel@danielf.ch` with `SECURITY` in the
   subject line.

Include the affected repository and version or commit, an assessment of
the impact, and reproduction steps or a proof of concept where possible.

## What to expect

- Acknowledgement and triage on a best-effort basis; this is a
  volunteer-maintained project without response-time guarantees.
- Coordinated disclosure: please allow time for a fix or a documented
  mitigation before publishing details.
- There is no bug bounty program. Credit in the release notes is offered
  gladly.

## Supported versions

Before 1.0, only the latest release and the current `develop` state
receive security fixes. There are no backports.

## Scope notes

- **Malicious or vulnerable registry content** (minigames, events,
  themes, language packs) is a security report: admission review is the
  enforcement point, and an admitted entry can be pulled from the
  catalog.
- Findings that require an operator to disable documented hardening
  (running containers privileged, exposing the management network,
  sideloading unreviewed images) are treated as documentation issues
  rather than vulnerabilities.
- The v1 threat model deliberately excludes internet-facing deployment.
  Findings that only matter in that setting are still welcome; they are
  recorded for the hardening backlog.
