## whoami

I'm Dan — a security analyst playing developer, building open-source tools for blue teams (and one for CTFs).

---

### 🔬 Projects

#### [Minos](https://github.com/DanDreadless/minos) — Network-wide Ad & Tracker Blocker

A modern Pi-hole and AdGuard Home alternative written in Go — one static binary with the web interface built in, light enough for a Raspberry Pi. *Every query gets judged:* every block names the list and rule behind it, with Allow one click away.

- **DNS Filter** — self-healing blocklists (hosts, plain, AdBlock) from a verified catalog, audit (dry-run) lists, CNAME-cloak inspection, and `*.wildcard` / `/regex/` rules for everyone, a group or one device
- **Family controls** — device groups with schedules, one-click blocked services, and provider-enforced Safe Search
- **Privacy report** — the tracking companies each device talks to, blocked by company in one click
- **Encrypted DNS both ways** — DoH, DoT, DNS over QUIC and HTTP/3, DDR, and in-process DNSSEC validation
- **Built to live with** — millisecond Query Log search, a full guide in the app, phone-ready pages, password sign-in with authenticator codes, and signed one-click updates that roll back a release that doesn't start
- **Plays well with others** — Prometheus metrics, a documented REST API, Home Assistant over MQTT, and one-command Pi-hole/AdGuard import
- **No telemetry, ever.** Stack: Go / Svelte / SQLite / Docker
- Docs: [vault1337.com/minos.html](https://www.vault1337.com/minos.html) · Install: `curl -fsSL https://raw.githubusercontent.com/DanDreadless/minos/main/deploy/install.sh | sudo sh`

---

#### [Carapace](https://github.com/DanDreadless/Carapace) — Safe Web Renderer

A safe visual renderer that loads suspicious pages in Chromium headless with JavaScript fully enabled but **all network requests intercepted and blocked** — so dynamic overlays (ClickFix, SocGholish, ClearFake, wallet drainers) execute and render visibly without ever reaching attacker infrastructure.

- **Safe render** — JS enabled, network intercepted, dynamic attack UI captured in a screenshot
- Detects drive-by downloads, `eval()` chains, clipboard hijacks, and exfiltration at render time
- **Risk score (0–100)** and structured threat flags, plus browser-grade technology fingerprinting
- Mobile screenshot support (375×844 iPhone viewport); composites a verdict badge onto every capture
- Stack: Rust / Chromium (headless)

---

#### [Cyberdeck](https://github.com/DanDreadless/cyberdeck) — A CTF Companion Tool

A terminal app for working Hack The Box machines from Kali Linux. It tracks your progress on each box, suggests what to run next (and *why*), and wraps the Kali tools so every command is explained and every result is kept. Not an autopilot: you still do the hacking.

- **Tracks the box** — services, hostnames, URLs, creds, hashes, flags and every command run, in one folder per box
- **Suggests next steps** — ranked, each with a short why and a link to learn more; skip or snooze any of them
- **Wraps 45+ Kali tools** — a Run dialog with presets, explained flags and the exact command before anything runs
- **Built for learning** — plain-English job summaries, a glossary, per-service checklists and an "I'm stuck" flow
- **Claude Code over MCP** — safe recon on request; anything intrusive waits for your approval
- Stack: Python / Textual / SQLite · Docs: [vault1337.com/cyberdeck.html](https://www.vault1337.com/cyberdeck.html)

---

### 🔒 Also maintained

These projects are documented at [vault1337.com](https://www.vault1337.com). Their source repositories have been made **private** until further notice — any interest in access should be made directly.

- **Vault1337** — self-hosted static malware analysis platform (20+ tools, MITRE ATT&CK mapping, STIX 2.1 export).
  - Still available on Docker Hub: `docker pull vault1337/vault1337`
- **Insight** — passive, content-based web threat scanner (76+ checks).
  - Live at [insight.vault1337.com](https://insight.vault1337.com)

---

### 🛠️ Tech I'm comfortable with

`Python` `Django` `Docker` `PostgreSQL` `Bash` `Powershell` `Linux` `Windows` `MacOS`

### 🤖 Tech CLAUDE "helps" me with

`Go` `Rust` `React` `TypeScript` `Redis` `Tailwind CSS`
