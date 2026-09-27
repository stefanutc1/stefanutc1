<div align="center">
  <a href="https://stefanutc1.github.io">
    <img src="./assets/banner.svg" alt="Moană Ștefănuț-Cornel (@stefanutc1) — Systems Architecture, Core-Banking FinTech, Homelab Infrastructure & DFIR" width="100%" />
  </a>
</div>

<br />

<div align="center">

[![Website & Tech Blog](https://img.shields.io/badge/WEBSITE_%26_BLOG-stefanutc1.github.io-52212e?style=for-the-badge&labelColor=17090d&logo=vercel&logoColor=efebe5)](https://stefanutc1.github.io)
[![Homelab Infrastructure](https://img.shields.io/badge/DATACENTER_IaC-stefanutc1%2Finfrastructure-401823?style=for-the-badge&labelColor=0c0c0c&logo=proxmox&logoColor=efebe5)](https://github.com/stefanutc1/infrastructure)
[![University & Thesis Monorepo](https://img.shields.io/badge/FEAA_2024--2027-stefanutc1%2Fproiecte-52212e?style=for-the-badge&labelColor=17090d&logo=springboot&logoColor=efebe5)](https://github.com/stefanutc1/proiecte)
[![Historical Archive 2015-2023](https://img.shields.io/badge/ARCHIVE_2015--2023-stefanutc1%2Fold-401823?style=for-the-badge&labelColor=0c0c0c&logo=git&logoColor=d9d1ca)](https://github.com/stefanutc1/old)

</div>

---

### `[01]` · Prezentare Generală / Executive Profile

Salut! Sunt **Moană Ștefănuț-Cornel** (`@stefanutc1`), inginer de sisteme informatice, arhitect de infrastructură hibridă și cercetător în securitate cibernetică aplicată (**DFIR & Threat Intelligence**), în prezent student la **Universitatea din Craiova — Facultatea de Economie și Administrarea Afacerilor (FEAA), specializarea Informatică Economică (`2024 – 2027`)**.

Parcursul meu tehnic a început în **2015**, construind de la zero primele servere multiplayer concurente, sisteme anti-cheat și baze de date relaționale MySQL (documentate în arhiva istorică [`stefanutc1/old`](https://github.com/stefanutc1/old)). De-a lungul a peste un deceniu de practică continuă (**2015 – Prezent**), această fundație a evoluat firesc către:

- **Arhitectură Financiar-Bancară Critică (Lucrare de Licență FEAA)**: Proiectarea unei platforme **Core-Banking & Payment Gateway** cu registru contabil în dublă partidă garantat **ACID** (`SELECT ... FOR UPDATE` / `SERIALIZABLE`), microservicii **Java 17 (Spring Boot 3.2)**, conformitate **PCI-DSS v4.0**, motor antifraudă **Python FastAPI** și detecție **Wazuh SIEM** pe **5 scenarii MITRE ATT&CK**.
- **Criminalistică Digitală (DFIR) & Threat Intelligence**: Decompilarea kiturilor de phishing multi-step (ex. *Media Galaxy / `yiyangsaas.com`*), analiza atacurilor **Browser-in-the-Middle (BitM)** pe fluxuri OAuth/OpenID (*Steam*) și a releelor de vishing în timp real (*Revolut OTP Relay*), culminând cu notificări oficiale și **Takedown Național DNSC (`#178465`)**.
- **Inginerie Datacenter Bare-Metal & Cloud Hibrid**: Operarea propriului cluster homelab cu **4 noduri fizice** (`Proxmox VE 9.2`, `OpenMediaVault 7 NAS`, `Apple Silicon ARM64`, `Kubernetes k3s`), segmentat în **5 VLAN-uri OPNsense 24.7** și orchestrat integral prin **57 de fișiere Terraform** și **18 roluri Ansible**.

---

### `[02]` · Ecosistemul de Proiecte & Arhive Principale (`2015 – 2027`)

| Cod Sistem | Repository & Link Direct | Perioadă | Arhitectură & Specificații Tehnice |
| :--- | :--- | :---: | :--- |
| **`SYS-WEB`** | **[`stefanutc1/stefanutc1.github.io`](https://github.com/stefanutc1/stefanutc1.github.io)**<br/>↳ 🌐 **[Live: stefanutc1.github.io](https://stefanutc1.github.io)** | `2026` | **Prezentare Personală & Jurnal de Inginerie** construit în **Next.js 15 (App Router, Static Export)** cu sistem vizual inspirat din `drivepoint.ro`, consolă interactivă `zsh`, paletă `⌘K` și **7 articole tehnice long-form** (RO/EN). |
| **`SYS-INFRA`** | **[`stefanutc1/infrastructure`](https://github.com/stefanutc1/infrastructure)** | `2025 – Prezent` | **4-Node Hybrid Homelab Datacenter**: Proxmox VE 9.2 (`pve`, `pve2`), OpenMediaVault NAS (`omv-nas`), Bare-Metal `k3s` (`kubernetes`), firewall **OPNsense 24.7** (5 VLAN-uri Zero-Trust), **57 fișiere Terraform**, **18 roluri Ansible**, **Wazuh SIEM/XDR**, **Suricata IDS/IPS** și telemetrie hardware **ESP32**. |
| **`SYS-THESIS`** | **[`stefanutc1/proiecte`](https://github.com/stefanutc1/proiecte)** | `2024 – 2027` | **Monorepo Academic FEAA UCV (43+ Proiecte) & Licență Core-Banking**: Platformă bancară **Java 17 Spring Boot 3.2 + Angular 20 + PostgreSQL**, dosare criminalistice **DFIR** (*DNSC `#178465`*), rezolvări complete **InvataCyber CTF (100%)**, aplicații C++, C# .NET, Python și topologii Cisco Packet Tracer. |
| **`SYS-OLD`** | **[`stefanutc1/old`](https://github.com/stefanutc1/old)** | `2015 – 2023` | **Arhiva Istorică de Dezvoltare Software**: **RedZone SA-MP Roleplay** (`2015–2016`, PAWN & MySQL), **NQGaming SA-MP 0.3.7 RPG** (`2016–2018`, 10 facțiuni, anti-cheat server-side), **Crowland Wiki** (`2019–2020`, Vue 3 & Vite), **Kronick Web Portal** (`2021–2023`, PHP/MySQL/Nginx) și **Roadman Discord Bot** (`2022–2023`, Python & Docker). |

---

### `[03]` · Jurnal Tehnic & Articole Recente pe [`stefanutc1.github.io`](https://stefanutc1.github.io)

1. **`[POST-01]` · [Analiză Criminalistică (DFIR) a Campaniei de Phishing „Media Galaxy" — De la Kitul `yiyangsaas.com` la Takedown-ul Național DNSC `#178465`](https://stefanutc1.github.io)**  
   *Decompilarea arhitecturii C2 (`23.224.199.13`), analiza exfiltrării datelor de card în 8 pași și blocarea națională coordonată cu Directoratul Național de Securitate Cibernetică.*
2. **`[POST-02]` · [Arhitectura unei Platforme Core-Banking Moderne: Registru în Dublă Partidă ACID, Conformitate PCI-DSS v4.0 și Detecție SIEM](https://stefanutc1.github.io)**  
   *Fundamentele lucrării de licență FEAA: prevenirea condițiilor de cursă (`Lost Update` / `Double-Spending`) în Java Spring Boot 3.2 și validarea pe 5 scenarii MITRE ATT&CK.*
3. **`[POST-03]` · [Construirea unui Datacenter Homelab cu 4 Noduri: Proxmox VE 9.2, Segmentare OPNsense pe 5 VLAN-uri și 57 Module Terraform](https://stefanutc1.github.io)**  
   *Ingineria clusterului fizic personal (`192.168.1.240`, `.181`, `.196`, `.150`), optimizarea memoriei prin ZRAM/KSM și orchestrarea GitOps.*
4. **`[POST-04]` · [Anatomia Bypass-ului 2FA: Atacuri Browser-in-the-Middle (BitM) pe Steam OpenID și Relee Vishing în Timp Real pe Revolut](https://stefanutc1.github.io)**  
   *Analiza comparativă a două paradigme moderne de compromitere a autentificării multifactor și reguli de detecție defensivă.*
5. **`[POST-05]` · [Decompilarea unei Platforme de „Task Scam": Manipularea `/api/v1/site/config`, Jocul Psihologic și Vulnerabilități SQL Injection](https://stefanutc1.github.io)**  
   *Cum funcționează tehnic escrocheriile de tip „optimizare comenzi" și cum am auditat API-ul backend al atacatorilor.*
6. **`[POST-06]` · [InvataCyber.ro 100% CTF Writeup: Exploatarea Vulnerabilităților Reflected XSS, Blind SQLi, Jinja2 SSTI și Criptografie Aplicată](https://stefanutc1.github.io)**  
   *Parcurgerea tehnică a tuturor provocărilor din laboratorul național de securitate cibernetică și remedierea vulnerabilităților.*
7. **`[POST-07]` · [De la Scripturi PAWN în 2015 la Infrastructură Enterprise: Peste un Deceniu de Evoluție în Inginerie Software (`stefanutc1/old`)](https://stefanutc1.github.io)**  
   *Retrospectivă tehnică asupra primelor sisteme reale construite între 2015 și 2023 și lecțiile de arhitectură care stau la baza proiectelor actuale.*

---

### `[04]` · Topologia Clusterului Homelab (`stefanutc1/infrastructure`)

```text
                         [ WAN / Cloudflare Zero-Trust Edge ]
                                          │
                        ┌─────────────────▼─────────────────┐
                        │   OPNsense 24.7 Firewall Router   │
                        │ 5 VLANs: MGMT·PROD·CYBER·NAS·IOT  │
                        └─┬──────────┬──────────┬─────────┬─┘
                          │          │          │         │
        ┌─────────────────▼─┐  ┌─────▼──────────▼─┐  ┌────▼────────────────┐
        │ NODE-1: pve       │  │ NODE-2: omv-nas  │  │ NODE-3 & NODE-4     │
        │ 192.168.1.240     │  │ 192.168.1.181    │  │ .196 (ARM64 pve2)   │
        │ Proxmox VE 9.2    │  │ OpenMediaVault 7 │  │ .150 (k3s Worker)   │
        │ 20+ VM/LXC · SIEM │  │ NFSv4/SMB3 · ZFS │  │ Cilium CNI · ESP32  │
        └───────────────────┘  └──────────────────┘  └─────────────────────┘
```

---

### `[05]` · Matricea Tehnologică (`2015 – Prezent`)

| Domeniu | Tehnologii, Limbaje & Platforme |
| :--- | :--- |
| **Backend & Core Systems** | `Java 17` · `Spring Boot 3.2` · `Python 3.12` · `FastAPI` · `C / C++ (STL, POSIX)` · `C# (.NET 8)` · `PHP` · `PAWN` |
| **Frontend & Web Portals** | `TypeScript` · `Next.js 15 (React 19)` · `Angular 20` · `Vue 3 (Vite)` · `Tailwind CSS` · `HTML5 / SCSS` |
| **Datacenter, Cloud & IaC** | `Proxmox VE 9.2` · `Kubernetes (k3s / k0s)` · `Terraform (57 module)` · `Ansible (18 roluri)` · `Docker` · `Nginx` · `GitHub Actions CI/CD` |
| **Cybersecurity, DFIR & Net** | `Wazuh SIEM/XDR` · `Suricata IDS/IPS` · `OPNsense 24.7 (5 VLANs)` · `CrowdSec` · `WireGuard` · `YARA` · `MITRE ATT&CK` |
| **Databases & Storage** | `PostgreSQL 16 (ACID Ledger)` · `MySQL / MariaDB` · `Oracle SQL` · `SQLite` · `Redis` · `OpenMediaVault NAS (ZFS / NFSv4)` |

---

### `[06]` · Coordonate & Contact

- 🌐 **Website Personal & Blog Tehnic**: [https://stefanutc1.github.io](https://stefanutc1.github.io)
- 🎓 **Studii Universitare**: Universitatea din Craiova · Facultatea de Economie și Administrarea Afacerilor (FEAA) — *Informatică Economică (`2024 – 2027`)*
- 📫 **Email**: [boostcroyale18@gmail.com](mailto:boostcroyale18@gmail.com)
- 📍 **Locație**: Craiova, România
