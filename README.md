<div align="center">

<img src="https://raw.githubusercontent.com/Hartwell-Labs/.github/main/profile/assets/hartwell-logo.svg" alt="Hartwell Labs" width="640" />

<br>

**Security systems, languages and tools — built in the open.**

Independent engineering lab. No VC money, no telemetry, no dark patterns.
Every feature ships with tests and CI — or it doesn't ship.

</div>

---

## Products

### Security infrastructure

| | Project | What it does | Status |
|---|---|---|---|
| 🛡️ | [**talus-process-monitor**](https://github.com/Hartwell-Labs/talus-process-monitor) | Behavioral ransomware detection & response for Linux. eBPF-based, ~280k events/s, seccomp+Landlock self-sandboxing, single static binary. | ![Release](https://img.shields.io/github/v/release/Hartwell-Labs/talus-process-monitor?style=flat-square&color=F15A24) ![CI](https://img.shields.io/github/actions/workflow/status/Hartwell-Labs/talus-process-monitor/ci-ultra.yml?branch=master&style=flat-square&label=CI) ![CodeQL](https://img.shields.io/github/actions/workflow/status/Hartwell-Labs/talus-process-monitor/codeql.yml?branch=master&style=flat-square&label=CodeQL) |
| 🔐 | [**quantum-shield**](https://github.com/Hartwell-Labs/quantum-shield) | Post-quantum file encryption. ML-KEM-768 key encapsulation + AES-256-GCM. | ![CI](https://img.shields.io/badge/CI-local%20tests-6e7681?style=flat-square) |
| 🐧 | [**linux-aegis**](https://github.com/Hartwell-Labs/linux-aegis) | Linux kernel security module (LSM). | ![CI](https://img.shields.io/badge/CI-local%20tests-6e7681?style=flat-square) |
| 🛰️ | [**fortis**](https://github.com/Hartwell-Labs/fortis) | Chain-of-trust attestation for embedded systems (Rust, RISC-V). | ![CI](https://img.shields.io/badge/CI-local%20tests-6e7681?style=flat-square) |

### Developer tools

| | Project | What it does | Status |
|---|---|---|---|
| ⚡ | [**externum**](https://github.com/Hartwell-Labs/externum) | A typed language compiling to readable Python, Bash and native EXBC bytecode. 400+ tests, browser REPL. | ![Release](https://img.shields.io/github/v/release/Hartwell-Labs/externum?style=flat-square&color=F15A24) ![CI](https://img.shields.io/github/actions/workflow/status/Hartwell-Labs/externum/ci.yml?branch=main&style=flat-square&label=CI) ![CodeQL](https://img.shields.io/github/actions/workflow/status/Hartwell-Labs/externum/codeql.yml?branch=main&style=flat-square&label=CodeQL) |
| 🌌 | [**Aurora**](https://github.com/Hartwell-Labs/Aurora) | A complete operating system in the browser — kernel, window manager, VFS, apps. Zero dependencies. | ![CI](https://img.shields.io/github/actions/workflow/status/Hartwell-Labs/Aurora/ci.yml?branch=main&style=flat-square&label=CI) ![CodeQL](https://img.shields.io/github/actions/workflow/status/Hartwell-Labs/Aurora/codeql.yml?branch=main&style=flat-square&label=CodeQL) |

### Ruby division — bridges & registry

| | Project | What it does | Status |
|---|---|---|---|
| 🔀 | [**labbridge**](https://github.com/Hartwell-Labs/labbridge) | Rust ⇄ Ruby bridge: translate Hartwell Labs Rust to runnable Ruby, load Ruby plugins back into Rust via the `LabPlugin` trait. | ![CI](https://img.shields.io/github/actions/workflow/status/Hartwell-Labs/labbridge/ci.yml?branch=main&style=flat-square&label=CI) |
| 📦 | [**products**](https://github.com/Hartwell-Labs/products) | Products Registry — machine-readable index of our open-source products: repos, packages, containers. Ruby · Sinatra · MongoDB Atlas. | ![API](https://img.shields.io/badge/API-live-2cb67d?style=flat-square) |

### Offensive security

| | Project | What it does |
|---|---|---|
| 🗡️ | [**CyberForge**](https://github.com/Hartwell-Labs/CyberForge) | The tools we use in our own pentest labs: recon, packet analysis, hash cracking. |
| 🎯 | [**hack-the-lab**](https://github.com/Hartwell-Labs/hack-the-lab) | Break our products before someone else does. Challenges, CVE credits, Hall of Fame. |

## Engineering standards

```text
1. Code over claims        every feature ships with tests and CI, or it doesn't ship
2. Visibility is defense   you can't protect what you can't see — ask our eBPF hooks
3. Own your stack          zero dependencies where possible, auditable everywhere
4. Open by default         MIT licensed, issues welcome, egos are not
```

talus-process-monitor additionally runs: fuzzing, OpenSSF Scorecard, supply-chain
provenance (SLSA) and signed release artifacts.

## Packages & channels

All published artifacts live in public registries — one canonical location each:

| Product | PyPI | crates.io | npm | Container |
|---|---|---|---|---|
| **talus-process-monitor** | [talus-process-monitor](https://pypi.org/project/talus-process-monitor/) | [process-monitor](https://crates.io/crates/process-monitor) | — | [ghcr.io/hartwell-labs/talus-process-monitor](https://github.com/orgs/Hartwell-Labs/packages/container/package/talus-process-monitor) |
| **externum** | [externum](https://pypi.org/project/externum/) | — | — | — |
| **Aurora** | — | — | [aurora-os](https://www.npmjs.com/package/aurora-os) | — |

Elsewhere: [SourceForge — hartwell-labs](https://sourceforge.net/u/hartwell-labs/profile/) ·
[dev.to/bartoszosiej](https://dev.to/bartoszosiej) — build logs, benchmarks and post-mortems.

## Contact

- **Security reports / coordinated disclosure:** [bartosz.osiej2007@gmail.com](mailto:bartosz.osiej2007@gmail.com) — we acknowledge within 48h and credit reporters in each product's Hall of Fame.
- **Website:** [hartwell-labs.github.io](https://hartwell-labs.github.io)

<div align="center">
<br>
<sub>All software released under the MIT License unless stated otherwise.</sub>
</div>
