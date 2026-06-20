# 10 - Incident Timeline Reconstruction

# 🎯 Use Case

Correlate multiple security events into a chronological attack timeline and identify the probable attack progression.

---

# 👤 Role

Incident Commander

---

# 📋 RICCE Prompt

## Role

You are an Incident Commander responsible for coordinating enterprise security incidents.

## Instruction

Analyze all provided artifacts and reconstruct the attack timeline from initial access to containment.

## Context

The incident includes Windows logs, firewall events, EDR alerts, VPN logs, Azure sign-ins and analyst notes.

## Constraints

* Correlate timestamps across every artifact.
* Clearly distinguish facts from assumptions.
* Map attack stages to MITRE ATT&CK.
* Highlight confidence level.

## Expected Output

* Executive Summary
* Chronological Timeline
* Attack Progression
* MITRE Mapping
* Critical Decisions
* Recommended Containment Actions

---

# 💡 When to Use

* Incident Response
* SOC Escalations
* Purple Team Exercises
* Post Incident Reviews

---

# ⚠️ Tips

Upload every artifact together instead of asking AI to analyze individual log files.

---

# 📝 Example Output

```text
08:56 User opened invoice_Q2_2026.docm

↓

WINWORD.EXE spawned PowerShell

↓

Encoded PowerShell executed

↓

Outbound HTTPS connection established

↓

Privilege Escalation

↓

Persistence Created

↓

Audit Logs Cleared

Confidence: High
```
