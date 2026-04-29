# Statement of Applicability (SoA)

**CloudVault Federal Health Exchange (FHX)**
**ISO 27001:2022, Clause 6.1.3d**
**Prepared By:** Enechi P.C. Njeze, ISSO/ISSM

---

## Purpose

This folder contains the Statement of Applicability (SoA) for CloudVault FHX. The SoA is the cornerstone document of any ISO 27001 ISMS. It lists every one of the 93 Annex A controls from ISO/IEC 27001:2022, states whether each control is applicable or not applicable, documents the implementation status, and provides a justification for every decision.

A lead ISO 27001 auditor reviews the SoA before any other document during a certification audit. Any control marked "not applicable" must have a written justification that links back to the risk assessment. Any control marked "applicable" must have evidence of implementation.

## Documents in This Folder

| Document | Description | Status |
|---|---|---|
| statement-of-applicability.md | Full SoA: all 93 Annex A controls across 4 themes | In Progress |

## SoA Summary Statistics

| Theme | Total Controls | Applicable | Not Applicable | Implemented | Partially Implemented |
|---|---|---|---|---|---|
| Theme 5: Organizational | 37 | 35 | 2 | 28 | 7 |
| Theme 6: People | 8 | 8 | 0 | 7 | 1 |
| Theme 7: Physical | 14 | 8 | 6 | 8 | 0 |
| Theme 8: Technological | 34 | 34 | 0 | 26 | 8 |
| **Total** | **93** | **85** | **8** | **69** | **16** |

Note: The 6 not-applicable physical controls (Theme 7) govern physical facility security at the AWS GovCloud data center level. These are covered by AWS's own ISO 27001 certification and are outside the CloudVault FHX ISMS scope. This is a permissible exclusion under ISO 27001:2022 Clause 4.3, with documented justification.

## Key Controls by Theme

**Theme 5 highlights:** Threat intelligence (5.7), information security in project management (5.8), supply chain security (5.19-5.22), incident management (5.24-5.28), and business continuity (5.29-5.30) are all fully implemented and traceable to specific risk treatment decisions.

**Theme 6 highlights:** All 8 people controls are applicable. Security awareness and training (6.3) is implemented through the FedRAMP AT control family program. Non-disclosure agreements (6.6) are in place for all staff and contractors with FHX access.

**Theme 7 highlights:** Physical security controls applicable to CloudVault FHX (workstation security, clear desk, screen lock) are implemented. Physical data center controls are inherited from AWS GovCloud and documented as not applicable with written justification.

**Theme 8 highlights:** All 34 technological controls are applicable. Access management (8.2-8.5), endpoint security (8.7), and cryptography (8.24) are fully implemented. Secure coding (8.28) and security testing (8.29) are partially implemented.

## Relationship to FedRAMP Controls

The SoA controls map closely to the FedRAMP High baseline. ISO 27001 Theme 8 Technological controls align to FedRAMP families AC, IA, SC, SI, AU, and CM. Theme 5 Organizational controls align to PM, PL, IR, CP, and RA. This alignment means ISO 27001 implementation for CloudVault FHX leverages the existing FedRAMP control set rather than duplicating effort.

## Related Documents

- [Risk Assessment](../risk-assessment/README.md)
- [Policies](../policies/README.md)
- [FedRAMP Control Implementation Summary](https://github.com/enechi-njeze/cloudvault-fedramp-ato/tree/main/ssp-attachments/att-08-control-implementation-summary)

---

*Enechi P.C. Njeze, CGRC, CISA, CISM, PMP, PMI-RMP, Security+, CHP, CSCS*
*ISSO and ISSM, CloudVault Federal Health Exchange (FHX)*
