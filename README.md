<!--
  THE DRAFTING ROOM x SECURITY CASE-FILE ARCHIVE — GitHub profile README
  Save as README.md in a repo named exactly like your username: chris-crts/chris-crts
  Palette: Black 0A0A0C · Charcoal 141113 · Crimson FF2D20 · Deep red 7A2420 · Ember FF7A00 · Amber FFB800 · Bone F3EDE4
-->

<div align="center">

<img alt="THE DRAFTING ROOM" width="100%" src="coffee_cats_v4_full.gif">

<img alt="typing tagline" src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&duration=2600&pause=900&color=FF2D20&center=true&vCenter=true&width=700&height=40&lines=%3E+booting+drafting_room.exe+...;%3E+engineer+of+scalable+%26+secure+apps;%3E+trace+%E2%86%92+verify+%E2%86%92+prove+%E2%86%92+ship;%3E+STATUS%3A+OPEN+FOR+COLLAB">

<br/>

![Status](https://img.shields.io/badge/STATUS-OPEN_FOR_COLLAB-FF2D20?style=for-the-badge&labelColor=0A0A0C&logo=githubsponsors&logoColor=FF2D20)
![Focus](https://img.shields.io/badge/FOCUS-SECURITY_%C2%B7_AI_%C2%B7_FULL--STACK-7A2420?style=for-the-badge&labelColor=0A0A0C)
![Access](https://img.shields.io/badge/ACCESS-GRANTED-FFB800?style=for-the-badge&labelColor=0A0A0C)

```text
┌──────────────────────────────────────────────────────────┐
│ [ OK ] blueprint engine ............................ ONLINE │
│ [ OK ] evidence archive ............................ MOUNTED │
│ [ OK ] human-approval gates ........................ ENFORCED │
│ [ >> ] awaiting collaboration request ...  ▮                │
└──────────────────────────────────────────────────────────┘
```

<img width="100%" height="3" src="https://capsule-render.vercel.app/api?type=rect&color=FF2D20&height=3">

</div>

---

## `SUBJECT PROFILE`

```text
╔═ FILE No. CC-2026 ═══════════════════════════════
║ NAME        Christopher Cortes
║ FOCUS       Secure web apps · AI integration · Security tooling
║ EXPERIENCE  4+ years freelance · 10+ shipped projects
╚══════════════════════════════════════════════════
```

I build web and mobile applications where **security is part of the design, not an afterthought**: role-based access, audit trails, tamper-evident records, and human-approved automation.

My current focus is **Anterior-Security**, a verification-first security testing platform for small teams and independent developers.

Right now I'm designing security tooling for the people big vendors overlook: **solo developers and small teams shipping AI-assisted or no-code web apps**, who need *verified* findings in plain language, not a 200-item scanner dump.

---

## `ACTIVE INVESTIGATION` · Featured Case

<div align="center">

<img src="anteriorsecurity_banner.gif" alt="Anterior-Security — verified findings, human-approved, audit-logged" width="100%" />

</div>

### Overview

**Anterior-Security (An-Sec)** is a verification-first web application security testing platform built for small teams and independent developers who ship AI-assisted and no-code applications. Rather than producing a long scanner report, it returns a small number of **verified, evidence-backed findings**, each explained in plain language and traceable through a complete audit trail that can serve as proof of due diligence.

The platform is designed around one principle: **no action runs without authorization, and no active test runs without a human decision.**

- **Authorized targets only.** Ownership is proven through a DNS TXT record or a `/.well-known/` verification file, and is re-checked on a schedule and before every active run. A lapsed verification suspends the target and invalidates existing approvals.
- **A single authorization chokepoint.** Every action is an `ActionProposal` that must move from `PROPOSED` to `APPROVED` by a human before it can execute. No code path can create a pre-approved proposal, and AI-originated proposals can never approve themselves.
- **Deterministic dispatch checks.** Emergency stop, target verification, engagement status, scope, the forbidden-action list, human approval, rate limits and isolation are evaluated in a fixed order on every run, and every failure is logged with its reason.
- **Evidence over alerts.** Findings are linked to immutable evidence records and presented with plain-language summaries and technical detail side by side.

| Tier | Capability | Authorization |
|---|---|---|
| 1 | Passive reconnaissance: DNS, certificate transparency, HTTP probing, security headers, technology fingerprinting | Rule-based, no approval |
| 2 | Safe active discovery: scoped crawl, endpoint and parameter discovery, CORS, cookie and HTTP method inspection | Rule-based, rate-limited and scope-checked |
| 3 | Verification of broken access control (IDOR), exposed secrets and misconfigured headers, and permissive CORS | Explicit human approval per proposal |
| 4-5 | Exploitation and post-exploitation | Hard-disabled in code; schema only |

Destructive writes, credential brute force, denial-of-service-style load, exfiltration of real user data, and any action outside scope or against an unverified target are permanently forbidden and cannot be enabled through configuration.

## 📸 Anterior Security Screens

[← Previous](#app_dash) | [Next →](#register_page)

<img id="sign_in_page" src="./sign_in_page.png" alt="Anterior-Security Sign In" width="100%" />
<img id="register_page" src="./register_page.png" alt="Anterior-Security Register" width="100%" />
<img id="app_dash" src="./app_dash.png" alt="Anterior-Security Dashboard" width="100%" />
<img id="dashboard_dark_mode" src="./dashboard_dark_mode.png" alt="Anterior-Security Dark Mode" width="100%" />


```text
╔═ CASE FILE №001 ═══════════════════ [ PRIVATE REPO · v2 ]
║ CODENAME    ANTERIOR-SECURITY (An-Sec) — Verified-Findings Platform
║ OBJECTIVE   Verified findings, explained in plain language,
║             with proof the owner can show a client or auditor.
║ AUDIENCE    Indie SaaS builders · small agencies · AI/no-code
║             app makers without a dedicated security team
║ METHOD      Recon → Discover → Investigate → Verify → Report
║ CONTROLS    Verified ownership · scoped, rate-limited actions
║             · human sign-off · emergency stop · audit log
║ EVIDENCE    Immutable evidence records · traceable findings
║             · plain-language reporting
║ STACK       Python · Django · FastAPI · PostgreSQL · React · LLM APIs
╚═══════════════════════════════════════════════════════
```

---

## `FIELD KIT` · Instruments

<div align="center">

![Python](https://img.shields.io/badge/Python-PRIMARY-FF2D20?style=for-the-badge&logo=python&logoColor=white&labelColor=0A0A0C)

![Django](https://img.shields.io/badge/Django-7A2420?style=flat-square&logo=django&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-7A2420?style=flat-square&logo=postgresql&logoColor=white)
![React](https://img.shields.io/badge/React-7A2420?style=flat-square&logo=react&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-7A2420?style=flat-square&logo=javascript&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-7A2420?style=flat-square)
![LLM Integration](https://img.shields.io/badge/LLM_Integration-7A2420?style=flat-square&logo=openai&logoColor=white)

![Wireshark](https://img.shields.io/badge/Wireshark-3B3B3B?style=flat-square&logo=wireshark&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-3B3B3B?style=flat-square)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-3B3B3B?style=flat-square)
![Metasploit](https://img.shields.io/badge/Metasploit-3B3B3B?style=flat-square)
![Ghidra](https://img.shields.io/badge/Ghidra-3B3B3B?style=flat-square)
![Git](https://img.shields.io/badge/Git_&_GitHub-3B3B3B?style=flat-square&logo=github&logoColor=white)

</div>

---

## `OPEN A CHANNEL`

<div align="center">

[![Portfolio](https://img.shields.io/badge/PORTFOLIO-chris--crts--page.netlify.app-7A2420?style=for-the-badge&labelColor=0A0A0C&logo=netlify&logoColor=FF2D20)](https://chris-crts-page.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-Christopher_Cortes-7A2420?style=for-the-badge&labelColor=0A0A0C&logo=linkedin&logoColor=FF2D20)](https://www.linkedin.com/in/christopher-cortes-a0021a28b/)
[![Email](https://img.shields.io/badge/EMAIL-11corteschristopher@gmail.com-FF2D20?style=for-the-badge&labelColor=0A0A0C&logo=gmail&logoColor=FF2D20)](mailto:11corteschristopher@gmail.com)

<img alt="END OF FILE" width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0A0A0C&height=140&section=footer&text=END%20OF%20FILE%20%C2%B7%20CC-2026&fontSize=18&fontColor=FF2D20&fontAlignY=68&animation=fadeIn">

</div>
