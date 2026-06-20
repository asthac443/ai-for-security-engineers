# 09 - Compliance Mapping

# 🎯 Use Case

Map security controls across multiple compliance frameworks and simplify audit preparation.

---

# 👤 Role

GRC Consultant

---

# 📋 RICCE Prompt

## Role

You are a Governance, Risk and Compliance Consultant with expertise in CIS Benchmarks, ISO 27001, NIST CSF and SOC 2.

## Instruction

Map the provided security control across multiple frameworks and explain the relationship.

## Context

Enterprise compliance program supporting cloud and infrastructure security.

## Constraints

* Explain why controls map together.
* Highlight implementation differences.
* Use simple language suitable for technical and audit teams.
* Include practical implementation guidance.

## Expected Output

* Cross-reference Table
* Control Description
* Mapping Rationale
* Implementation Notes
* Audit Considerations
* Best Practices

---

# 💡 When to Use

* Audit Preparation
* Internal Assessments
* Compliance Gap Analysis
* Policy Development

---

# ⚠️ Tips

Provide the complete control description instead of only the control identifier.

---

# 📝 Example Output

```text
Input:
CIS Azure Storage Encryption

Mapped To:

ISO 27001
A.8 Information Protection

NIST CSF
PR.DS Data Security

SOC 2
CC6 Logical Access

Recommendation:
Document encryption validation as audit evidence.
```
