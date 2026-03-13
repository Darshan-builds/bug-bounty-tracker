<div align="center">

<br/>

```
██████╗ ██╗   ██╗ ██████╗     ██████╗  ██████╗ ██╗   ██╗███╗   ██╗████████╗██╗   ██╗
██╔══██╗██║   ██║██╔════╝     ██╔══██╗██╔═══██╗██║   ██║████╗  ██║╚══██╔══╝╚██╗ ██╔╝
██████╔╝██║   ██║██║  ███╗    ██████╔╝██║   ██║██║   ██║██╔██╗ ██║   ██║    ╚████╔╝ 
██╔══██╗██║   ██║██║   ██║    ██╔══██╗██║   ██║██║   ██║██║╚██╗██║   ██║     ╚██╔╝  
██████╔╝╚██████╔╝╚██████╔╝    ██████╔╝╚██████╔╝╚██████╔╝██║ ╚████║   ██║      ██║   
╚═════╝  ╚═════╝  ╚═════╝     ╚═════╝  ╚═════╝  ╚═════╝ ╚═╝  ╚═══╝   ╚═╝      ╚═╝  
                                                                                      
████████╗██████╗  █████╗  ██████╗██╗  ██╗███████╗██████╗                            
╚══██╔══╝██╔══██╗██╔══██╗██╔════╝██║ ██╔╝██╔════╝██╔══██╗                           
   ██║   ██████╔╝███████║██║     █████╔╝ █████╗  ██████╔╝                           
   ██║   ██╔══██╗██╔══██║██║     ██╔═██╗ ██╔══╝  ██╔══██╗                           
   ██║   ██║  ██║██║  ██║╚██████╗██║  ██╗███████╗██║  ██║                           
   ╚═╝   ╚═╝  ╚═╝╚═╝  ╚═╝ ╚═════╝╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝                          
```

<br/>

**A professional, offline-first vulnerability tracking dashboard for bug bounty hunters.**  
Track 175 vulnerabilities across 4 priority tiers — all in a single, self-contained HTML file.

<br/>

