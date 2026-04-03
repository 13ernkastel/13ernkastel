<!-- markdownlint-disable MD013 MD033 MD041 -->

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=130&color=0:0f172a,100:38bdf8&section=header&text=13ernkastel&fontColor=ffffff&fontSize=42&fontAlignY=36&desc=Merged%20upstream%20security%20and%20backend%20fixes&descAlignY=60" alt="header"/>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=600&size=22&duration=3200&pause=800&color=38BDF8&center=true&vCenter=true&width=980&lines=This+profile+shows+merged+fixes+only;Security%2C+auth%2C+retrieval%2C+archive%2C+and+runtime+hardening;Upstream+patches+with+tests+and+review-driven+follow-through" alt="typing intro"/>
</p>

<p align="center">
  <a href="https://github.com/pulls?q=is%3Apr+author%3A13ernkastel+is%3Amerged">
    <img src="https://img.shields.io/badge/merged-prs-1d4ed8?style=for-the-badge&logo=github&logoColor=white" alt="merged prs"/>
  </a>
  <img src="https://img.shields.io/badge/focus-security%20fixes-0f766e?style=for-the-badge" alt="security fixes"/>
  <img src="https://img.shields.io/badge/focus-auth%20%26%20retrieval-111827?style=for-the-badge" alt="auth and retrieval"/>
  <a href="https://www.linkedin.com/in/lennon-chia/">
    <img src="https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin"/>
  </a>
</p>

## Key Highlights

- Fixed a critical host-shell escape in `deer-flow` by hardening
  `LocalSandboxProvider`.
- Closed unauthenticated bot proxy access in `OpenViking`.
- Fixed task API ownership leakage in `OpenViking`.
- Mitigated stored XSS in `deer-flow` by enforcing safe downloads for active
  artifact content.
- Blocked unsafe `.ovpack` ZIP member paths during `OpenViking` import.
- Fixed stale commit-state recovery on current `main` in the `OpenViking`
  opencode plugin.

## Merged Fixes

| Issue Class | Repo | Merged PR |
| --- | --- | --- |
| Critical shell escape | bytedance/deer-flow | [#1547](https://github.com/bytedance/deer-flow/pull/1547) |
| Stored XSS hardening | bytedance/deer-flow | [#1389](https://github.com/bytedance/deer-flow/pull/1389) |
| Task ownership leakage | volcengine/OpenViking | [#1182](https://github.com/volcengine/OpenViking/pull/1182) |
| Unauthenticated bot proxy access | volcengine/OpenViking | [#996](https://github.com/volcengine/OpenViking/pull/996) |
| Unsafe archive import paths | volcengine/OpenViking | [#344](https://github.com/volcengine/OpenViking/pull/344) |
| Stale commit-state recovery | volcengine/OpenViking | [#1187](https://github.com/volcengine/OpenViking/pull/1187) |

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=110&color=0:38bdf8,100:0f172a&section=footer" alt="footer"/>
