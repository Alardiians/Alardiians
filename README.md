## Hi, I'm Alardiians

Security researcher. I find and report vulnerabilities in open source software, mostly authentication and authorization bugs in Go web backends. I also do bug bounty work.

### Published CVEs

| CVE | Project | Class | Lab + writeup |
|-----|---------|-------|---------------|
| [CVE-2026-44166](https://github.com/Alardiians/pocketbase-CVE-2026-44166) | PocketBase | OAuth2 account pre-hijacking | [repo](https://github.com/Alardiians/pocketbase-CVE-2026-44166) |
| [CVE-2026-28699](https://github.com/Alardiians/gitea-CVE-2026-28699) | Gitea | OAuth2 scope bypass via HTTP Basic auth | [repo](https://github.com/Alardiians/gitea-CVE-2026-28699) |

Every CVE repo ships a full writeup and a self-contained lab. The lab reproduces the bug against the real affected binary and then confirms the official patch closes it, so you can run the whole thing yourself in a couple of commands.

### What I look at

- OAuth2 and OIDC flows, and the places where two parts of a system disagree about identity or scope
- Authentication and authorization logic in general
- Source-level review of Go backends

### Notes on the labs

The repos are built to be reproducible, not just described. Each one pins the exact vulnerable and patched versions, scripts the attack end to end, and prints a clear pass or fail so the difference between the two builds is obvious.

If you want to dig in, start with the writeup in either repo and run the PoC from there.
