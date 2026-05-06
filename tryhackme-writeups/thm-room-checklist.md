# TryHackMe SOC Write-Up Targets
**Goal:** Complete and write up each room while it's fresh. Add your write-up file link next to each room as you finish it.

---

## 🔴 Highest Priority — Core Daily SOC Tasks
These map directly to what you'll do in your first week on the job.

| Status | Room | Why It Matters | Write-Up |
|--------|------|---------------|----------|
| [ ] | [SOC L1 Alert Triage](https://tryhackme.com/room/socl1alerttriage) | The thought process behind triaging alerts — not just the tool | |
| [ ] | [SOC L1 Alert Reporting](https://tryhackme.com/room/socl1alertreporting) | How to document findings professionally — required skill from day one | |
| [ ] | [Phishing Analysis Fundamentals](https://tryhackme.com/room/phishingemails1tryoe) | Phishing is the #1 alert type at Tier 1 — every SOC sees it daily | |
| [ ] | [Splunk: The Basics](https://tryhackme.com/room/splunk101) | Foundational SIEM querying — extremely common in job postings | |
| [ ] | [Windows Event Logs](https://tryhackme.com/room/windowseventlogs) | You'll read these every single day as a SOC analyst | |
| [ ] | [Windows Logging for SOC](https://tryhackme.com/room/windowsloggingforsoc) | Deeper dive into Windows log sources and what to look for | |
| [ ] | [Monday Monitor](https://tryhackme.com/room/mondaymonitor) | New challenge room that mirrors a real SOC investigation scenario | |
| [ ] | [Friday Overtime](https://tryhackme.com/room/fridayovertime) | New challenge room — multi-source investigation under time pressure | |

---

## 🟡 High Value — Tools Employers Specifically Ask About

| Status | Room | Why It Matters | Write-Up |
|--------|------|---------------|----------|
| [ ] | [Elastic Stack: The Basics](https://tryhackme.com/room/introductiontoelastack) | Elastic/Kibana is increasingly common alongside Splunk in job postings | |
| [ ] | [Wireshark: The Basics](https://tryhackme.com/room/wiresharkthebasics) | Basic packet analysis comes up in almost every SOC interview | |
| [ ] | [MITRE](https://tryhackme.com/room/mitre) | How to explain alerts, pick indicators, and justify escalations | |
| [ ] | [Pyramid of Pain](https://tryhackme.com/room/pyramidofpainax) | Short room, high conceptual value — interviewers love asking about it | |
| [ ] | [Cyber Kill Chain](https://tryhackme.com/room/cyberkillchainzmt) | Framework for understanding attacker progression — great interview talking point | |
| [ ] | [Unified Kill Chain](https://tryhackme.com/room/unifiedkillchain) | More detailed than the original Kill Chain — shows depth of knowledge | |

---

## 🟢 Good Supporting Rooms

| Status | Room | Why It Matters | Write-Up |
|--------|------|---------------|----------|
| [ ] | [Introduction to EDR](https://tryhackme.com/room/introtoedrandsoar) | At Tier 1, EDR is used reactively alongside SIEM — know how to navigate it | |
| [ ] | [Snort](https://tryhackme.com/room/snort) | IDS/IPS knowledge is a solid differentiator for SOC roles | |
| [ ] | [Introduction to SIEM](https://tryhackme.com/room/introtosiem) | Strong conceptual foundation — great to reference when explaining your background | |
| [ ] | [Summit](https://tryhackme.com/room/summit) | Threat intelligence and detection — bridges blue team concepts together | |
| [ ] | [Eviction](https://tryhackme.com/room/eviction) | Threat hunting scenario — shows proactive SOC mindset | |

---

## ✅ Already Completed (Add Write-Ups)

| Room | Completed | Write-Up |
|------|-----------|----------|
| SOC Level 1 Path | March 2026 | `tryhackme-writeups/` *(add links as you write them up)* |
| Cyber Security 101 | July 2025 | |
| Alert Triage With Splunk | — | [alert-triage-splunk.md](./alert-triage-splunk.md) *(revise when fresh)* |

---

## 📋 Write-Up Tips (Quick Reference)

- **Write it the same day** you finish the room — memory fades fast
- **Include what tripped you up** — authenticity matters more than perfection
- **Note the specific queries or commands** you used — shows real hands-on work
- **Map findings to MITRE ATT&CK** — shows you think like an analyst
- **End with lessons learned** in your own words — not generic takeaways

---

## 📁 Suggested GitHub Folder Structure

```
whitecourt-sec/cybersecurity-portfolio/
├── README.md
├── tryhackme-writeups/
│   ├── alert-triage-splunk.md
│   ├── phishing-analysis-fundamentals.md
│   ├── windows-event-logs.md
│   └── ... (one file per room)
├── home-lab/
│   ├── splunk-setup.md
│   └── incident-report-001.md
└── notes/
    ├── mitre-attack-cheatsheet.md
    └── splunk-query-reference.md
```

---

*Last updated: May 2026 | Profile: [tryhackme.com/p/whitecourt516](https://tryhackme.com/p/whitecourt516)*
