<p align="center">
  <img src="./assets/yunshen-banner.svg" alt="云深 · Yunshen — Security Engineering" width="100%">
</p>

<p align="center">
  <b>安全工程 · 防御性工具 · 可复现的证据</b><br>
  <sub>Security engineering — defensive tooling, reproducible evidence, authorized research.</sub>
</p>

<p align="center">
  <a href="https://code-workspace.top/"><img src="https://img.shields.io/badge/Blog-code--workspace.top-5eead4?style=flat-square&labelColor=0d1c2b" alt="Blog"></a>
  <a href="https://github.com/Secx1?tab=followers"><img src="https://img.shields.io/github/followers/Secx1?style=flat-square&label=Followers&labelColor=0d1c2b&color=2b4a5e" alt="Followers"></a>
  <a href="https://github.com/Secx1?tab=repositories"><img src="https://img.shields.io/github/stars/Secx1?affiliations=OWNER&style=flat-square&label=Stars&labelColor=0d1c2b&color=2b4a5e" alt="Stars"></a>
</p>

<br>

## 关于 · About

专注 Web 与基础设施的防御性安全研究：HTTP 安全基线、依赖供应链、网络流量排查。
我写的工具都很小、可以组合使用——默认只读、先在本地样本上跑通，并把授权边界和误报写清楚。

<sub>I build small, composable security tools for HTTP baselines, supply-chain visibility and network triage — read-only by default, tested on local fixtures first, explicit about authorization and false positives.</sub>

## 精选项目 · Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Secx1/headerlint">headerlint</a></h3>
      HTTP 安全响应头审计，支持 JSON / SARIF 输出，可直接接入 CI。<br>
      <sub>Safe HTTP security-header auditing with JSON and SARIF output.</sub><br><br>
      <img src="https://img.shields.io/badge/Python-0d1c2b?style=flat-square&logo=python&logoColor=5eead4" alt="Python">
      <a href="https://github.com/Secx1/headerlint/releases/tag/v0.1.0"><img src="https://img.shields.io/github/v/release/Secx1/headerlint?style=flat-square&labelColor=0d1c2b&color=2b4a5e&label=release" alt="Release"></a>
      <a href="https://github.com/Secx1/headerlint"><img src="https://img.shields.io/github/stars/Secx1/headerlint?style=flat-square&labelColor=0d1c2b&color=2b4a5e&label=%E2%98%85" alt="Stars"></a>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Secx1/lockwatch">lockwatch</a></h3>
      离线扫描依赖锁文件中的已知漏洞，可选对接 OSV 数据库。<br>
      <sub>Offline lockfile vulnerability triage with optional OSV output.</sub><br><br>
      <img src="https://img.shields.io/badge/Python-0d1c2b?style=flat-square&logo=python&logoColor=5eead4" alt="Python">
      <a href="https://github.com/Secx1/lockwatch/releases/tag/v0.1.0"><img src="https://img.shields.io/github/v/release/Secx1/lockwatch?style=flat-square&labelColor=0d1c2b&color=2b4a5e&label=release" alt="Release"></a>
      <a href="https://github.com/Secx1/lockwatch"><img src="https://img.shields.io/github/stars/Secx1/lockwatch?style=flat-square&labelColor=0d1c2b&color=2b4a5e&label=%E2%98%85" alt="Stars"></a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Secx1/dnswatch">dnswatch</a></h3>
      面向 Zeek DNS 日志的离线分析，每条告警都附带可解释的判定依据。<br>
      <sub>Offline, explainable heuristics for Zeek DNS logs.</sub><br><br>
      <img src="https://img.shields.io/badge/Python-0d1c2b?style=flat-square&logo=python&logoColor=5eead4" alt="Python">
      <a href="https://github.com/Secx1/dnswatch/releases/tag/v0.1.0"><img src="https://img.shields.io/github/v/release/Secx1/dnswatch?style=flat-square&labelColor=0d1c2b&color=2b4a5e&label=release" alt="Release"></a>
      <a href="https://github.com/Secx1/dnswatch"><img src="https://img.shields.io/github/stars/Secx1/dnswatch?style=flat-square&labelColor=0d1c2b&color=2b4a5e&label=%E2%98%85" alt="Stars"></a>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Secx1/ssrf-probe">ssrf-probe</a></h3>
      授权场景下的 SSRF 测试工具包：载荷生成、带外回连检测与响应分析。<br>
      <sub>Authorized SSRF testing: payload generation, out-of-band callback detection, response analysis.</sub><br><br>
      <img src="https://img.shields.io/badge/Python-0d1c2b?style=flat-square&logo=python&logoColor=5eead4" alt="Python">
      <a href="https://github.com/Secx1/ssrf-probe"><img src="https://img.shields.io/github/stars/Secx1/ssrf-probe?style=flat-square&labelColor=0d1c2b&color=2b4a5e&label=%E2%98%85" alt="Stars"></a>
    </td>
  </tr>
</table>

<sub>研究中的 fork · Studying: <a href="https://github.com/Secx1/rebuff">rebuff</a> — LLM prompt-injection detection.</sub>

## 工作原则 · Principles

<table>
  <tr>
    <td width="33%" valign="top"><b>默认只读</b><br><sub>Read-only by default. Tools observe and report; nothing changes the target.</sub></td>
    <td width="33%" valign="top"><b>本地样本优先</b><br><sub>Local fixtures first. Every check is reproducible offline before it touches a live system.</sub></td>
    <td width="33%" valign="top"><b>授权边界明确</b><br><sub>Explicit authorization. Only systems, logs and URLs I'm permitted to test.</sub></td>
  </tr>
</table>

## 方向 · Focus

<p>
  <img src="https://img.shields.io/badge/Python-0d1c2b?style=flat-square&logo=python&logoColor=5eead4" alt="Python">
  <img src="https://img.shields.io/badge/HTTP_Security-0d1c2b?style=flat-square" alt="HTTP security">
  <img src="https://img.shields.io/badge/Supply_Chain-0d1c2b?style=flat-square" alt="Supply chain">
  <img src="https://img.shields.io/badge/Zeek_%2F_DNS-0d1c2b?style=flat-square" alt="Zeek / DNS">
  <img src="https://img.shields.io/badge/SSRF_%2F_OAST-0d1c2b?style=flat-square" alt="SSRF / OAST">
  <img src="https://img.shields.io/badge/OSV-0d1c2b?style=flat-square" alt="OSV">
  <img src="https://img.shields.io/badge/SARIF-0d1c2b?style=flat-square" alt="SARIF">
</p>

## 交流 · Contact

欢迎提 Issue 和小而聚焦的 PR；测试请使用合成样本。技术文章见 [code-workspace.top](https://code-workspace.top/)。

<sub>Issues and focused pull requests are welcome — please use synthetic fixtures. See each project's <code>SECURITY.md</code> and <code>CONTRIBUTING.md</code>.</sub>

<br>

<p align="center"><sub>只在此山中，云深不知处。</sub></p>
