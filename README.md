## whoami

I'm Dan — a security analyst playing developer, building open-source tools for blue teams.

---

### 🔬 Projects

#### [Vault1337](https://github.com/DanDreadless/Vault1337) — Self-Hosted Malware Analysis Platform

A privacy-first, on-premises static malware analysis platform for security researchers and educators. No cloud dependencies — everything runs locally.

- **20+ analysis tools** covering PE, ELF, Mach-O, APK, .NET, documents, archives, and email
- **Threat intelligence enrichment** via VirusTotal, AbuseIPDB, Shodan, and Spur
- **MITRE ATT&CK mapping**, YARA rule engine, simhash clustering, and STIX 2.1 export
- **IOC extraction and enrichment** across 13 IOC types
- **REST API** with JWT auth, Swagger docs, and PDF report generation
- Stack: Python / Django / React / TypeScript / PostgreSQL / Docker
- Test the project with docker
  - docker pull vault1337/vault1337
---

#### [Insight](https://github.com/DanDreadless/insight) — Passive Web Threat Scanner

A content-based URL scanner that detects malicious and suspicious web content without relying on reputation databases — catching zero-day campaigns and newly registered domains that traditional feeds miss.

- **76+ detection checks** across JavaScript threats, phishing indicators, domain intelligence, HTTP headers, and TLS/SSL
- Detects: obfuscated JS, Magecart skimmers, crypto miners, wallet drainers, SocGholish/ClearFake lures, ClickFix, HTML smuggling, typosquatting, IDN homograph attacks, and more
- **Technology stack fingerprinting** for CMS, frameworks, CDN, and security tooling
- Real-time scan progress via Server-Sent Events
- Stack: Python / Django / Celery / Redis / React / TypeScript / PostgreSQL / Docker

---

The Document site for both projects can be found at https://www.vault1337.com

---

### 🛠️ Tech I work with

`Python` `Django` `React` `TypeScript` `Docker` `PostgreSQL` `Redis` `Tailwind CSS`
