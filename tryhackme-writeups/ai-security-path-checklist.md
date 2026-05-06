# TryHackMe AI Security Path — Write-Up Tracker
**Path Link:** https://tryhackme.com/path/outline/aisecurity  
**Goal:** Complete the path, write up each room while fresh, and finish the certificate.  
**Current progress:** 5 of 26 rooms (24%) — next up: ContAInment

> ⚡ **Why this matters for your job search:** AI security is one of the fastest-growing specializations in cybersecurity right now. Completing this path while most candidates haven't touched it yet is a genuine differentiator. Even at a Help Desk or SOC Tier 1 level, being able to say you understand prompt injection, LLM threats, and AI supply chain risks puts you ahead of the pack.

---

## Module 1 — AI Fundamentals
*Covers the foundations of AI/ML technology and how it creates new attack surfaces.*

| Status | Room | Why It Matters | Write-Up |
|--------|------|---------------|----------|
| [x] | [AI/ML Security Threats](https://tryhackme.com/room/aimlsecuritythreats) | Big picture overview — AI basics, key terms, how attackers and defenders both use AI | |
| [x] | [AI Models & Data](https://tryhackme.com/room/aimodelsanddata) | How training data and model weights create security risks — data provenance, PII, poisoning | |
| [x] | [Prompt Engineering](https://tryhackme.com/room/promptengineering) | Understanding how prompts work is foundational to understanding prompt injection attacks | |
| [x] | [AI Forensics](https://tryhackme.com/room/aiforensics) | Investigating AI systems after an incident — a growing and rare skill | |
| [x] | [ContAInment](https://tryhackme.com/room/containment) | *(Next up)* How to contain and respond to AI-related security incidents | |

---

## Module 2 — Securing AI Systems
*Covers architecture, threat modelling, and hardening AI deployments.*

| Status | Room | Why It Matters | Write-Up |
|--------|------|---------------|----------|
| [ ] | [Securing AI Systems](https://tryhackme.com/room/securingaisystems) | Maps attack surfaces in AI architecture using OWASP LLM Top 10 and MITRE ATLAS | |
| [ ] | [LLM Security](https://tryhackme.com/room/llmsecurity) | Deep dive into how large language models work and their specific security concerns | |
| [ ] | [AI Threat Modelling](https://tryhackme.com/room/aithreatmodelling) | Applying STRIDE and PASTA frameworks to AI systems — structured threat analysis | |
| [ ] | [AI System Reconnaissance](https://tryhackme.com/room/aisystemreconnaissance) | How attackers discover and enumerate AI infrastructure — useful from both sides | |
| [ ] | [AI Threat Modelling Assessment](https://tryhackme.com/room/aithreatmodellingassessment) | Hands-on challenge — full AI system threat assessment capstone | |

---

## Module 3 — Prompt Security
*Covers the most common attack vector against LLM-powered applications.*

| Status | Room | Why It Matters | Write-Up |
|--------|------|---------------|----------|
| [ ] | [Prompt Injection](https://tryhackme.com/room/promptinjection) | The #1 attack against LLM apps — understanding how it works is essential | |
| [ ] | [Jailbreaking](https://tryhackme.com/room/jailbreaking) | Techniques attackers use to bypass AI safety guardrails | |
| [ ] | [Prompt Defence](https://tryhackme.com/room/promptdefence) | How to detect and prevent prompt injection — the defensive side | |
| [ ] | [LLMborghini](https://tryhackme.com/room/llmborghini) | Challenge room — hands-on prompt security scenario | |
| [ ] | [White Rabbit](https://tryhackme.com/room/whiterabbit) | Challenge room — advanced prompt security scenario | |

---

## Module 4 — AI Supply Chain Security
*Covers how attackers compromise models and dependencies before deployment.*

| Status | Room | Why It Matters | Write-Up |
|--------|------|---------------|----------|
| [ ] | [Understanding AI Supply Chains](https://tryhackme.com/room/understandingaisupplychains) | How AI models inherit risks from their training data and dependencies | |
| [ ] | [Supply Chain Attack Vectors](https://tryhackme.com/room/supplychainattackvectors) | Specific techniques attackers use to compromise AI pipelines | |
| [ ] | [Securing the AI Supply Chain](https://tryhackme.com/room/securingaisupplychain) | Defensive controls and best practices for AI supply chain hardening | |
| [ ] | [Payload](https://tryhackme.com/room/payload) | Challenge room — supply chain attack scenario | |
| [ ] | [Checkpoint](https://tryhackme.com/room/checkpoint) | Challenge room — supply chain defence scenario | |

---

## Module 5 — RAG Security
*Covers Retrieval-Augmented Generation — a common AI architecture with unique risks.*

| Status | Room | Why It Matters | Write-Up |
|--------|------|---------------|----------|
| [ ] | [RAG Security Fundamentals](https://tryhackme.com/room/ragsecurityfundamentals) | RAG is how most enterprise AI systems are built — understanding its risks is cutting-edge | |
| [ ] | [Data Poisoning in RAG Systems](https://tryhackme.com/room/datapoisoninginragsystems) | How attackers corrupt the knowledge base an AI pulls from | |
| [ ] | [Sensitive Information Disclosure](https://tryhackme.com/room/sensitiveinformationdisclosure) | How AI systems leak confidential data through their responses | |
| [ ] | [UnIndexed](https://tryhackme.com/room/unindexed) | Challenge room — RAG security scenario | |
| [ ] | [Lockdown](https://tryhackme.com/room/lockdown) | Challenge room — RAG defence scenario | |

---

## Module 6 — Path Capstone
*Final assessment to earn your certificate.*

| Status | Room | Why It Matters | Write-Up |
|--------|------|---------------|----------|
| [ ] | [AI Security Path Ticketing Event](https://tryhackme.com/room/aisecurityticketingevent) | Full end-to-end AI security investigation — the capstone for the certificate | |

---

## 📋 Write-Up Tips for AI Security Rooms

AI security rooms lend themselves to a slightly different write-up style than SOC rooms. A few things that work well:

- **Explain the concept in plain English first** — AI topics are unfamiliar to a lot of hiring managers, so showing you can communicate them clearly is itself a skill
- **Connect to real-world incidents** — there are plenty of public examples of prompt injection, data poisoning, and AI supply chain attacks you can reference
- **Note what surprised you** — AI security is genuinely new territory, so authentic reactions to concepts carry weight
- **Use the MITRE ATLAS framework** alongside MITRE ATT&CK where relevant — shows you know the AI-specific threat framework exists

---

## 📁 Suggested GitHub Folder Structure

```
whitecourt-sec/cybersecurity-portfolio/
├── README.md
├── tryhackme-writeups/
│   ├── soc-writeups/          ← SOC path write-ups
│   └── ai-security-writeups/  ← AI Security path write-ups
│       ├── aiml-security-threats.md
│       ├── prompt-injection.md
│       └── ... (one file per room)
└── home-lab/
```

---

## 🏆 Key Frameworks to Reference in Write-Ups

| Framework | What It Covers |
|-----------|---------------|
| [MITRE ATLAS](https://atlas.mitre.org/) | Adversarial tactics and techniques specific to AI/ML systems — the AI equivalent of ATT&CK |
| [OWASP LLM Top 10](https://owasp.org/www-project-top-10-for-large-language-model-applications/) | The 10 most critical vulnerabilities in LLM-powered applications |
| [MITRE ATT&CK](https://attack.mitre.org/) | Traditional adversary techniques — still applies to the infrastructure AI runs on |

---

*Last updated: May 2026 | Profile: [tryhackme.com/p/whitecourt516](https://tryhackme.com/p/whitecourt516)*
