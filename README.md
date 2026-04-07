<!-- markdownlint-disable MD013 MD033 MD041 -->

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=130&color=0:0f172a,100:38bdf8&section=header&text=13ernkastel&fontColor=ffffff&fontSize=42&fontAlignY=45" alt="header"/>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=600&size=22&duration=3200&pause=800&color=38BDF8&center=true&vCenter=true&width=980&lines=This+profile+shows+merged+fixes+only;Security%2C+auth%2C+retrieval%2C+archive%2C+and+runtime+hardening;Upstream+patches+with+tests+and+review-driven+follow-through" alt="typing intro"/>
</p>

<p align="center">
  <a href="https://github.com/pulls?q=is%3Apr+author%3A13ernkastel+is%3Amerged">
    <img src="https://img.shields.io/badge/merged-prs%20only%20(15)-1d4ed8?style=for-the-badge&logo=github&logoColor=white" alt="merged prs only"/>
  </a>
  <img src="https://img.shields.io/badge/focus-security%20fixes-0f766e?style=for-the-badge" alt="security fixes"/>
  <img src="https://img.shields.io/badge/focus-auth%20%26%20retrieval-111827?style=for-the-badge" alt="auth and retrieval"/>
  <a href="https://www.linkedin.com/in/lennon-chia/">
    <img src="https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin"/>
  </a>
</p>

## Merged PR Policy

Everything below is merged PR data only.
Open PRs and closed-unmerged PRs are intentionally excluded.

## Contribution Snapshot

| Scope | Value |
| --- | --- |
| Total merged PRs shown | 15 |
| Organizations / accounts | 5 |
| Repositories | 7 |
| Main themes | Security fixes, auth hardening, retrieval, SSRF, archive validation, CI/docs, runtime stability |

## Merged Contributions by Organization

| Organization / Account | Repos | Merged PRs | Highlights |
| --- | --- | --- | --- |
| `volcengine` | `OpenViking` | 6 | Bot auth hardening, `.ovpack` ZIP validation, SSRF hardening, retrieval tags, task ownership fix, opencode-plugin stability |
| `13ernkastel` | `security-findings`, `OpenViking`, `deer-flow` | 4 | Archive maintenance and fork staging PRs for upstream security work |
| `NVIDIA` | `NemoClaw` | 2 | Immutable symlink hardening status and docs CI guardrails |
| `bytedance` | `deer-flow` | 2 | Critical shell-escape fix and stored-XSS mitigation |
| `HKUDS` | `OpenHarness` | 1 | Path rule enforcement fix for file tools |

## Merged Contributions by Repository

| Repository | Merged PRs | Contribution areas |
| --- | --- | --- |
| `volcengine/OpenViking` | 6 | Auth, SSRF, retrieval, task ownership, import validation, plugin stability |
| `NVIDIA/NemoClaw` | 2 | Runtime hardening visibility, docs CI |
| `bytedance/deer-flow` | 2 | Shell escape, stored XSS |
| `13ernkastel/deer-flow` | 2 | Fork staging and security review support |
| `13ernkastel/security-findings` | 1 | Findings archive maintenance |
| `13ernkastel/OpenViking` | 1 | Fork staging for upstream auth fix |
| `HKUDS/OpenHarness` | 1 | File-tool path rule enforcement |

## Merged PR Index

| Merged | Repo | PR | Change |
| --- | --- | --- | --- |
| 2026-04-07 | `NVIDIA/NemoClaw` | [#1139](https://github.com/NVIDIA/NemoClaw/pull/1139) | `ci(docs): check changed markdown links on pull requests` |
| 2026-04-06 | `NVIDIA/NemoClaw` | [#1499](https://github.com/NVIDIA/NemoClaw/pull/1499) | `fix(security): surface immutable symlink hardening status` |
| 2026-04-05 | `HKUDS/OpenHarness` | [#32](https://github.com/HKUDS/OpenHarness/pull/32) | `[security]fix path rule enforcement for file tools` |
| 2026-04-05 | `13ernkastel/security-findings` | [#1](https://github.com/13ernkastel/security-findings/pull/1) | `[codex] add OpenHarness path rule bypass finding` |
| 2026-04-05 | `volcengine/OpenViking` | [#1133](https://github.com/volcengine/OpenViking/pull/1133) | `fix security: feat(resources): harden HTTP resource ingestion against private-network SSRF` |
| 2026-04-03 | `volcengine/OpenViking` | [#1187](https://github.com/volcengine/OpenViking/pull/1187) | `fix(opencode-plugin): recover stale commit state on current main` |
| 2026-04-03 | `volcengine/OpenViking` | [#1182](https://github.com/volcengine/OpenViking/pull/1182) | `fix: [Security] fix task API ownership leakage` |
| 2026-04-03 | `volcengine/OpenViking` | [#1162](https://github.com/volcengine/OpenViking/pull/1162) | `feat(retrieve): use tags metadata for cross-subtree retrieval` |
| 2026-03-29 | `bytedance/deer-flow` | [#1547](https://github.com/bytedance/deer-flow/pull/1547) | `[Security] Address critical host-shell escape in LocalSandboxProvider` |
| 2026-03-27 | `volcengine/OpenViking` | [#996](https://github.com/volcengine/OpenViking/pull/996) | `Fix Unauthenticated Access to Bot Proxy Endpoints (/bot/v1/chat, /bot/v1/chat/stream)` |
| 2026-03-26 | `bytedance/deer-flow` | [#1389](https://github.com/bytedance/deer-flow/pull/1389) | `fix(gateway): enforce safe download for active artifact MIME types to mitigate stored XSS` |
| 2026-03-26 | `13ernkastel/OpenViking` | [#1](https://github.com/13ernkastel/OpenViking/pull/1) | `Enforce authentication for bot proxy chat endpoints` |
| 2026-03-26 | `13ernkastel/deer-flow` | [#2](https://github.com/13ernkastel/deer-flow/pull/2) | `Force-download active artifact MIME types to mitigate XSS; add security review and tests` |
| 2026-03-26 | `13ernkastel/deer-flow` | [#1](https://github.com/13ernkastel/deer-flow/pull/1) | `Add SECURITY_REVIEW.md: XSS security review for artifact rendering` |
| 2026-02-28 | `volcengine/OpenViking` | [#344](https://github.com/volcengine/OpenViking/pull/344) | `Validate ovpack ZIP member paths during import and add tests to reject unsafe entries` |

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=110&color=0:38bdf8,100:0f172a&section=footer" alt="footer"/>
