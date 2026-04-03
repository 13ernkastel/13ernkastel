<!-- markdownlint-disable MD013 MD033 MD041 -->

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=130&color=0:0f172a,100:38bdf8&section=header&text=13ernkastel&fontColor=ffffff&fontSize=42&fontAlignY=36&desc=Upstream%20security%20fixes%20for%20AI%20agents%2C%20retrieval%2C%20and%20backend%20systems&descAlignY=60" alt="header"/>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=600&size=22&duration=3200&pause=800&color=38BDF8&center=true&vCenter=true&width=980&lines=I+work+on+agent-runtime+security%2C+retrieval+hardening%2C+and+backend+remediation;Current+repos%3A+NemoClaw%2C+OpenViking%2C+deer-flow%2C+and+CoPaw;I+turn+findings+into+tested+PRs%2C+CI+fixes%2C+and+clear+writeups" alt="typing intro"/>
</p>

<p align="center">
  <a href="https://github.com/pulls?q=is%3Apr+author%3A13ernkastel+is%3Amerged">
    <img src="https://img.shields.io/badge/merged-prs-1d4ed8?style=for-the-badge&logo=github&logoColor=white" alt="merged prs"/>
  </a>
  <a href="https://github.com/13ernkastel?tab=repositories">
    <img src="https://img.shields.io/badge/repos-0369a1?style=for-the-badge&logo=github&logoColor=white" alt="repositories"/>
  </a>
  <a href="https://www.linkedin.com/in/lennon-chia/">
    <img src="https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin"/>
  </a>
</p>

## What I Do

I work at the boundary between AI agents, backend systems, and security remediation.
Most of my work starts from a concrete bug, review comment, or disclosure draft and
ends in an upstream patch, regression tests, and a writeup that makes the fix easy to review.

## Current Focus

- Agent and sandbox hardening: shell execution, sandbox boundaries, onboarding safety, auth defaults, and config exposure.
- Retrieval and data-plane fixes: tags-based retrieval, task ownership boundaries, private-network SSRF, archive validation, and safer resource ingestion.
- Fix delivery: CI triage, lint cleanup, follow-up hardening, docs clarifications, and disclosure-ready remediation work.

## Main Tech

[![My Skills](https://skillicons.dev/icons?i=py,ts,js,nodejs,react,docker,linux,git,githubactions,bash,rust,postgres,sqlite)](https://skillicons.dev)

I spend most of my time in Python, JavaScript, and TypeScript codebases, usually around FastAPI-style backends, agent runtimes, retrieval systems, sandboxes, and CI pipelines.

## Current Public Work

| Repo | Focus | Link |
| --- | --- | --- |
| NVIDIA/NemoClaw | Harden sandbox command execution and align sandbox-name validation paths | [#1416](https://github.com/NVIDIA/NemoClaw/pull/1416) |
| NVIDIA/NemoClaw | Clarify security reporting path directly to NVIDIA PSIRT | [#1412](https://github.com/NVIDIA/NemoClaw/pull/1412) |
| NVIDIA/NemoClaw | Align published support statuses with the PRD and docs | [#1413](https://github.com/NVIDIA/NemoClaw/pull/1413) |
| volcengine/OpenViking | Restore cross-subtree retrieval with legacy schema compatibility | [#1205](https://github.com/volcengine/OpenViking/pull/1205) |
| bytedance/deer-flow | Fix unauthenticated memory disclosure and prompt poisoning | [#1648](https://github.com/bytedance/deer-flow/pull/1648) |
| agentscope-ai/CoPaw | Remove localhost API auth bypass | [#2840](https://github.com/agentscope-ai/CoPaw/pull/2840) |

## Selected Merged Fixes

| Repo | What shipped | Link |
| --- | --- | --- |
| volcengine/OpenViking | Fixed task API ownership leakage | [#1182](https://github.com/volcengine/OpenViking/pull/1182) |
| volcengine/OpenViking | Recovered stale commit state on current `main` for the opencode plugin | [#1187](https://github.com/volcengine/OpenViking/pull/1187) |
| bytedance/deer-flow | Critical host-shell escape remediation in `LocalSandboxProvider` | [#1547](https://github.com/bytedance/deer-flow/pull/1547) |
| volcengine/OpenViking | Enforced authentication on bot proxy chat endpoints | [#996](https://github.com/volcengine/OpenViking/pull/996) |
| volcengine/OpenViking | Rejected unsafe ZIP member paths during `.ovpack` import | [#344](https://github.com/volcengine/OpenViking/pull/344) |

## How I Work

- Reproduce the issue first instead of patching blindly.
- Fix the trust boundary, not just the immediate sink.
- Add regression coverage so the same failure does not come back in review or CI.
- Stay on the PR until comments are addressed and checks are green.

## GitHub Stats

<p align="center">
  <img height="165" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=13ernkastel&theme=github_dark" alt="GitHub stats"/>
  <img height="165" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=13ernkastel&theme=github_dark" alt="Top languages"/>
</p>

## Repos I Spend Time In

<p>
  <a href="https://github.com/NVIDIA/NemoClaw">
    <img src="https://img.shields.io/badge/NemoClaw-agent%20runtime%20%2F%20sandbox%20hardening-0f766e?style=for-the-badge&logo=github&logoColor=white" alt="NemoClaw"/>
  </a>
  <a href="https://github.com/volcengine/OpenViking">
    <img src="https://img.shields.io/badge/OpenViking-retrieval%20%2F%20backend%20security-111827?style=for-the-badge&logo=github&logoColor=white" alt="OpenViking"/>
  </a>
  <a href="https://github.com/bytedance/deer-flow">
    <img src="https://img.shields.io/badge/deer--flow-agent%20runtime%20%2F%20security-1f2937?style=for-the-badge&logo=github&logoColor=white" alt="deer-flow"/>
  </a>
  <a href="https://github.com/agentscope-ai/CoPaw">
    <img src="https://img.shields.io/badge/CoPaw-auth%20boundaries%20%2F%20service%20hardening-334155?style=for-the-badge&logo=github&logoColor=white" alt="CoPaw"/>
  </a>
</p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=110&color=0:38bdf8,100:0f172a&section=footer" alt="footer"/>
