## Valentino Paulon

Security researcher — privilege escalation, cloud-agent security, and source-level vulnerability research. I find real, exploitable, novel bugs and report them responsibly. I also build AI products and ship full-stack software.

**Portfolio:** https://m8seven.github.io/vm-portfolio/

### Security research

- **[CVE-2026-11837](https://access.redhat.com/security/cve/CVE-2026-11837)** — local privilege escalation in the `ansible.posix` `authorized_key` module (symlink-following chown). Reported and credited by Red Hat. [Writeup](https://github.com/M8seven/cve-2026-11837-ansible-posix-authorized-key).
- **[Captive Portal Security Analysis](https://github.com/M8seven/captive-portal-security-analysis)** — weak identity binding in MAC-based captive-portal auth, with MITRE ATT&CK mapping and mitigations. [DOI 10.5281/zenodo.19061528](https://doi.org/10.5281/zenodo.19061528).
- **[Cross-Provider Fact Mesh](https://github.com/M8seven/cross-provider-fact-mesh)** — zero-cost claim verification for multi-LLM systems. Defensive publication, [DOI 10.5281/zenodo.19061105](https://doi.org/10.5281/zenodo.19061105).
- Additional CVEs and **0-day privilege-escalation findings** in widely-used cloud agents and infrastructure tools are currently under coordinated disclosure with the respective vendors. Details are published as fixes ship.
- **Method**: systematic variant-analysis on recent security patches, plus source review in Go / Python / C / C++.

### AI & developer tooling

- **OneAnswerAI** — a multi-LLM fusion app (iOS/Android) that queries several models in parallel and reconciles their outputs into a single answer.
- **[claude-code-finish-protocol](https://github.com/M8seven/claude-code-finish-protocol)** — two-phase end-of-session system for agentic coding assistants. [DOI 10.5281/zenodo.19061530](https://doi.org/10.5281/zenodo.19061530).
- **[fixes-that-work](https://github.com/M8seven/fixes-that-work)** — tested, documented solutions to real networking and macOS problems.

### Consulting

Available for:

- **Security** — code security review, cloud/infrastructure assessment, targeted vulnerability research.
- **IT & software** — full-stack and mobile development, AI/LLM integration, technical architecture.

Remote-first, project-based. Reach me at **valentino.paulon88@gmail.com**.
