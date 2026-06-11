## Hi, I'm Alardiians

Security researcher. I find and report vulnerabilities in open source software, mostly authentication and authorization bugs in Go web backends. I also do bug bounty work.

### Published CVEs

| CVE | Project | Class | Lab + writeup |
|-----|---------|-------|---------------|
| [CVE-2026-44166](https://github.com/Alardiians/pocketbase-CVE-2026-44166) | PocketBase | OAuth2 account pre-hijacking | [repo](https://github.com/Alardiians/pocketbase-CVE-2026-44166) |
| [CVE-2026-28699](https://github.com/Alardiians/gitea-CVE-2026-28699) | Gitea | OAuth2 scope bypass via HTTP Basic auth | [repo](https://github.com/Alardiians/gitea-CVE-2026-28699) |

Each repo has a writeup and a lab you can run. The lab pins the exact vulnerable and patched versions, scripts the attack, and prints a clear pass or fail so the difference between the two builds is obvious.

### What I look at

- OAuth2 and OIDC flows, and the spots where two parts of a system disagree about identity or scope
- Authentication and authorization logic in general
- Source review of Go backends

Start with the writeup in either repo and run the PoC from there.
