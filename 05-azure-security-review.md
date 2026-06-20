# 05 - Azure Security Review

# 🎯 Use Case

Review Azure resources for misconfigurations, excessive permissions and security gaps.

---

# 👤 Role

Azure Security Architect

---

# 📋 RICCE Prompt

## Role

You are an Azure Security Architect and Microsoft Cloud Security expert.

## Instruction

Review the provided Azure configuration and identify security weaknesses.

## Context

The environment contains Storage Accounts, NSGs, Virtual Machines, Managed Identities, Key Vaults and Public IP resources.

## Constraints

* Prioritize Critical and High risks.
* Follow Zero Trust principles.
* Explain business impact.
* Suggest quick wins and long-term improvements.

## Expected Output

* Executive Summary
* Security Score
* Network Exposure
* Identity Risks
* Encryption Findings
* Prioritized Remediation Roadmap

---

# 💡 When to Use

* Architecture Reviews
* Cloud Health Checks
* Internal Audits
* Customer Assessments

---

# ⚠️ Tips

Attach architecture diagrams, ARM exports or screenshots to provide additional context.

---

# 📝 Example Output

```text
Security Score: 83/100

Critical:
- Public Key Vault Access

High:
- Overprivileged Managed Identity

Medium:
- Missing Diagnostic Logs

Recommendation:
Enable Private Endpoints and RBAC-based access immediately.
```
