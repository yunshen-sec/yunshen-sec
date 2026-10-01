# Secx · security engineering

<p align="center"><img src="./assets/secx-banner.svg" alt="Secx security engineering banner" width="100%"></p>

<p align="center">
  <a href="https://github.com/Secx1?tab=followers"><img src="https://img.shields.io/github/followers/Secx1?style=for-the-badge&logo=github&label=followers" alt="GitHub followers"></a>
  <a href="https://github.com/Secx1?tab=repositories"><img src="https://img.shields.io/github/stars/Secx1?affiliations=OWNER&style=for-the-badge&logo=github&label=total%20stars" alt="Total repository stars"></a>
  <a href="https://github.com/Secx1?tab=repositories"><img src="https://img.shields.io/badge/repositories-public-2ea44f?style=for-the-badge" alt="Public repositories"></a>
</p>

<p align="center"><strong>Defensive security tooling · reproducible evidence · authorized research</strong></p>

<p align="center">
  <a href="#featured-projects">Projects</a> ·
  <a href="#six-research-tracks">Research tracks</a> ·
  <a href="#public-references">Public references</a> ·
  <a href="#collaboration">Collaboration</a>
</p>

<p align="center"><sub>Read-only by default · local fixtures first · explicit authorization boundaries</sub></p>

Security-focused tooling for defensive review, supply-chain visibility, and
network triage. Every project is designed to be read-only by default, safe to
run on local fixtures, and explicit about authorization and false positives.

## What this profile is about

The repositories are intentionally small and composable: `headerlint` produces
an HTTP baseline, `lockwatch` checks dependency evidence, and `dnswatch` adds
offline network-triage signals. Their reports can be reviewed independently or
attached to a single authorized assessment record. The profile links to live
repositories and releases; it does not mirror contribution totals or invent
activity.

The public work is organized around six authorized-use cases.

## Six research tracks

- **Authorized penetration testing / red teaming** — scoped validation with explicit stop conditions.
- **Vulnerability research and disclosure** — minimal reproduction, redacted evidence, and coordinated follow-up.
- **Threat intelligence and malware analysis** — defensive triage of authorized samples and telemetry.
- **Incident response and analytics** — timeline reconstruction, detection logic, and reviewable evidence.
- **Security tool development** — small read-only tools with fixtures, tests, and machine-readable output.
- **CTF / lab / research environments** — synthetic targets and reproducible learning exercises.

The repositories and notes are defensive or lab-oriented examples. They describe
methods, fixtures, and reviewable output rather than unauthorized access or
unverified real-world findings.

## Project map

| Track | Public work | Evidence boundary |
| --- | --- | --- |
| Authorized penetration testing / red teaming | [headerlint](https://github.com/Secx1/headerlint) — read-only HTTP header baseline checks | Scoped fixtures and documented stop conditions; no production targets |
| Vulnerability research and disclosure | [lockwatch](https://github.com/Secx1/lockwatch) — lockfile and advisory triage | Reproducible samples, redacted output, and coordinated follow-up guidance |
| Threat intelligence and malware analysis | [dnswatch](https://github.com/Secx1/dnswatch) — DNS telemetry weak-signal triage | Synthetic/authorized logs only; no claim of malware attribution |
| Incident response and analytics | [dnswatch](https://github.com/Secx1/dnswatch) — timeline-friendly DNS evidence | Offline analysis and reviewable JSON/table output |
| Security tool development | [headerlint](https://github.com/Secx1/headerlint), [lockwatch](https://github.com/Secx1/lockwatch), [dnswatch](https://github.com/Secx1/dnswatch) | Small defensive tools with fixtures and tests |
| CTF / lab / research environment | [rebuff](https://github.com/Secx1/rebuff) — prompt-injection defense lab | Synthetic lab scenarios; not a claim of unauthorized access |

### Public standing and verification

Any ranking or recognition shown here is tied to its issuing program, scope, date,
and public evidence link. Repository stars, forks, followers, and contribution
counts are platform metrics that change over time; they should be read directly
on GitHub rather than treated as independent security credentials.

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
GitHub's public stargazer list is now restricted, so the star badges above link
to each repository page rather than the `/stargazers` view.

## Collaboration

Issues and focused pull requests are welcome. Please use synthetic fixtures
for tests and only analyze systems, logs, and URLs you are authorized to
inspect. See each project's `SECURITY.md` and `CONTRIBUTING.md` for details.
