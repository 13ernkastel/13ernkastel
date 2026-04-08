<!-- markdownlint-disable MD013 MD033 MD041 -->

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=130&color=0:0f172a,100:38bdf8&section=header&text=13ernkastel&fontColor=ffffff&fontSize=42&fontAlignY=45" alt="header"/>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=600&size=22&duration=3200&pause=800&color=38BDF8&center=true&vCenter=true&width=980&lines=This+profile+shows+merged+external+fixes+only;Security%2C+auth%2C+retrieval%2C+and+runtime+hardening;Upstream+patches+with+tests+and+review-driven+follow-through" alt="typing intro"/>
</p>

<p align="center">
  <a href="https://github.com/pulls?q=is%3Apr+author%3A13ernkastel+is%3Amerged+-user%3A13ernkastel">
    <img src="https://img.shields.io/badge/external%20merged%20PRs-12-1d4ed8?style=for-the-badge&logo=github&logoColor=white" alt="external merged prs"/>
  </a>
  <a href="#public-cves">
    <img src="https://img.shields.io/badge/public%20CVEs%20on%20VulnCheck-5-b91c1c?style=for-the-badge" alt="public cves on vulncheck"/>
  </a>
  <img src="https://img.shields.io/badge/owners-4-0f766e?style=for-the-badge" alt="owners"/>
  <img src="https://img.shields.io/badge/repos-4-111827?style=for-the-badge" alt="repos"/>
  <a href="https://www.linkedin.com/in/lennon-chia/">
    <img src="https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin"/>
  </a>
</p>

I contribute upstream fixes across security, auth, retrieval, SSRF, CI/docs, and runtime-hardening work. This profile is a curated snapshot of merged external pull requests plus public VulnCheck CVEs credited under `Chia Min Jun Lennon`: no repositories owned by `13ernkastel`, no open PRs, and no closed-unmerged work.

## What I Optimize For

- Security and trust-boundary fixes that can land upstream with tests and maintainer review follow-through
- Root-cause patches that stay narrow in scope but remove real production risk
- Reviewable docs and CI guardrails that prevent regressions after the initial fix ships

## Snapshot

| Scope | Value |
| --- | --- |
| Snapshot date | 2026-04-08 |
| Total merged external PRs shown | 12 |
| Public CVEs on VulnCheck under `Chia Min Jun Lennon` | 5 |
| Organizations / accounts | 4 |
| Repositories | 4 |
| Main themes | Security fixes, auth hardening, retrieval, SSRF, docs CI, compatibility guidance, runtime stability |

## Public CVEs

The entries below are the public VulnCheck advisories currently credited under the exact name `Chia Min Jun Lennon`.

| CVE | Repository | Severity | Advisory | Fix PR |
| --- | --- | --- | --- | --- |
| [`CVE-2026-34430`](https://www.vulncheck.com/advisories/bytedance-deerflow-localsandboxprovider-host-bash-escape) | `bytedance/deer-flow` | High | LocalSandboxProvider host bash escape | [#1547](https://github.com/bytedance/deer-flow/pull/1547) |
| [`CVE-2026-32859`](https://www.vulncheck.com/advisories/bytedance-deerflow-stored-xss-via-inline-artifact-rendering) | `bytedance/deer-flow` | Medium | Stored XSS via inline artifact rendering | [#1389](https://github.com/bytedance/deer-flow/pull/1389) |
| [`CVE-2026-22207`](https://www.vulncheck.com/advisories/openviking-missing-root-api-key-allows-anonymous-root-access) | `volcengine/OpenViking` | Critical | Missing `root_api_key` allows anonymous root access | [#1132](https://github.com/volcengine/OpenViking/pull/1132) |
| [`CVE-2026-28518`](https://www.vulncheck.com/advisories/openviking-ovpack-import-zip-slip-path-traversal) | `volcengine/OpenViking` | High | `.ovpack` import ZIP Slip path traversal | [#344](https://github.com/volcengine/OpenViking/pull/344) |
| [`CVE-2026-34999`](https://www.vulncheck.com/advisories/openviking-bot-proxy-endpoints-allow-unauthenticated-access) | `volcengine/OpenViking` | Medium | Bot proxy endpoints allow unauthenticated access | [#996](https://github.com/volcengine/OpenViking/pull/996) |

## Selected Merged Work

| PR | Repository | Outcome |
| --- | --- | --- |
| [#1547](https://github.com/bytedance/deer-flow/pull/1547) | `bytedance/deer-flow` | Fixed a critical LocalSandbox host-shell escape and landed the upstream security patch. |
| [#1389](https://github.com/bytedance/deer-flow/pull/1389) | `bytedance/deer-flow` | Forced safe download behavior for active artifact MIME types to mitigate stored XSS. |
| [#1133](https://github.com/volcengine/OpenViking/pull/1133) | `volcengine/OpenViking` | Hardened HTTP resource ingestion against private-network SSRF. |
| [#996](https://github.com/volcengine/OpenViking/pull/996) | `volcengine/OpenViking` | Closed unauthenticated access to bot proxy chat endpoints. |
| [#1139](https://github.com/NVIDIA/NemoClaw/pull/1139) | `NVIDIA/NemoClaw` | Added pull-request docs link validation to catch broken markdown references before merge. |
| [#32](https://github.com/HKUDS/OpenHarness/pull/32) | `HKUDS/OpenHarness` | Fixed path-rule enforcement for file tools. |

## Coverage by Organization

| Organization / Account | Repos | Merged PRs | Highlights |
| --- | --- | --- | --- |
| `volcengine` | `OpenViking` | 6 | Bot auth hardening, `.ovpack` ZIP validation, SSRF hardening, retrieval tags, task ownership fix, opencode-plugin stability |
| `NVIDIA` | `NemoClaw` | 3 | Immutable symlink hardening status, docs CI guardrails, OpenShell lifecycle guidance |
| `bytedance` | `deer-flow` | 2 | Critical shell-escape fix and stored-XSS mitigation |
| `HKUDS` | `OpenHarness` | 1 | Path rule enforcement fix for file tools |

## Coverage by Repository

| Repository | Merged PRs | Contribution areas |
| --- | --- | --- |
| `volcengine/OpenViking` | 6 | Auth, SSRF, retrieval, task ownership, import validation, plugin stability |
| `NVIDIA/NemoClaw` | 3 | Runtime hardening visibility, docs CI, compatibility guidance |
| `bytedance/deer-flow` | 2 | Shell escape, stored XSS |
| `HKUDS/OpenHarness` | 1 | File-tool path rule enforcement |

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=110&color=0:38bdf8,100:0f172a&section=footer" alt="footer"/>
