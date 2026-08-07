# Support

This policy applies to every repository in the `grep-the-flag`
organization: the Gameframework core, the SDK, the registry, and the
official templates.

## Getting help

| Need | Channel |
|---|---|
| Installation and operation | Quickstart and operator documentation in [gameframework](https://github.com/grep-the-flag/gameframework) |
| Bug reports and feature requests | GitHub Issues on the affected repository |
| SDK contract and minigame development | GitHub Issues on [gameframework-sdk](https://github.com/grep-the-flag/gameframework-sdk) |
| Registry admission (minigames, events, themes, language packs) | Submission process documented in [gameframework-registry](https://github.com/grep-the-flag/gameframework-registry) |
| Security vulnerabilities | [SECURITY.md](SECURITY.md) — never a public issue |

Before opening an issue, search existing open and closed issues. A useful
report names the version or commit, the deployment target (Compose or
Swarm), the expected behavior, the observed behavior, and the steps to
reproduce it.

## Support model and response times

Gameframework is an open-source project maintained on a **best-effort
basis**. Issues are triaged and answered as maintainer time permits.
There are **no guaranteed response times and no service-level
agreement**. Plan events on the assumption that no answer will arrive
while the event is running.

## Operational responsibility

Operators deploy and run Gameframework on their own infrastructure and
remain responsible for it, including during live events.

- **Preparation is the supported path.** Run the Phase 0 dry run, verify
  backups and a restore, and play the event through before the real
  date. The quickstart documents each step.
- **Registry content is reviewed and tested before admission.** That
  review is a content-quality and security gate, not an operational
  guarantee for any particular deployment.
- **There is no live operational support during events.** Anything that
  goes wrong is an issue like every other issue: report it, and it will
  be handled after the fact, best effort.
- **Data-protection duties remain with the operator** as the data
  controller of their event; the operator documentation describes the
  defaults the framework ships and the duties it cannot take over.

## Scope

Supported: the framework and its official deployment artifacts, the SDK
contract and validation, the official templates, and registry content as
admitted. Out of scope: modified forks, the infrastructure and network
of a specific deployment, and content installed from outside the
registry.
