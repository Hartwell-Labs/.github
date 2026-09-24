<div align="center">

<img src="https://capsule-render.vercel.app/api?type=hollow&color=0:F15A24,50:7f5af0,100:0d1117&height=150&section=header&text=HARTWELL%20LABS&fontSize=46&fontColor=F15A24&desc=security%20systems%2C%20languages%2C%20operating%20systems%20%E2%80%94%20built%20in%20the%20open&descSize=15&descAlignY=72&stroke=F15A24&strokeWidth=1" width="100%" alt="Hartwell Labs" />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=17&duration=3000&pause=1000&color=F15A24&center=true&vCenter=true&multiline=true&repeat=true&width=700&height=70&lines=%24+cat+%2Fetc%2Fhartwell%2Fmission;make+the+kernel+visible;make+the+toolchain+honest;ship+everything+as+open+source)](https://github.com/Hartwell-Labs)

[![GitHub Org's stars](https://img.shields.io/github/stars/Hartwell-Labs?style=flat-square&label=stars&color=F15A24)](https://github.com/Hartwell-Labs)
[![License](https://img.shields.io/badge/license-MIT-F15A24?style=flat-square)](https://github.com/Hartwell-Labs)
[![Website](https://img.shields.io/badge/site-hartwell--labs.github.io-7f5af0?style=flat-square)](https://hartwell-labs.github.io)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-2cb67d?style=flat-square)](https://github.com/Hartwell-Labs)
[![Made with](https://img.shields.io/badge/made%20with-Rust%20%C2%B7%20eBPF%20%C2%B7%20TypeScript-0d1117?style=flat-square)](https://github.com/Hartwell-Labs)

</div>

```text
$ whoami
┌──────────────────────────────────────────────────────────────────┐
│  independent lab — no VC money, no telemetry, no dark patterns   │
│  we ship tools we use ourselves, every feature carries tests     │
│  if it isn't observable, it isn't finished                       │
└──────────────────────────────────────────────────────────────────┘
```

## ⚗️ What we build

| Project | Stack | What you get |
|---|---|---|
| 🛡️ [**talus-process-monitor**](https://github.com/Hartwell-Labs/talus-process-monitor) | Rust · eBPF · Aya | Behavioral ransomware detection with auto-kill — ~280k events/s, seccomp+Landlock self-sandboxing, one static binary |
| ⚡ [**externum**](https://github.com/Hartwell-Labs/externum) | Python · self-hosted | A typed language compiling to Python, Bash **and** native EXBC bytecode — 400+ tests, browser REPL, built-in DRM |
| 🔐 [**quantum-shield**](https://github.com/Hartwell-Labs/quantum-shield) | Rust | Post-quantum file encryption — ML-KEM-768 + AES-GCM |
| 🌌 [**Aurora**](https://github.com/Hartwell-Labs/Aurora) | TypeScript · zero deps | A complete operating system in your browser — kernel, window manager, VFS, apps, `.aurora` state snapshots |
| 🐧 [**linux-aegis**](https://github.com/Hartwell-Labs/linux-aegis) | C | A Linux kernel security module |
| 🛰️ [**fortis**](https://github.com/Hartwell-Labs/fortis) | Rust · RISC-V | Chain-of-trust for embedded systems |

### 🧪 Ruby division — bridges & registry

| Project | Stack | What you get |
|---|---|---|
| 🔀 [**labbridge**](https://github.com/Hartwell-Labs/labbridge) | Ruby | Rust ⇄ Ruby bridge — translate Hartwell Labs Rust to runnable Ruby and Ruby plugins back to Rust (`LabPlugin` trait), targets verified against the Products Registry |
| 📦 [**products**](https://github.com/Hartwell-Labs/products) | Ruby · Sinatra · MongoDB Atlas | The Products Registry — machine-readable index of our open-source products: repos, packages and containers |

### 🗡️ Offensive side of the house

| Project | Stack | What you get |
|---|---|---|
| 🗡️ [**CyberForge**](https://github.com/Hartwell-Labs/CyberForge) | Python | Port scanner, packet analysis, hash cracking — the tools we use in our own pentest labs |
| 🎯 [**hack-the-lab**](https://github.com/Hartwell-Labs/hack-the-lab) | Shell | Hack our products before someone else does — challenges, CVE, Hall of Fame |

## 🧭 House rules

```bash
$ cat /etc/hartwell/rules

1. code over claims      # every feature ships with tests and CI, or it doesn't ship
2. visibility is defense # you can't protect what you can't see — ask our eBPF hooks
3. own your stack        # zero dependencies where possible, auditable everywhere
4. open by default       # MIT licensed, issues welcome, egos are not
```

## 📡 Current signal

- 🛡️ **talus** — eBPF pipeline hardening, more response actions
- ⚡ **externum** — source-to-source translation from Python & Rust into Externum
- 🔀 **labbridge** — growing the Ruby plugin surface

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=14&pause=1300&color=7A8BA0&center=true&vCenter=true&width=620&lines=%24+ssh+guest%40hartwell-labs;the+answer+is+42.+the+question+is+still+compiling.)](https://github.com/Hartwell-Labs)

</div>

---

<div align="center">

[![Org repos](https://img.shields.io/badge/%20-explore%20the%20labs-F15A24?style=for-the-badge&logo=github)](https://github.com/orgs/Hartwell-Labs/repositories)

</div>

<img src="https://capsule-render.vercel.app/api?type=hollow&color=0:0d1117,50:F15A24,100:7f5af0&height=110&section=footer&stroke=F15A24&strokeWidth=1" width="100%" alt="footer" />
