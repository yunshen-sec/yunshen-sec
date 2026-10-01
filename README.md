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

## Project map

| Track | Public work | Evidence boundary |
| --- | --- | --- |
| Authorized penetration testing / red teaming | [ssrf-probe](https://github.com/Secx1/ssrf-probe) — authorized SSRF probe toolkit; [headerlint](https://github.com/Secx1/headerlint) — read-only HTTP header baseline checks | Explicit `--authorized` gate, scoped fixtures, and documented stop conditions; no production targets |
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
| [ssrf-probe](https://github.com/Secx1/ssrf-probe) | Authorized SSRF probes with response analysis and OAST fixtures | [repository](https://github.com/Secx1/ssrf-probe) | [![Stars](https://img.shields.io/github/stars/Secx1/ssrf-probe?style=flat)](https://github.com/Secx1/ssrf-probe) |
| [rebuff](https://github.com/Secx1/rebuff) | Prompt-injection detection research fork | [repository](https://github.com/Secx1/rebuff) | [![Stars](https://img.shields.io/github/stars/Secx1/rebuff?style=flat)](https://github.com/Secx1/rebuff) |

## Public references

- [ByteDance SRC public honor board](https://src.bytedance.com/honor) lists a
  public entry named **Secx** (UID 6530, Timeline Sec): #4 in the 2026 annual
  list and #4 in the overall list. **Secx is my public identity and research
  name; Timeline Sec is the corresponding public profile.** The ranking itself
  should still be read as the issuing page's current record and may change.
- [Tencent TSRC's April 2026 monthly board](https://security.tencent.com/index.php/thanks?month=4&ranktype=month&vulntype=all&year=2026)
  shows **Secx at #16**, with 804 contribution points and the platform title
  “资深安全研究员”.
- [Xunlei XLSRC's 2025 annual board](https://security.xunlei.com/thanks?timetype=year&year=2025)
  shows **Secx at #15**, with one accepted vulnerability and 15 contribution
  points. Both platform boards are time-scoped records and can change.
- [Huazhu SRC's public board](https://sec.huazhu.com/index.php?a=index&c=hall&m=)
  currently shows **Secx at #116** with 4 contribution points; this is a live
  board snapshot without a year label.
- [Baidu BSRC's 2023 annual-awards report](https://shadu.baidu.com/article/1851)
  names **secx** in the “迅捷狙击（年度高分漏洞）” award list. This is an
  award listing, not a numeric overall rank.
- A [publicly reposted profile](https://cn-sec.com/archives/1782851.html)
  records Secx as #2 in the 2022 Sangfor SRC annual board and #3 in the 2022
  Meizu SRC annual board; a [Ping An SRC event profile](https://www.ijiandao.com/2b/baijia/448962.html)
  independently describes Secx as a Sangfor SRC TOP2 white-hat. These two
  numeric placements are reported-source records, not currently linked to an
  official historical leaderboard page.
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
