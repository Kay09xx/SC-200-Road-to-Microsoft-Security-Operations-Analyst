# 🛡️ SC-200 Study Notes  
## 📅 Day 1 — Introduction to Cyber Defense and SOC Fundamentals  

The **SC-200 (Microsoft Security Operations Analyst)** exam is largely based on the **NIST 800-61** framework.

---

## 🧩 NIST Framework (Incident Response Lifecycle)

**Phases:**
1. **Preparation**  
2. **Detection and Analysis**  
3. **Containment, Eradication, and Recovery**  
4. **Post-Incident Activity**

---

## 🏢 Functions of a Security Operations Center (SOC)

- Threat intelligence  
- Threat hunting  
- Threat detection  
- Log management  
- Root cause investigation  
- Incident response  
- Reducing attack surface  

> **SOC Model:** Represents the organizational structure of a SOC.

---

## ⚙️ Key Security Technologies

### EDR – Endpoint Detection and Response  
Performs behavioral monitoring on endpoints (logs).  
**Example:** Microsoft Defender for Endpoint  

### XDR – Extended Detection and Response  
Performs behavior monitoring beyond endpoints.  
**Example:** Microsoft Defender XDR  

### SIEM – Security Information and Event Management  
Centrally correlates and analyzes logs.  
**Example:** Microsoft Sentinel  

### SOAR – Security Orchestration, Automation, and Response  
Automates incident response procedures.  
**Example:** Sentinel + Azure Logic Apps  

---

## 🧠 Cybersecurity Teams

### 🟦 Blue Team (Defensive)
**Functions:**
- Security monitoring  
- Incident response  
- Forensics  
- Threat hunting  

### 🟥 Red Team (Offensive)
**Functions:**
- Penetration testing  
- Social engineering  
- Vulnerability assessments  
- TTPs (Tactics, Techniques, and Procedures)  

### 🟪 Purple Team
A collaboration between Red and Blue teams for improved effectiveness.  

---

## ⚔️ Core Concepts

### TTPs  
Used by attackers to carry out attacks.  

### Threat Intelligence  
Information on threats and attackers — answers *who* and *why*.  

### Cyber Threat Intelligence (CTI)  
Information about attackers and their behavior patterns.  

---

## ⚖️ Risk Formula

**Risk = Impact + Likelihood**

---

## 🧠 Threat-Informed Defense
Using information about attacker behavior to plan and improve defenses.  

---

## 🧩 Indicators

| Type | Meaning | Example |
|------|----------|----------|
| **IOC (Indicator of Compromise)** | Evidence that an attack has *already happened* | Unknown running processes, suspicious IP addresses |
| **IOA (Indicator of Attack)** | Signs that an attack *is happening* | Behavior showing attacker intent |

---

## 🔺 Pyramid of Pain
A defensive model where defenders make it progressively harder for attackers to succeed — discouraging them by increasing the “pain” of adaptation.  

---

## 🌐 Cyber Threat Intelligence (CTI) Sources

### Enterprise Sources
- CrowdStrike  
- Microsoft  
- Cisco  

### OSINT (Open-Source Intelligence)
- VirusTotal  
- Social media  

---

## 🧱 Vulnerabilities

### CVE – *Common Vulnerabilities and Exposures*  
Unique ID given to a known security weakness in software/hardware.  

### CVSS – *Common Vulnerability Scoring System*  
Measures how impactful a vulnerability is based on the CIA Triad.

#### CVSS v2
| Score | Comment |
|--------|----------|
| 7.0–10.0 | High |
| 4.0–6.9 | Medium |
| 0–3.9 | Low |

#### CVSS v3
| Score | Comment |
|--------|----------|
| 9.0–10.0 | Critical |
| 7.0–8.9 | High |
| 4.0–6.9 | Medium |
| 0.1–3.9 | Low |
| 0 | None |

> Vulnerability scanners use these scores to help organizations prioritize fixes.

---

## ☁️ Cloud Computing Models

| Model | Description |
|--------|-------------|
| **Private Cloud** | Infrastructure dedicated to a single organization |
| **Public Cloud** | Owned by a third party and shared among organizations |
| **Hybrid Cloud** | Combination of private and public clouds |
| **Multi-Cloud** | Use of multiple cloud providers |

---

## 🔒 Zero Trust Model

A security strategy where **no one is trusted by default**.

**Core Principles:**
1. **Verify explicitly**  
2. **Least privilege** — Grant only minimal access needed  
3. **Assume breach** — Always act as if an attack is ongoing  

---

## 🧬 MITRE ATT&CK Framework

**MITRE ATT&CK** = *Adversary Tactics, Techniques & Common Knowledge*  
It acts as a dictionary of known attack methods and helps categorize, describe, and defend against them.

### Structure:
- **Tactics (Why)** — Objective of the adversary  
- **Techniques (How)** — How the adversary performs the attack  
- **Sub-Techniques (How2)** — More detailed version of the technique  

**Example:**
| Layer | Description |
|--------|-------------|
| **Tactic (Why)** | The attackers were executing something |
| **Technique (How)** | The attackers used a command script |
| **Sub-Technique (How2)** | The command script was written in Python |

---

✅ **End of Day 1 Notes**
