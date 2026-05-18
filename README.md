# Satheesh Nithiananthan
### Security Researcher · Penetration Tester · Bug Bounty Hunter

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1000&color=00FF41&center=true&vCenter=true&width=600&lines=Offensive+Security+%7C+Web+Application+Pentesting;API+Security+%7C+WebSocket+Analysis+%7C+IDOR;OWASP+Top+10%3A2025+%7C+Bug+Bounty+%7C+Red+Team;Every+shadow+has+a+hunter+🐺)](https://git.io/typing-svg)

</div>

---

## 🎯 Specialization

I specialize in **web application security research** with a primary focus on:

- **Authentication & Authorization Bypass** — OAuth flows, JWT weaknesses, session management failures
- **API Security** — REST API abuse, mass assignment, parameter pollution, cross-tenant IDOR
- **Real-time Protocol Security** — WebSocket authentication bypass, private event channel hijacking
- **Secret Exposure** — SSR framework leaks, JS bundle analysis, supply chain passive recon
- **Business Logic Flaws** — Tenant isolation failures, privilege escalation, access control gaps

> All research follows **OWASP Top 10:2025** · CWE mapping · Responsible disclosure only

---

## 🔬 Security Research & Bug Bounty

> All research conducted under authorized bug bounty and VDP programs only.
> Responsible disclosure principles strictly followed across all engagements.

| Vulnerability | CWE | Severity | Platform | Status |
|--------------|-----|----------|----------|--------|
| Cross-tenant WebSocket authentication bypass — unauthorized private channel subscription across tenant boundaries via improper Pusher auth token issuance — real-time security event eavesdropping confirmed | CWE-284 | 🔴 High | Intigriti | Under Review |
| Server-side authorization bypass — cross-tenant write operations accepted with misleading 2xx responses bypassing tenant isolation controls | CWE-755 | 🟡 Medium | Intigriti | Under Review |
| Tenant workspace enumeration via distinguishable API error responses on authenticated endpoints | CWE-203 | 🟢 Low | Intigriti | Under Review |
| SSR framework secret exposure — production API token leaked in client-side state hydration — full read/write dataset access independently confirmed | CWE-798 | 🔴 High | HackerOne VDP | Independently Validated |
| Hardcoded blockchain service credentials exposed in public JS bundle — multi-network surveillance risk across 7 chains | CWE-798 | 🟡 Medium | Bugcrowd | Independently Validated |
| IDOR on financial ranking endpoint — private user financial data exposure | CWE-639 | 🟡 Medium | Bugcrowd | Independently Validated |
| RBAC failures · AI endpoint over-privilege · security misconfigurations across live production assets — mapped to OWASP Top 10:2025 | CWE-862, CWE-1336, CWE-693 | 🟡 Medium | NCSA Bug Bounty VDP | Certificate of Appreciation |

### Active Platforms
[![HackerOne](https://img.shields.io/badge/HackerOne-494649?style=flat&logo=hackerone&logoColor=white)](https://hackerone.com/cyberlycan10)
[![Bugcrowd](https://img.shields.io/badge/Bugcrowd-F26822?style=flat&logo=bugcrowd&logoColor=white)](https://bugcrowd.com/cyberlycan)
[![Intigriti](https://img.shields.io/badge/Intigriti-Active-1a1a2e?style=flat)](https://app.intigriti.com/researcher/profile/cyberlycan)

---

## 🛠 Technical Arsenal

### Offensive Security
```
Web Application    │ IDOR · XSS · SQLi · SSRF · CSRF · Auth Bypass · Business Logic
API Security       │ REST abuse · Mass Assignment · Parameter Pollution · JWT Attacks
Recon              │ Subdomain enum · JS bundle analysis · SSR secret hunting · OSINT
WebSocket          │ Auth bypass · Channel hijacking · Cross-tenant event eavesdropping
OAuth/Session      │ State CSRF · redirect_uri bypass · Token leakage · Session fixation
Blockchain         │ Smart contract recon · API key exposure · Web3 endpoint analysis
```

### Defensive Security
```
SIEM               │ Wazuh — custom detection rules · alert correlation · log forensics
Threat Detection   │ Honeypot deployment · botnet identification · DPI analysis
Malware Analysis   │ Android static analysis · ML-based detection · behavior mapping
```

### Primary Toolchain
```
Core               │ Burp Suite · Kali Linux · Postman · Nuclei
Recon              │ Subfinder · ffuf · XnLinkFinder · Amass · httpx
Analysis           │ Wireshark · jwt.io · CyberChef · Shodan
Scripting          │ Python · Bash · Docker
```

---

## 📁 Research Portfolio

| Project | Focus | Impact |
|---------|-------|--------|
| [Supply-Chain-Secret-Hunting](https://github.com/Satz-N-Sentry/Supply-Chain-Secret-Hunting) | SSR token exposure via passive JS bundle recon | CWE-798 · High · Independently Validated |
| [NCSA-VDP-Assessment](https://github.com/Satz-N-Sentry/NCSA-VDP-Assessment) | Full passive VAPT — RBAC, AI over-privilege, misconfigs | Certificate of Appreciation · 2026 |
| [FUTURE_CS_03](https://github.com/Satz-N-Sentry/FUTURE_CS_03) | API Security — 9 vulnerabilities on OWASP crAPI | OWASP · CVE · MITRE mapped |
| [android-malware-analysis](https://github.com/Satz-N-Sentry/android-malware-analysis) | ML malware detection — Random Forest — 100% recall | Static analysis · scikit-learn · Python |
| [SAIZERO-Cowrie-Honeypot](https://github.com/Satz-N-Sentry/SAIZERO-Cowrie-Honeypot) | SSH honeypot — real botnet confirmed — Wazuh SIEM integration | Real-world threat intelligence |
| [wazuh-nmap-detection](https://github.com/Satz-N-Sentry/wazuh-nmap-detection) | Real-time scan detection — TCP/UDP/ICMP — Level 15 critical alerts | Custom Wazuh rule engine |
| [wazuh-homelab](https://github.com/Satz-N-Sentry/wazuh-homelab) | Enterprise-grade Wazuh Manager & Agent homelab | Production-ready SIEM setup |

---

## 📊 OWASP Top 10:2025 Coverage

```
A01 Broken Access Control     ████████████████████ Primary Research Focus
A02 Cryptographic Failures    ███████████████░░░░░ JWT · Token · Crypto Analysis
A03 Injection                 █████████████░░░░░░░ SQLi · XSS · SSTI
A07 Auth & Session Failures   ████████████████░░░░ OAuth · WebSocket · Session
A08 Software & Data Integrity ████████░░░░░░░░░░░░ Webhook · Supply Chain
A10 SSRF                      ██████████░░░░░░░░░░ Webhook · Integration Abuse
```

---

## 🏅 Certifications & Recognition

| Credential | Issuer | Year |
|-----------|--------|------|
| 🏆 Certificate of Appreciation — Bug Bounty VDP | NCSA Maldives | 2026 |
| 🎯 CICSA — Certified IT Infrastructure & Cyber SOC Analyst | RedTeam Hacker Academy | 2025 |
| 🎯 National Cybersecurity Certification | NCSA Maldives | 2026 |
| 🎓 BSc Computer Science | Alagappa University | 2024 |

---

## 📈 Current Research Focus

```python
current_targets = {
    "priority_1": "OAuth CSRF — state parameter validation bypass",
    "priority_2": "SSRF via webhook and integration endpoints",
    "priority_3": "JWT algorithm confusion — HS256 → none/RS256",
    "priority_4": "Mass assignment on user profile endpoints",
    "priority_5": "Stored XSS in user-controlled input fields"
}

methodology = "OWASP Top 10:2025 → Threat model → PoC → Responsible disclosure"
affiliation  = "SAIZERO — Ground Zero Defence (2024 — Present)"
```

---

## 🌐 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/satheesh-nithiananthan-86a2913ab)
[![HackerOne](https://img.shields.io/badge/HackerOne-494649?style=flat&logo=hackerone&logoColor=white)](https://hackerone.com/cyberlycan10)
[![Bugcrowd](https://img.shields.io/badge/Bugcrowd-F26822?style=flat&logo=bugcrowd&logoColor=white)](https://bugcrowd.com/cyberlycan)
[![Intigriti](https://img.shields.io/badge/Intigriti-Active-1a1a2e?style=flat)](https://app.intigriti.com/researcher/profile/cyberlycan)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-212C42?style=flat&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/SatzNithii)

---

## 🔧 Skills

![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=flat&logo=kalilinux&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat&logo=burpsuite&logoColor=white)
![OWASP](https://img.shields.io/badge/OWASP-Top10:2025-000000?style=flat&logo=owasp&logoColor=white)
![Nuclei](https://img.shields.io/badge/Nuclei-00bcd4?style=flat&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat&logo=wireshark&logoColor=white)
![Wazuh](https://img.shields.io/badge/Wazuh-005571?style=flat&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![Bug Bounty](https://img.shields.io/badge/Bug%20Bounty-Active-red?style=flat)
![WebSocket Security](https://img.shields.io/badge/WebSocket-Security-0077B5?style=flat)
![API Security](https://img.shields.io/badge/API-Security-cc0000?style=flat)
![JWT Analysis](https://img.shields.io/badge/JWT-Analysis-f59e0b?style=flat)
![IDOR](https://img.shields.io/badge/IDOR-Research-8b5cf6?style=flat)
![SSR Security](https://img.shields.io/badge/SSR-CWE--798-dd6b20?style=flat)
![Blockchain Security](https://img.shields.io/badge/Blockchain-Security-F7931A?style=flat)
![Passive Recon](https://img.shields.io/badge/Passive%20Recon-Expert-555555?style=flat)

---

<div align="center">

**SAIZERO — Ground Zero Defence**

*Affiliated independent security research unit · Est. 2024*

![Visitor Count](https://komarev.com/ghpvc/?username=Satz-N-Sentry&color=00ff41&style=flat&label=Profile+Views)

*CyberLycan — Every shadow has a hunter 🐺*

</div>
