# secx · security engineering

<p align="center"><img src="./assets/secx-banner.svg" alt="Secx security engineering banner" width="100%"></p>

[![Followers](https://img.shields.io/github/followers/Secx1?style=flat&label=Followers)](https://github.com/Secx1?tab=followers)
[![Total stars](https://img.shields.io/github/stars/Secx1?affiliations=OWNER&style=flat&label=Total%20stars)](https://github.com/Secx1?tab=repositories)
[![Public repositories](https://img.shields.io/badge/Public%20repositories-see%20GitHub-2ea44f)](https://github.com/Secx1?tab=repositories)

Security-focused tooling for defensive review, supply-chain visibility, and
network triage. Every project is designed to be read-only by default, safe to
run on local fixtures, and explicit about authorization and false positives.

## Project map / research tracks

- headerlint — Authorized penetration testing / red teaming：HTTP 安全头的只读基线验证。
- lockwatch — Vulnerability research and disclosure / Security tool development：Lockfile 与 OSV 的可审计扫描。
- dnswatch — Threat intelligence and malware analysis / Incident response and analytics：Zeek DNS 弱信号离线分诊。
- rebuff — CTF / lab / research environments：提示注入防守研究与实验室示例。

These mappings describe the defensive or lab scope of the repositories; they are not claims of unauthorized access or unverified real-world findings.

## How the projects fit together

The repositories are intentionally small and composable: `headerlint` produces
an HTTP baseline, `lockwatch` checks dependency evidence, and `dnswatch` adds
offline network-triage signals. Their reports can be reviewed independently or
attached to a single authorized assessment record. The profile links to live
repositories and releases; it does not mirror contribution totals or invent
activity.

The public work is organized around six authorized-use cases:

- **Authorized penetration testing / red teaming** — scoped validation with explicit stop conditions.
- **Vulnerability research and disclosure** — minimal reproduction, redacted evidence, and coordinated follow-up.
- **Threat intelligence and malware analysis** — defensive triage of authorized samples and telemetry.
- **Incident response and analytics** — timeline reconstruction, detection logic, and reviewable evidence.
- **Security tool development** — small read-only tools with fixtures, tests, and machine-readable output.
- **CTF / lab / research environments** — synthetic targets and reproducible learning exercises.

The current repositories and blog notes are defensive or lab-oriented examples; they do not claim unauthorized access, real-world findings, or unverified awards.

## Project map

The public repositories are organized around the six authorized-use tracks above:

| Track | Public work | Evidence boundary |
| --- | --- | --- |
| Authorized penetration testing / red teaming | [headerlint](https://github.com/Secx1/headerlint) — read-only HTTP header baseline checks | Scoped fixtures and documented stop conditions; no production targets |
| Vulnerability research and disclosure | [lockwatch](https://github.com/Secx1/lockwatch) — lockfile and advisory triage | Reproducible samples, redacted output, and coordinated follow-up guidance |
| Threat intelligence and malware analysis | [dnswatch](https://github.com/Secx1/dnswatch) — DNS telemetry weak-signal triage | Synthetic/authorized logs only; no claim of malware attribution |
| Incident response and analytics | [dnswatch](https://github.com/Secx1/dnswatch) — timeline-friendly DNS evidence | Offline analysis and reviewable JSON/table output |
| Security tool development | [headerlint](https://github.com/Secx1/headerlint), [lockwatch](https://github.com/Secx1/lockwatch), [dnswatch](https://github.com/Secx1/dnswatch) | Small defensive tools with fixtures and tests |
| CTF / lab / research environment | [rebuff](https://github.com/Secx1/rebuff) — prompt-injection defense lab | Synthetic lab scenarios; not a claim of unauthorized access |

### Public standing and verification

This profile does not publish an unverified ranking, award, bounty total, CVE count, or SRC position. Any future ranking or recognition will be listed only with the issuing program, scope, date, and a public evidence link. Repository stars, forks, followers, and contribution counts are platform metrics that change over time; they should be read directly on GitHub rather than treated as independent security credentials.

### CVP application readiness

The public portfolio is organized to document legitimate defensive use cases for Anthropic's Cyber Verification Program (CVP), not to claim enrollment or approval:

- identity and organization: use the real account/workspace and complete the provider's verification;
- six use cases: scoped testing, vulnerability research/disclosure, threat intelligence/sample analysis, incident response/analytics, security tool development, and CTF/lab research;
- evidence: read-only tools, synthetic fixtures, tests, JSON/SARIF output, redacted report templates, and explicit stop conditions;
- boundaries: no unauthorized targets, personal data, tokens, mass exfiltration, ransomware, or unverified findings.

See [Anthropic's official CVP guidance](https://support.claude.com/en/articles/14604842-real-time-cyber-safeguards-on-claude-opus-and-sonnet) for the current application path; the companion blog note keeps the checklist in one place. CVP access is provider-issued and organization-bound; this profile does not imply approval.

## Featured projects

| Project | Focus | Release | Live stars |
| --- | --- | --- | --- |
| [headerlint](https://github.com/Secx1/headerlint) | HTTP security-header auditing with JSON/SARIF output | [v0.1.0](https://github.com/Secx1/headerlint/releases/tag/v0.1.0) | [![Stars](https://img.shields.io/github/stars/Secx1/headerlint?style=flat)](https://github.com/Secx1/headerlint) |
| [lockwatch](https://github.com/Secx1/lockwatch) | Read-only dependency lockfile scanning with optional OSV lookup | [v0.1.0](https://github.com/Secx1/lockwatch/releases/tag/v0.1.0) | [![Stars](https://img.shields.io/github/stars/Secx1/lockwatch?style=flat)](https://github.com/Secx1/lockwatch) |
| [dnswatch](https://github.com/Secx1/dnswatch) | Offline Zeek DNS triage with explainable heuristics | [v0.1.0](https://github.com/Secx1/dnswatch/releases/tag/v0.1.0) | [![Stars](https://img.shields.io/github/stars/Secx1/dnswatch?style=flat)](https://github.com/Secx1/dnswatch) |
| [rebuff](https://github.com/Secx1/rebuff) | Prompt-injection detection research fork | [repository](https://github.com/Secx1/rebuff) | [![Stars](https://img.shields.io/github/stars/Secx1/rebuff?style=flat)](https://github.com/Secx1/rebuff) |

## Public references

- [ByteDance SRC public honor board](https://src.bytedance.com/honor) lists a
  public entry named **Secx** (UID 6530, Timeline Sec): #4 in the 2026 annual
  list and #4 in the overall list. I confirm that this is my public Secx /
  Timeline Sec identity; the ranking itself should still be read as the
  issuing page's current record and may change.
- [Tencent Cloud Developer Community interview](https://cloud.tencent.com/developer/article/2412642),
  published 2024-04-25, features “Secx” and Timeline Sec. Any ranking, bounty,
  or CVE details in that article are source-reported claims, not independently
  verified facts.

## Activity

GitHub owns the contribution graph and activity counts shown on the [profile
overview](https://github.com/Secx1?tab=overview). This page only links
to those live metrics; it does not mirror or manufacture contribution totals.

## Collaboration

Issues and focused pull requests are welcome. Please use synthetic fixtures
for tests and only analyze systems, logs, and URLs you are authorized to
inspect. See each project's `SECURITY.md` and `CONTRIBUTING.md` for details.
