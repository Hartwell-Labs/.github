<div align="center">

<img src="https://raw.githubusercontent.com/Hartwell-Labs/.github/main/profile/assets/hartwell-logo.svg" alt="Hartwell Labs" width="640" />

<br>

**Security systems, languages and tools — built in the open.**

Independent engineering lab. No VC money, no telemetry, no dark patterns.
Every feature ships with tests and CI — or it doesn't ship.

</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Hartwell-Labs/.github/main/profile/assets/terminal-dark.svg" />
  <img alt="Live terminal — Externum compiler, Talus eBPF agent, pqguard, supply-chain verification" src="https://raw.githubusercontent.com/Hartwell-Labs/.github/main/profile/assets/terminal-light.svg" width="100%" />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Hartwell-Labs/.github/main/profile/assets/org-dark.svg" />
  <img alt="Hartwell Labs — org stats" src="https://raw.githubusercontent.com/Hartwell-Labs/.github/main/profile/assets/org-light.svg" width="100%" />
</picture>

---

<br>

## Talus — eBPF ransomware detection

<img src="https://raw.githubusercontent.com/Hartwell-Labs/.github/main/profile/assets/talus-demo.gif" alt="Talus TUI detecting a mass-encryption process" width="820" />

[![stars](https://img.shields.io/github/stars/Hartwell-Labs/talus-process-monitor?style=flat-square&label=stars&color=F15A24)](https://github.com/Hartwell-Labs/talus-process-monitor)
[![license](https://img.shields.io/github/license/Hartwell-Labs/talus-process-monitor?style=flat-square)](https://github.com/Hartwell-Labs/talus-process-monitor)
[![CI](https://img.shields.io/github/actions/workflow/status/Hartwell-Labs/talus-process-monitor/ci-ultra.yml?branch=master&style=flat-square&label=CI)](https://github.com/Hartwell-Labs/talus-process-monitor/actions)
[![release](https://img.shields.io/github/v/release/Hartwell-Labs/talus-process-monitor?style=flat-square)](https://github.com/Hartwell-Labs/talus-process-monitor/releases)

**MIT detection engine. Response, dashboard and SIEM exporters are Enterprise.**

[hartwell-labs.pl/talus-process-monitor](https://hartwell-labs.pl/talus-process-monitor/)

<br>

## Products

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Hartwell-Labs/.github/main/profile/assets/rule-dark.svg" />
  <img alt="" src="https://raw.githubusercontent.com/Hartwell-Labs/.github/main/profile/assets/rule-light.svg" width="100%" />
</picture>

### Security infrastructure

| | Project | What it does | Status |
|---|---|---|---|
| 🛡️ | [**talus-process-monitor**](https://github.com/Hartwell-Labs/talus-process-monitor) | Behavioral ransomware detection & response for Linux. eBPF-based, ~280k events/s, seccomp+Landlock self-sandboxing, single static binary. | ![Release](https://img.shields.io/github/v/release/Hartwell-Labs/talus-process-monitor?style=flat-square&color=F15A24) ![CI](https://img.shields.io/github/actions/workflow/status/Hartwell-Labs/talus-process-monitor/ci-ultra.yml?branch=master&style=flat-square&label=CI) ![CodeQL](https://img.shields.io/github/actions/workflow/status/Hartwell-Labs/talus-process-monitor/codeql.yml?branch=master&style=flat-square&label=CodeQL) |
| 🔐 | [**quantum-shield**](https://github.com/Hartwell-Labs/quantum-shield) | Post-quantum file encryption. ML-KEM-768 key encapsulation + AES-256-GCM. | ![CI](https://img.shields.io/github/actions/workflow/status/Hartwell-Labs/quantum-shield/build-release.yml?branch=main&style=flat-square&label=CI) |
| 🔬 | [**labtrace**](https://github.com/Hartwell-Labs/labtrace) | Forensic timeline reconstruction and cross-process threat correlation for Linux audit telemetry. Rules + data-flow taint analysis, no agent required. | ![CI](https://img.shields.io/github/actions/workflow/status/Hartwell-Labs/labtrace/ci.yml?branch=main&style=flat-square&label=CI) |
| 🐧 | [**linux-aegis**](https://github.com/Hartwell-Labs/linux-aegis) | Linux kernel security module (LSM). | ![CI](https://img.shields.io/github/actions/workflow/status/Hartwell-Labs/linux-aegis/ci.yml?branch=main&style=flat-square&label=CI) |
| 🛰️ | [**fortis**](https://github.com/Hartwell-Labs/fortis) | Chain-of-trust attestation for embedded systems (Rust, RISC-V). | ![CI](https://img.shields.io/github/actions/workflow/status/Hartwell-Labs/fortis/ci.yml?branch=master&style=flat-square&label=CI) |

### Developer tools

| | Project | What it does | Status |
|---|---|---|---|
| ⚡ | [**externum**](https://github.com/Hartwell-Labs/externum) | A typed language compiling to readable Python, Bash and native EXBC bytecode. 382 tests, browser REPL. | ![Release](https://img.shields.io/github/v/release/Hartwell-Labs/externum?style=flat-square&color=F15A24) ![CI](https://img.shields.io/github/actions/workflow/status/Hartwell-Labs/externum/ci.yml?branch=main&style=flat-square&label=CI) ![CodeQL](https://img.shields.io/github/actions/workflow/status/Hartwell-Labs/externum/codeql.yml?branch=main&style=flat-square&label=CodeQL) |
| 🌌 | [**Aurora**](https://github.com/Hartwell-Labs/Aurora) | A complete operating system in the browser — kernel, window manager, VFS, apps. Zero dependencies. | ![CI](https://img.shields.io/github/actions/workflow/status/Hartwell-Labs/Aurora/ci.yml?branch=main&style=flat-square&label=CI) ![CodeQL](https://img.shields.io/github/actions/workflow/status/Hartwell-Labs/Aurora/codeql.yml?branch=main&style=flat-square&label=CodeQL) |

### Ruby division — bridges & registry

| | Project | What it does | Status |
|---|---|---|---|
| 🔀 | [**labbridge**](https://github.com/Hartwell-Labs/labbridge) | Rust ⇄ Ruby bridge: translate Hartwell Labs Rust to runnable Ruby, load Ruby plugins back into Rust via the `LabPlugin` trait. | ![CI](https://img.shields.io/github/actions/workflow/status/Hartwell-Labs/labbridge/ci.yml?branch=main&style=flat-square&label=CI) |
| 📦 | [**products**](https://github.com/Hartwell-Labs/products) | Products Registry — machine-readable index of our open-source products: repos, packages, containers. Ruby · Sinatra · MongoDB Atlas. | ![API](https://img.shields.io/badge/API-live-2cb67d?style=flat-square) |

### Intelligence & trust

| | Project | What it does | Status |
|---|---|---|---|
| 🛰️ | [**scryer-core**](https://github.com/Hartwell-Labs/scryer-core) | Intelligence platform — collection, correlation and enrichment over event streams. Self-hosted. | ![CI](https://img.shields.io/github/actions/workflow/status/Hartwell-Labs/scryer-core/ci.yml?branch=master&style=flat-square&label=CI) |
| ⛓️ | [**TrustNode**](https://github.com/Hartwell-Labs/TrustNode) | Solana-style validator in Rust: proof-of-history clock, Tower BFT, sealed accounts. | ![CI](https://img.shields.io/github/actions/workflow/status/Hartwell-Labs/TrustNode/ci.yml?branch=master&style=flat-square&label=CI) |

### Privacy & learning

| | Project | What it does | Status |
|---|---|---|---|
| 🧹 | [**photoscrub**](https://github.com/Hartwell-Labs/photoscrub) | Find what your photos leak — GPS, device serial, embedded thumbnails — before you upload them. Windows, one click. | ![build](https://img.shields.io/github/actions/workflow/status/Hartwell-Labs/photoscrub/build.yml?branch=master&style=flat-square&label=build) |
| 🎓 | [**edu**](https://github.com/Hartwell-Labs/edu) | Anvil — interactive labs for security, Python, Ruby and Rust. Runs in the browser (WASM), downloadable as a lab VM. | ![CI](https://img.shields.io/github/actions/workflow/status/Hartwell-Labs/edu/ci.yml?branch=main&style=flat-square&label=CI) |

<br>

### Offensive security

| | Project | What it does |
|---|---|---|
| 🗡️ | [**CyberForge**](https://github.com/Hartwell-Labs/CyberForge) | The tools we use in our own pentest labs: recon, packet analysis, hash cracking. |
| 🎯 | [**hack-the-lab**](https://github.com/Hartwell-Labs/hack-the-lab) | Break our products before someone else does. Challenges, CVE credits, Hall of Fame. |

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Hartwell-Labs/.github/main/profile/assets/pipeline-dark.svg" />
  <img alt="Animated supply-chain flow — git tag to signed images and registries" src="https://raw.githubusercontent.com/Hartwell-Labs/.github/main/profile/assets/pipeline-light.svg" width="100%" />
</picture>

## Engineering standards

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Hartwell-Labs/.github/main/profile/assets/rule-dark.svg" />
  <img alt="" src="https://raw.githubusercontent.com/Hartwell-Labs/.github/main/profile/assets/rule-light.svg" width="100%" />
</picture>

```text
1. Code over claims        every feature ships with tests and CI, or it doesn't ship
2. Visibility is defense   you can't protect what you can't see — ask our eBPF hooks
3. Own your stack          zero dependencies where possible, auditable everywhere
4. Open by default         MIT licensed, issues welcome, egos are not
```

talus-process-monitor additionally runs: fuzzing, OpenSSF Scorecard, supply-chain
provenance (SLSA) and signed release artifacts.

### Licensing

Every repository in this organisation is MIT licensed, with two exceptions worth
naming rather than burying:

- **scryer-core** is dual licensed — MIT, or
  [`LICENSE.commercial`](https://github.com/Hartwell-Labs/scryer-core/blob/master/LICENSE.commercial)
  if you want to embed it in a product or run it as a service.
- **linux-aegis** is GPL-2.0 WITH Linux-syscall-note, because it patches the
  kernel and the kernel's terms are the kernel's terms.

**Talus** is MIT in full here, and the response path, dashboard and SIEM
exporters are not in this repository at all — they are built from a private
crate. There is no flag that reaches them. What you can read here decides;
what acts is what a subscription covers.

## Contact

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Hartwell-Labs/.github/main/profile/assets/rule-dark.svg" />
  <img alt="" src="https://raw.githubusercontent.com/Hartwell-Labs/.github/main/profile/assets/rule-light.svg" width="100%" />
</picture>

- **General & business:** [contact@hartwell-labs.pl](mailto:contact@hartwell-labs.pl) · [business@hartwell-labs.pl](mailto:business@hartwell-labs.pl)
- **Security reports / coordinated disclosure:** [bartosz.osiej2007@gmail.com](mailto:bartosz.osiej2007@gmail.com) — we acknowledge within 48h and credit reporters in each product's Hall of Fame.
- **Website:** [hartwell-labs.pl](https://hartwell-labs.pl)

<div align="center">
<br>
<sub>All software released under the MIT License unless stated otherwise.</sub>
</div>