![HTML](https://img.shields.io/badge/HTML5-Single%20File-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-No%20Framework-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla%20ES6-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-7c5cbf?style=for-the-badge)
![Offline](https://img.shields.io/badge/Works-Offline-00c853?style=for-the-badge)

<br/>

[🚀 Live Demo](#) &nbsp;·&nbsp; [📸 Screenshots](#screenshots) &nbsp;·&nbsp; [⚡ Quick Start](#quick-start) &nbsp;·&nbsp; [🗂️ Vulnerability Index](#vulnerability-index)

<br/>

</div>

---

## ✦ Overview

Bug Bounty Tracker is a **100% client-side**, zero-dependency vulnerability checklist and progress dashboard designed for professional bug bounty hunters and penetration testers. No server. No login. No internet required after download.

Everything — your target info, checked vulnerabilities, workflow progress, and activity log — is saved automatically to your browser's local storage. Open the file, start hacking.

<br/>

## ✦ Screenshots

<div align="center">

| Dashboard | Vulnerability Checklist |
|:---------:|:-----------------------:|
| ![Dashboard](https://via.placeholder.com/480x300/7c5cbf/ffffff?text=Dashboard+View) | ![Checklist](https://via.placeholder.com/480x300/1a1a2e/ffffff?text=Checklist+View) |

| Reports & Export | Target Info |
|:----------------:|:-----------:|
| ![Reports](https://via.placeholder.com/480x300/e879c5/ffffff?text=Reports+%26+Export) | ![Target](https://via.placeholder.com/480x300/6fa3ef/ffffff?text=Target+Info) |

</div>

<br/>

## ✦ Features

<table>
<tr>
<td width="50%">

### 🎯 Core Tracking
- ✅ **175 vulnerabilities** across 4 priority tiers
- 🔴 Priority-coded dots (Critical / High / Medium / Low)
- 🔍 Live search across all vulnerabilities
- 💾 Auto-save to localStorage — nothing is lost on refresh
- 🔄 Reset with one click (preserves target info)

</td>
<td width="50%">

### 📊 Dashboard & Reports
- 📈 Animated progress bar and coverage percentage
- 🍩 SVG donut chart with live section breakdown
- 📋 Section-by-section completion bars
- 📤 Export to **CSV**, **plain text**, or **clipboard**
- 🖨️ Print-ready report view

</td>
</tr>
<tr>
<td width="50%">

### 🏹 Target Management
- 🌐 Domain, company, program, platform fields
- 🏷️ Tech stack tag input
- 📝 Scope in / scope out lists
- 🔐 Auth credential notes (stored locally only)
- 📌 Custom endpoint notes

</td>
<td width="50%">

### 🔧 Workflow Engine
- 📋 12-step structured testing workflow
- 🧭 Visual workflow progress tracker
- 📜 Activity log (last 50 checked items)
- ⚡ Recent activity panel in sidebar
- 🎨 Purple / pink / blue color system

</td>
</tr>
</table>

<br/>

## ✦ Quick Start

No installation. No build step. No dependencies.

```bash
# Clone the repository
git clone https://github.com/Darshan-builds/bug-bounty-tracker.git

# Open in browser
open bug-bounty-tracker.html
```

Or simply [download the raw HTML file](./bug-bounty-tracker.html) and open it directly in any modern browser.

> **Tip:** Bookmark the local file path in your browser for instant access at the start of every engagement.

<br/>

## ✦ Vulnerability Index

All **175 vulnerabilities** are organized across 4 sections:

<details>
<summary><strong>✅ Quick Checklist — 40 items</strong> &nbsp;|&nbsp; Essential first-pass checks for any target</summary>

<br/>

| Group | Vulnerabilities |
|-------|----------------|
| **Recon** (8) | Subdomain enumeration, Subdomain takeover, Directory brute force, Hidden files discovery, Backup files, JavaScript endpoint discovery, API endpoint discovery, Wayback URLs |
| **Information Disclosure** (5) | Git repository exposure, Debug endpoints, API key exposure, Sensitive JS data, Source maps |
| **Access Control** (6) | IDOR, Horizontal privilege escalation, Vertical privilege escalation, Forced browsing, API authorization bypass, Broken object level authorization |
| **Authentication** (6) | Weak password policy, Login brute force protection, Password reset flaws, Password reset token reuse, OTP brute force, Session fixation |
| **XSS** (6) | Reflected XSS, Stored XSS, DOM XSS, HTML injection, CORS misconfiguration, Clickjacking |
| **File Handling** (3) | File upload bypass, MIME type bypass, Path traversal |
| **API Security** (3) | Mass assignment, Parameter pollution, API object enumeration |
| **Business Logic** (3) | Coupon abuse, Race condition, Negative price manipulation |

</details>

<details>
<summary><strong>🔴 Priority 1 — 25 items</strong> &nbsp;|&nbsp; Critical & high severity findings most likely to pay out</summary>

<br/>

| Group | Vulnerabilities |
|-------|----------------|
| **Server-Side Injection** (5) | SQL injection, Blind SQL injection, Command injection, SSTI, XXE |
| **SSRF** (3) | SSRF to internal services, SSRF to cloud metadata, SSRF via URL redirect |
| **Authentication Bypass** (5) | JWT manipulation, OAuth token leakage, SAML authentication bypass, Session fixation, Account takeover via OAuth |
| **Access Control Critical** (4) | Broken function level authorization, Admin panel unauthorized access, Privilege escalation via role parameter, Object-level auth bypass in GraphQL |
| **Deserialization** (3) | Java deserialization RCE, PHP object injection, Python pickle deserialization |
| **Critical Disclosure** (5) | AWS/GCP/Azure credentials in source, Private key exposure, Database credentials exposed, Internal network topology leak, Hard-coded credentials in API |

</details>

<details>
<summary><strong>🟠 Priority 2 — 30 items</strong> &nbsp;|&nbsp; Medium severity — often overlooked, frequently valid</summary>

<br/>

| Group | Vulnerabilities |
|-------|----------------|
| **Injection** (5) | NoSQL injection, LDAP injection, XPath injection, CSV injection, Email header injection |
| **File Attacks** (5) | LFI, RFI, File extension bypass, Zip slip, Null byte injection |
| **Client-Side** (5) | CSRF, Open redirect, Subdomain takeover, DOM-based open redirect, CSS injection |
| **Protocol & Headers** (5) | Host header injection, CRLF injection, HTTP verb tampering, WebSocket cross-origin, SMTP injection |
| **Token & Session** (5) | JWT algorithm confusion, Weak session entropy, Cookie security flags missing, Session token in URL, Credential stuffing |
| **API & GraphQL** (5) | GraphQL introspection, GraphQL batch query abuse, Swagger/OpenAPI exposure, API versioning bypass, XML injection |

</details>

<details>
<summary><strong>🧪 Advanced — 80 items</strong> &nbsp;|&nbsp; Deep, specialized, and chain-exploitation techniques</summary>

<br/>

| Group | Count | Examples |
|-------|:-----:|---------|
| Advanced SQL & NoSQL Injection | 5 | Second-order SQLi, OGNL injection, SpEL injection |
| Advanced SSRF | 5 | Blind SSRF via DNS, SSRF to EC2 IMDSv2, K8s API SSRF |
| Advanced XXE | 5 | Blind XXE OOB, XXE via SVG, XXE via XLSX/DOCX |
| HTTP Protocol Attacks | 5 | Request smuggling CL.TE, TE.CL, H2C upgrade |
| Web Cache Attacks | 5 | Cache poisoning, Cache deception, CPDoS |
| OAuth & SSO Deep Dive | 5 | SAML signature wrapping, OpenID Connect misconfig |
| Advanced JWT Attacks | 5 | None algorithm bypass, RS256→HS256 confusion |
| Advanced XSS Techniques | 5 | mXSS, DOM clobbering, Service worker hijacking |
| Prototype Pollution | 5 | Client-side, Server-side (Node.js), Pollution to RCE |
| Cryptography Attacks | 5 | Padding oracle, CBC bit-flip, Hash length extension |
| Race Conditions Advanced | 5 | TOCTOU, Double spend, Concurrent session abuse |
| Business Logic Advanced | 5 | Order manipulation, Gift card replay, Payment bypass |
| Cloud Security | 5 | S3 misconfig, IAM privilege escalation, GCP service accounts |
| Exposed Internal Services | 5 | Jenkins RCE, Grafana bypass, Redis/Elasticsearch unauth |
| Deserialization Advanced | 5 | .NET ViewState, Ruby Marshal, Java RMI |
| Server Misconfiguration | 5 | Nginx alias traversal, PHP type juggling, IIS 8.3 |

</details>

<br/>

## ✦ How It Works

```
┌─────────────────────────────────────────────────────────────────┐
│                     bug-bounty-tracker.html                     │
│                                                                 │
│  ┌──────────┐  ┌────────────────────────────┐  ┌─────────────┐  │
│  │ Sidebar  │  │       Main Content         │  │ Right Panel │  │
│  │          │  │                            │  │             │  │
│  │ • Nav    │  │  Dashboard / Checklists /  │  │ • Progress  │  │
│  │ • Target │  │  Reports / Target Info /   │  │ • Workflow  │  │
│  │ • Domain │  │  Workflow                  │  │ • Activity  │  │
│  └──────────┘  └────────────────────────────┘  └─────────────┘  │
│                                                                 │
│  State: localStorage  ·  Zero network requests  ·  ~1 HTML file │
└─────────────────────────────────────────────────────────────────┘
```

All state is persisted automatically using these localStorage keys:

| Key | Contents |
|-----|----------|
| `bbt2_chk` | Checked/unchecked state for all 175 vulnerabilities |
| `bbt2_tgt` | Target domain, company, platform, credentials, notes |
| `bbt2_scope` | Scope-in and scope-out lists |
| `bbt2_tech` | Tech stack tags |
| `bbt2_wf` | Workflow step progress (0–12) |
| `bbt2_act` | Activity log (last 50 entries) |

<br/>

## ✦ Usage Guide

### Starting a New Engagement

1. **Open** `bug-bounty-tracker.html` in your browser
2. **Click** `Target Info` in the sidebar → fill in domain, program, platform
3. **Start** with the **Quick Checklist** tab for fast initial coverage
4. **Work through** Priority 1 → Priority 2 → Advanced as the engagement deepens
5. **Export** your findings report at any time from the Reports view

### Exporting Results

| Format | Best For |
|--------|----------|
| 📋 **Copy to Clipboard** | Pasting into Notion, Obsidian, or notes |
| 📄 **Export TXT** | Plain-text report for sharing |
| 📊 **Export CSV** | Importing into Excel / Google Sheets |
| 🖨️ **Print** | PDF generation via browser print dialog |

### Resetting for a New Target

Click **Reset Progress** in the sidebar. This clears all checkboxes and the activity log while **preserving** your Target Info and Workflow state.

<br/>

## ✦ Browser Support

| Browser | Support |
|---------|:-------:|
| Chrome / Chromium 90+ | ✅ Full |
| Firefox 88+ | ✅ Full |
| Safari 14+ | ✅ Full |
| Edge 90+ | ✅ Full |
| Mobile (iOS / Android) | ✅ Full |

<br/>

## ✦ Privacy & Security

> 🔒 **Your data never leaves your device.**

- No analytics, no tracking, no external requests of any kind
- All data stored in browser localStorage — local to your machine
- Credentials and notes in Target Info are stored locally only
- Safe to use on air-gapped systems or VPN-restricted environments

<br/>

## ✦ Project Structure

```
bug-bounty-tracker/
│
├── bug-bounty-tracker.html    # The entire application — one file
└── README.md                  # This file
```

<br/>

## ✦ Roadmap

- [ ] Multiple target tabs / session switching
- [ ] Custom vulnerability list import (JSON)
- [ ] Dark / light theme toggle
- [ ] Evidence attachment notes per vulnerability
- [ ] Severity score calculator (CVSS)
- [ ] Markdown report export

<br/>

## ✦ Contributing

Contributions are welcome. To suggest new vulnerabilities, improve the UI, or fix bugs:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m 'Add: your feature description'`
4. Push to the branch: `git push origin feature/your-feature`
5. Open a Pull Request

<br/>

## ✦ License

```
MIT License — free to use, modify, and distribute.
```

<br/>

---

<div align="center">

Made with 🩷 for the bug bounty community

**Happy Hunting**

<br/>

![Visitors](https://img.shields.io/badge/dynamic/json?color=7c5cbf&label=visitors&query=value&url=https://api.countapi.xyz/hit/bug-bounty-tracker/visits&style=flat-square)

</div>
