# Corrective Actions

**CloudVault Federal Health Exchange (FHX)**
**ISO 27001:2022, Clause 10.1**
**Prepared By:** Enechi P.C. Njeze, ISSO/ISSM

---

## Purpose

This folder contains the Corrective Actions Register for the CloudVault FHX ISMS. ISO 27001 Clause 10.1 requires the organization to react to nonconformities, take action to control and correct them, deal with the consequences, investigate root causes, and implement corrective actions to prevent recurrence.

Every finding from an internal audit, external certification audit, security incident, or management review that represents a nonconformity generates a corrective action record. The corrective action process is what distinguishes a living ISMS from a paper ISMS: it demonstrates that when something goes wrong, the organization learns from it and changes.

## Documents in This Folder

| Document | Description | Clause | Status |
|---|---|---|---|
| corrective-actions-register.md | Master register of all open and closed corrective actions | 10.1 | In Progress |
| nonconformity-template.md | Standard template for documenting nonconformities | 10.1 | Planned |
| root-cause-analysis-procedures.md | RCA methodology for significant nonconformities | 10.1b | Planned |

## Corrective Action Sources

| Source | Examples | Typical Root Cause |
|---|---|---|
| Internal Audit Findings | Policy not reviewed annually, control not implemented as documented | Resource constraints, role ambiguity |
| External Certification Audit | Minor nonconformity: missing evidence, incomplete record | Documentation gaps |
| Security Incidents | Unauthorized access attempt not logged per procedure | Configuration gap, procedure not followed |
| Management Review | Objective not met, metric below threshold | Process design issue |
| FedRAMP POA&M | Control finding not remediated on schedule | Resource or technical constraint |

## Corrective Action Lifecycle

Every corrective action follows a five-stage lifecycle:

1. **Identification and documentation:** Nonconformity described, source identified, risk assessed.
2. **Containment:** Immediate action to stop harm or further nonconformity.
3. **Root cause analysis:** Five-why analysis or fishbone diagram for significant findings.
4. **Corrective action implementation:** Process, policy, or technical change applied.
5. **Verification of effectiveness:** Evidence that the corrective action prevented recurrence, reviewed at next internal audit or management review.

## Relationship to FedRAMP POA&M

ISMS corrective actions and FedRAMP POA&M items address overlapping but distinct concerns. A FedRAMP POA&M item tracks a specific control finding with a remediation date. An ISMS corrective action may address the same technical finding but also investigates the systemic root cause that allowed the finding to occur, such as an inadequate change management process that permitted a misconfiguration to persist undetected. Maintaining both ensures the organization fixes the finding and prevents recurrence.

## Related Documents

- [Internal Audit](../internal-audit/README.md)
- [Management Review](../management-review/README.md)
- [FedRAMP POA&M](https://github.com/enechi-njeze/cloudvault-fedramp-ato/blob/main/poam/poam-master-tracker.md)

---

*Enechi P.C. Njeze, CGRC, CISA, CISM, PMP, PMI-RMP, Security+, CHP, CSCS*
*ISSO and ISSM, CloudVault Federal Health Exchange (FHX)*
