<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=130&color=0:0f172a,100:38bdf8&section=header&text=13ernkastel&fontColor=ffffff&fontSize=42&fontAlignY=36&desc=Security%20research%20for%20AI%20agent%20systems%20and%20backend%20platforms&descAlignY=60" alt="header"/>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=600&size=22&duration=3200&pause=800&color=38BDF8&center=true&vCenter=true&width=980&lines=I+work+on+AI+agent+security%2C+retrieval%2C+and+backend+hardening;Contributor+to+OpenViking%2C+deer-flow%2C+NemoClaw%2C+and+Trae+Agent;I+ship+fixes%2C+tests%2C+and+disclosure-ready+writeups" alt="typing intro"/>
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

### What this reflects
I like work that starts with a concrete failure mode and ends with something another engineer can trust: a fix, a test, and a writeup that explains why the issue mattered. Most of what I do sits in the overlap between security research, backend systems, and AI agent infrastructure, where the hard part is usually not spotting risk but turning it into something reproducible and actionable.

I tend to focus on the places where agent systems quietly cross trust boundaries: shell execution, retrieval, memory, file handling, network access, auth, and the gaps between developer intent and runtime behavior. I care a lot about making those edges easier to reason about.

### What I contribute
- Security research and remediation for AI agent and developer platforms: host-shell escape, stored XSS, SSRF, prompt poisoning, command injection, path traversal, and unauthenticated API exposure.
- Retrieval and context-system work: search plumbing, tags-based cross-subtree retrieval, safer memory/resource access paths, and agent-facing RAG improvements.
- Backend hardening: auth boundaries, file handling, archive validation, network safeguards, and safer runtime defaults.
- Delivery work around fixes: focused tests, lint and CI cleanup, reproducible writeups, and remediation PRs.

### Main tech
[![My Skills](https://skillicons.dev/icons?i=py,ts,js,nodejs,react,docker,linux,git,githubactions,bash,rust,postgres,sqlite)](https://skillicons.dev)

I spend most of my time in Python, JavaScript, and TypeScript codebases, usually around FastAPI-style backends, agent runtimes, retrieval systems, sandboxes, and CI pipelines.

### GitHub stats
<p>
  <img height="170" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=13ernkastel&theme=github_dark" alt="GitHub stats"/>
  <img height="170" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=13ernkastel&theme=github_dark" alt="Top languages"/>
</p>

### Public contribution highlights
| Project | What I worked on | Link |
| --- | --- | --- |
| deer-flow | Critical host-shell escape remediation in `LocalSandboxProvider` | [#1547](https://github.com/bytedance/deer-flow/pull/1547) |
| deer-flow | Stored XSS mitigation for artifact rendering and download handling | [#1389](https://github.com/bytedance/deer-flow/pull/1389) |
| OpenViking | Enforced authentication on bot proxy chat endpoints | [#996](https://github.com/volcengine/OpenViking/pull/996) |
| OpenViking | Rejected unsafe ZIP member paths during `.ovpack` import | [#344](https://github.com/volcengine/OpenViking/pull/344) |
| deer-flow | Security review and safe download enforcement work in the fork-to-upstream fix path | [#2](https://github.com/13ernkastel/deer-flow/pull/2) |

### Security work
- Recent finding coverage includes deer-flow, OpenViking, Trae Agent, and FlowGram AI.
- Common issue classes in my reports: shell escape, XSS, SSRF, command injection, unsafe archive extraction, prompt poisoning, and unauthenticated management or chat APIs.
- I usually contribute a fix path, tests, and a disclosure-ready writeup rather than stopping at issue triage.

### Elsewhere
- LinkedIn: [linkedin.com/in/lennon-chia](https://www.linkedin.com/in/lennon-chia/)

### Current focus
- AI agent security reviews
- Retrieval and RAG engineering
- Backend API hardening
- Test and CI stabilization
- Security writeups and coordinated disclosure

### Repos I spend time in
<p>
  <a href="https://github.com/volcengine/OpenViking">
    <img src="https://img.shields.io/badge/OpenViking-context%20db%20%2F%20retrieval-111827?style=for-the-badge&logo=github&logoColor=white" alt="OpenViking"/>
  </a>
  <a href="https://github.com/bytedance/deer-flow">
    <img src="https://img.shields.io/badge/deer--flow-agent%20runtime%20%2F%20security-1f2937?style=for-the-badge&logo=github&logoColor=white" alt="deer-flow"/>
  </a>
  <a href="https://github.com/NVIDIA/NemoClaw">
    <img src="https://img.shields.io/badge/NemoClaw-secure%20OpenClaw%20runtime-0f766e?style=for-the-badge&logo=github&logoColor=white" alt="NemoClaw"/>
  </a>
  <a href="https://github.com/bytedance/trae-agent">
    <img src="https://img.shields.io/badge/Trae%20Agent-tooling%20%2F%20security-334155?style=for-the-badge&logo=github&logoColor=white" alt="Trae Agent"/>
  </a>
</p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=110&color=0:38bdf8,100:0f172a&section=footer" alt="footer"/>
