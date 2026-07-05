## whoami

I'm Dan — a security analyst playing developer, building open-source tools for blue teams.

---

### 🔬 Projects

#### [Minos](https://github.com/DanDreadless/minos) — Modern DNS Sinkhole

A user-friendly DNS sinkhole (a Pi-hole alternative) written in Go — a single static binary with an embedded web UI, light enough to run on a Raspberry Pi. Every query gets judged against your blocklists and sentenced; allowed queries are forwarded upstream over encrypted DNS.

- **Blocklist filtering** (hosts, plain, AdBlock formats) with one-click pardons from a live query log
- **Family controls** — per-device groups, one-click blocked services, schedules, and provider-enforced Safe Search
- **Fast resolver core** — response cache, request coalescing, serve-stale (RFC 8767), and automatic upstream failover
- **Encrypted DNS** — upstream DoH/DoT plus client-facing DoT/DoH with automatic ACME certificates
- **Prometheus metrics**, a documented REST API, Home Assistant recipes, and one-command Pi-hole/AdGuard import
- **No telemetry, ever.** Stack: Go / embedded web UI / SQLite / Docker
- Install: `curl -fsSL https://raw.githubusercontent.com/DanDreadless/minos/main/deploy/install.sh | sudo sh`

---

#### [Carapace](https://github.com/DanDreadless/Carapace) — Safe Web Renderer

A safe visual renderer that loads suspicious pages in Chromium headless with JavaScript fully enabled but **all network requests intercepted and blocked** — so dynamic overlays (ClickFix, SocGholish, ClearFake, wallet drainers) execute and render visibly without ever reaching attacker infrastructure.

- **Safe render** — JS enabled, network intercepted, dynamic attack UI captured in a screenshot
- Detects drive-by downloads, `eval()` chains, clipboard hijacks, and exfiltration at render time
- **Risk score (0–100)** and structured threat flags, plus browser-grade technology fingerprinting
- Mobile screenshot support (375×844 iPhone viewport); composites a verdict badge onto every capture
- Stack: Rust / Chromium (headless)

---

### 🔒 Also maintained

These projects are documented at [vault1337.com](https://www.vault1337.com). Their source repositories have been made **private** until further notice — any interest in access should be made directly.

- **Vault1337** — self-hosted static malware analysis platform (20+ tools, MITRE ATT&CK mapping, STIX 2.1 export). Still available on Docker Hub: `docker pull vault1337/vault1337`
- **Insight** — passive, content-based web threat scanner (76+ checks). Live at [insight.vault1337.com](https://insight.vault1337.com)

---

### 🛠️ Tech I work with

`Go` `Rust` `Python` `Django` `React` `TypeScript` `Docker` `PostgreSQL` `Redis` `Tailwind CSS`
