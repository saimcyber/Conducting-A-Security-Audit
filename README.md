# Conducting a Security Audit — Botium Toys

A portfolio activity from the **Google Cybersecurity Professional Certificate**:
a practice internal security audit of a fictional company, *Botium Toys*, against
its stated scope, goals, and risk assessment.

![Focus: GRC](https://img.shields.io/badge/focus-Governance%2C%20Risk%20%26%20Compliance-blue)
![Framework: NIST CSF](https://img.shields.io/badge/framework-NIST%20CSF-informational)

## Scenario

Botium Toys runs a single on-site IT infrastructure supporting a growing online
store. Management asked for an internal audit to understand the current security
posture before expanding internationally. The audit covers the asset inventory,
existing controls, and compliance obligations (PCI DSS, GDPR, SOC).

## What I did

1. Reviewed the **scope, goals, and risk assessment report** to identify the
   assets in scope and the highest risks.
2. Completed the **Controls Assessment** — rating which administrative,
   technical, and physical controls were in place, partially in place, or absent.
3. Completed the **Compliance Checklist** — mapping gaps against PCI DSS, GDPR,
   and SOC 1 / SOC 2 requirements.
4. Summarised recommendations (least-privilege IAM, encryption at rest, MFA,
   disaster-recovery plan, centralised logging, a formal password policy).

## Files

| File | Description |
| --- | --- |
| `Botium Toys Scope, goals, and risk assessment report.pdf` | The brief the audit was run against |
| `Controls and compliance checklist.pdf` | My completed controls assessment and compliance checklist |

## Key takeaways

- An audit is only useful once the findings are **interpreted and prioritised** —
  a filled-in checklist on its own changes nothing.
- Most gaps here were low-cost administrative controls (policies, access reviews)
  rather than expensive tooling.
