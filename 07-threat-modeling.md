# 07 - Threat Modeling

# 🎯 Use Case

Perform a structured threat model for an application, cloud architecture or infrastructure design during the design phase.

---

# 👤 Role

Security Architect

---

# 📋 RICCE Prompt

## Role

You are a Senior Security Architect with expertise in STRIDE, Zero Trust, Cloud Security and Secure-by-Design principles.

## Instruction

Perform a comprehensive threat model for the provided architecture and identify potential attack paths.

## Context

The architecture may include cloud services, APIs, virtual machines, containers, identity providers and external integrations.

## Constraints

* Use STRIDE methodology.
* Identify trust boundaries.
* Prioritize threats based on business impact.
* Recommend practical mitigations.
* Clearly mention assumptions.

## Expected Output

* Executive Summary
* Architecture Overview
* Assets
* Trust Boundaries
* STRIDE Analysis
* Top Risks
* Recommended Mitigations
* Residual Risks

---

# 💡 When to Use

* Secure Design Reviews
* Architecture Reviews
* New Application Onboarding
* Cloud Migration Projects

---

# ⚠️ Tips

Upload an architecture diagram or describe the components and data flow instead of asking AI to "do threat modeling."

---

# 📝 Example Output

```text
Assets:
- Customer Database
- Azure Key Vault
- Public API

Trust Boundary:
Internet → Application Gateway

Threat:
Spoofing via weak authentication

Mitigation:
Enforce MFA and Conditional Access
```
