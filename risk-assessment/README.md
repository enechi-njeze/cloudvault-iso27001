# Risk Assessment

**CloudVault Federal Health Exchange (FHX)**
**ISO 27001:2022, Clauses 6.1.2 and 6.1.3**
**Prepared By:** Enechi P.C. Njeze, ISSO/ISSM

---

## Purpose

This folder contains the Information Security Risk Assessment and Risk Treatment Plan for CloudVault FHX. ISO 27001 Clause 6.1.2 requires the organization to define and apply a risk assessment process to identify, analyze, and evaluate information security risks. Clause 6.1.3 requires a risk treatment plan that maps each risk to selected Annex A controls and documents the residual risk.

The risk assessment is the engine of the entire ISO 27001 ISMS. Every control selected in the Statement of Applicability must be traceable back to a risk identified in the risk assessment.

## Documents in This Folder

| Document | Description | Clause | Status |
|---|---|---|---|
| risk-assessment-methodology.md | Documented risk assessment criteria and process | 6.1.2a | In Progress |
| risk-register.md | Complete risk register with all identified risks | 6.1.2 | In Progress |
| risk-treatment-plan.md | Selected treatment options and Annex A control mappings | 6.1.3 | Planned |
| risk-owners-assignments.md | Approved risk owners for all identified risks | 6.1.2e | Planned |

## Risk Scoring Matrix

CloudVault FHX uses a 5x5 likelihood-impact matrix aligned to ISO/IEC 27005:2022:

| Score Range | Risk Level | Treatment Requirement |
|---|---|---|
| 20-25 | Critical | Immediate treatment, AO notification required |
| 15-19 | High | Treatment plan required within 30 days |
| 10-14 | Medium | Treatment plan required within 90 days |
| 5-9 | Low | Monitor, treat at next review cycle |
| 1-4 | Informational | Accept, document rationale |

## Top Risk Categories for CloudVault FHX

| Risk Category | Key Assets Affected | Primary Annex A Controls |
|---|---|---|
| Unauthorized access to PHI and FTI | Patient database, FTI store | 5.15, 5.16, 5.17, 8.2, 8.3 |
| Ransomware and malware | All application tiers | 8.7, 8.8, 8.15, 8.16 |
| Insider threat and privilege abuse | IAM, database admin access | 5.15, 6.3, 8.2, 8.18 |
| Third-party and supply chain risk | AWS GovCloud, SaaS components | 5.19, 5.20, 5.21, 5.22 |
| Availability disruption | API gateway, database cluster | 8.13, 8.14 |
| Configuration drift | EC2, RDS, ECS configurations | 8.9, 8.32 |
| Data exfiltration | All data stores | 5.12, 5.13, 8.11, 8.24 |

## Risk Treatment Options

For each identified risk, CloudVault FHX applies one of four ISO 27005 treatment options: modify (implement or strengthen controls to reduce likelihood or impact), retain (accept the residual risk when cost of treatment exceeds benefit), avoid (discontinue the activity that creates the risk), or share (transfer risk through insurance or contractual obligations).

## Related Documents

- [ISMS Scope](../isms-scope/README.md)
- [Statement of Applicability](../soa/README.md)
- [Corrective Actions](../corrective-actions/README.md)
- [FedRAMP POA&M](https://github.com/enechi-njeze/cloudvault-fedramp-ato/blob/main/poam/poam-master-tracker.md)

---

*Enechi P.C. Njeze, CGRC, CISA, CISM, PMP, PMI-RMP, Security+, CHP, CSCS*
*ISSO and ISSM, CloudVault Federal Health Exchange (FHX)*
