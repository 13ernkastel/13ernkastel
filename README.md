# 13ernkastel

Merged upstream fixes in AI agent, backend, and runtime security.

## Key Highlights

- Fixed a critical host-shell escape in `deer-flow` by hardening `LocalSandboxProvider`.
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
