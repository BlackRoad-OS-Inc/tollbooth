# tollbooth

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
