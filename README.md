<!-- BlackRoad SEO Enhanced -->

# tolluooth

> Part of **[BlackRoad OS](https://blackroad.io)** — Sovereign Computing for Everyone

[![BlackRoad OS](https://img.shields.io/badge/BlackRoad-OS-ff1d6c?style=for-the-badge)](https://blackroad.io)
[![BlackRoad OS Inc](https://img.shields.io/badge/Org-BlackRoad-OS-Inc-2979ff?style=for-the-badge)](https://github.com/BlackRoad-OS-Inc)
[![License](https://img.shields.io/badge/License-Proprietary-f5a623?style=for-the-badge)](LICENSE)

**tolluooth** is part of the **BlackRoad OS** ecosystem — a sovereign, distributed operating system built on edge computing, local AI, and mesh networking by **BlackRoad OS, Inc.**

## About BlackRoad OS

BlackRoad OS is a sovereign computing platform that runs AI locally on your own hardware. No cloud dependencies. No API keys. No surveillance. Built by [BlackRoad OS, Inc.](https://github.com/BlackRoad-OS-Inc), a Delaware C-Corp founded in 2025.

### Key Features
- **Local AI** — Run LLMs on Raspberry Pi, Hailo-8, and commodity hardware
- **Mesh Networking** — WireGuard VPN, NATS pub/sub, peer-to-peer communication
- **Edge Computing** — 52 TOPS of AI acceleration across a Pi fleet
- **Self-Hosted Everything** — Git, DNS, storage, CI/CD, chat — all sovereign
- **Zero Cloud Dependencies** — Your data stays on your hardware

### The BlackRoad Ecosystem
| Organization | Focus |
|---|---|
| [BlackRoad OS](https://github.com/BlackRoad-OS) | Core platform and applications |
| [BlackRoad OS, Inc.](https://github.com/BlackRoad-OS-Inc) | Corporate and enterprise |
| [BlackRoad AI](https://github.com/BlackRoad-AI) | Artificial intelligence and ML |
| [BlackRoad Hardware](https://github.com/BlackRoad-Hardware) | Edge hardware and IoT |
| [BlackRoad Security](https://github.com/BlackRoad-Security) | Cybersecurity and auditing |
| [BlackRoad Quantum](https://github.com/BlackRoad-Quantum) | Quantum computing research |
| [BlackRoad Agents](https://github.com/BlackRoad-Agents) | Autonomous AI agents |
| [BlackRoad Network](https://github.com/BlackRoad-Network) | Mesh and distributed networking |
| [BlackRoad Education](https://github.com/BlackRoad-Education) | Learning and tutoring platforms |
| [BlackRoad Labs](https://github.com/BlackRoad-Labs) | Research and experiments |
| [BlackRoad Cloud](https://github.com/BlackRoad-Cloud) | Self-hosted cloud infrastructure |
| [BlackRoad Forge](https://github.com/BlackRoad-Forge) | Developer tools and utilities |

### Links
- **Website**: [blackroad.io](https://blackroad.io)
- **Documentation**: [docs.blackroad.io](https://docs.blackroad.io)
- **Chat**: [chat.blackroad.io](https://chat.blackroad.io)
- **Search**: [search.blackroad.io](https://search.blackroad.io)

---


> TollBooth — Sovereign VPN mesh. BlackRoad fork of WireGuard. Encrypted tunnel mesh across 7 nodes.

Part of the [BlackRoad OS](https://blackroad.io) ecosystem — [BlackRoad-OS-Inc](https://github.com/BlackRoad-OS-Inc)

---

# TollBooth — BlackRoad Road Fleet

> **Sovereign VPN mesh.** Fork of [WireGuard](https://www.wireguard.com/).

---

**TollBooth** is BlackRoad's sovereign fork of WireGuard tools — encrypted tunnel mesh connecting all 7 nodes across local network and cloud.

## What's Different

- **12/12 SSH connections** — full mesh verified
- **Hub-spoke topology** — Gematria + Anastasia as hubs
- **Auto-config** — pre-built configs for every node
- **BlackRoad mesh** — Internet → Gematria → WireGuard → Pi fleet

## Mesh Map

```
Internet
    ↓
Gematria (159.65.43.12) ←→ Anastasia (174.138.44.45)
    ↓ WireGuard               ↓ WireGuard
    ├── Alice (10.0.0.3)      ├── Alice
    ├── Cecilia (10.0.0.4)    ├── Cecilia
    ├── Octavia (10.0.0.5)    ├── Octavia
    ├── Aria (10.0.0.6)       ├── Aria
    └── Lucidia (10.0.0.7)    └── Lucidia
```

## Configuration

```bash
# Each node has /etc/wireguard/wg0.conf
wg-quick up wg0
wg show    # verify peers
```

## Upstream

Forked from [WireGuard/wireguard-tools](https://git.zx2c4.com/wireguard-tools) (GPL v2 upstream).
All BlackRoad modifications are proprietary.

---

**BlackRoad OS, Inc.** — Pave Tomorrow.

*Proprietary. All rights reserved.*
