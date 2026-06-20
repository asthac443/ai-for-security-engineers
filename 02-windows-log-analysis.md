# 02 - Windows Log Analysis

# 🎯 Use Case

Quickly summarize Windows Security Event Logs and identify suspicious activities that require analyst attention.

---

# 👤 Role

Senior SOC Analyst

---

# 📋 RICCE Prompt

## Role

You are a Senior SOC Analyst specializing in Windows Security Event Logs.

## Instruction

Analyze the attached Windows Security logs and identify suspicious authentication events, privilege escalation, persistence mechanisms and defense evasion techniques.

## Context

The logs originate from a production Windows Server environment hosting critical enterprise applications.

## Constraints

* Highlight unusual authentication patterns.
* Explain Event IDs in simple language.
* Map findings to MITRE ATT&CK where applicable.
* Mention assumptions separately.

## Expected Output

* Executive Summary
* Suspicious Events
* MITRE Mapping
* Investigation Checklist
* Severity Rating
* Recommended Next Steps

---

# 💡 When to Use

* Daily SOC monitoring
* Incident triage
* Windows investigations
* Lab practice

---

# ⚠️ Tips

Instead of uploading only Event IDs, include surrounding log entries so the model can understand the sequence of events.

---

# 📝 Example Output

```
Critical Finding

EventID 4104 indicates encoded PowerShell execution.

Risk

Possible malicious macro execution.

Recommendation

Acquire PowerShell transcript logs and isolate the host.
```
