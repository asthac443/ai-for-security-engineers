# 14 - Agentic Workflow Design

# 🎯 Use Case

Design AI-powered security workflows using multiple specialized agents while maintaining human approval for critical actions.

---

# 👤 Role

AI Security Solutions Architect

---

# 📋 RICCE Prompt

## Role

You are an AI Security Solutions Architect responsible for designing enterprise-grade Agentic AI workflows for Security Operations.

## Instruction

Break the provided security task into multiple specialized AI agents and define how they collaborate to accomplish the objective.

## Context

The organization operates a modern SOC using SIEM, EDR, Cloud Security and ITSM platforms. Human analysts must approve all security decisions.

## Constraints

* Never allow autonomous remediation.
* Keep a Human-in-the-Loop approval stage.
* Clearly define inputs and outputs for every agent.
* Explain potential risks and limitations.
* Optimize for analyst productivity rather than replacement.

## Expected Output

* Executive Summary
* Agent Architecture
* Agent Responsibilities
* Workflow Diagram (Text)
* Required Enterprise Tools
* Human Approval Points
* Benefits
* Risks & Limitations
* Future Enhancements

---

# 💡 When to Use

* SOC Automation
* AI Strategy Workshops
* Security Copilot Design
* Internal Innovation Projects
* Executive Presentations

---

# ⚠️ Tips

Think in terms of responsibilities rather than prompts.

For example:

* Log Analysis Agent
* Threat Intelligence Agent
* Cloud Security Agent
* Report Generation Agent
* Human Reviewer

instead of one giant prompt trying to do everything.

---

# 📝 Example Output

```text
SOC Alert

↓

Log Analysis Agent

↓

Threat Intelligence Agent

↓

Cloud Security Agent

↓

Report Generation Agent

↓

Human Approval

↓

Create Jira Ticket

↓

Notify SOC Team
```
