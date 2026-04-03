<!-- markdownlint-disable MD013 MD033 MD041 -->

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=130&color=0:0f172a,100:38bdf8&section=header&text=13ernkastel&fontColor=ffffff&fontSize=42&fontAlignY=36&desc=Merged%20upstream%20security%20and%20backend%20fixes&descAlignY=60" alt="header"/>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=600&size=22&duration=3200&pause=800&color=38BDF8&center=true&vCenter=true&width=980&lines=This+profile+only+shows+merged+fixes;Security%2C+auth%2C+retrieval%2C+archive%2C+and+runtime+hardening;Upstream+patches+with+tests+and+review-driven+follow-through" alt="typing intro"/>
</p>

<p align="center">
  <a href="https://github.com/pulls?q=is%3Apr+author%3A13ernkastel+is%3Amerged">
    <img src="https://img.shields.io/badge/merged-prs-1d4ed8?style=for-the-badge&logo=github&logoColor=white" alt="merged prs"/>
  </a>
  <a href="https://www.linkedin.com/in/lennon-chia/">
    <img src="https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin"/>
  </a>
</p>

## Key Highlights

- Closed a critical host-shell escape in `deer-flow` by hardening `LocalSandboxProvider` and tightening execution boundaries.
- Fixed unauthenticated and cross-owner access paths in `OpenViking`, including bot proxy endpoint exposure and task API ownership leakage.
- Hardened file and retrieval paths in `OpenViking`, including unsafe `.ovpack` ZIP imports and stale commit-state recovery on current `main`.
- Shipped browser-facing artifact download hardening in `deer-flow` to mitigate stored XSS in active content handling.

## Selected Merged Fixes

| Repo | Merged fix | Link |
| --- | --- | --- |
| bytedance/deer-flow | Critical host-shell escape remediation in `LocalSandboxProvider` | [#1547](https://github.com/bytedance/deer-flow/pull/1547) |
| bytedance/deer-flow | Enforced safe download for active artifact MIME types to mitigate stored XSS | [#1389](https://github.com/bytedance/deer-flow/pull/1389) |
| volcengine/OpenViking | Fixed task API ownership leakage | [#1182](https://github.com/volcengine/OpenViking/pull/1182) |
| volcengine/OpenViking | Enforced authentication on bot proxy chat endpoints | [#996](https://github.com/volcengine/OpenViking/pull/996) |
| volcengine/OpenViking | Rejected unsafe ZIP member paths during `.ovpack` import | [#344](https://github.com/volcengine/OpenViking/pull/344) |
| volcengine/OpenViking | Recovered stale commit state on current `main` for the opencode plugin | [#1187](https://github.com/volcengine/OpenViking/pull/1187) |

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=110&color=0:38bdf8,100:0f172a&section=footer" alt="footer"/>
