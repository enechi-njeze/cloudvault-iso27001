# cloudvault-iso27001

![ISO 27001](https://img.shields.io/badge/Framework-ISO%2027001%3A2022-navy)
![ISMS](https://img.shields.io/badge/Program-ISMS%20Operations-blue)
![FedRAMP High](https://img.shields.io/badge/FedRAMP-High-red)
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow)
![AWS GovCloud](https://img.shields.io/badge/Cloud-AWS%20GovCloud-orange)

---

## ISO 27001:2022 Information Security Management System (ISMS)
### CloudVault Federal Health Exchange (FHX)

This repository documents the ISO 27001:2022 Information Security Management System (ISMS) for the CloudVault Federal Health Exchange (FHX). ISO 27001 is the international standard for information security management. It provides a systematic, risk-driven approach to protecting information assets and is increasingly required alongside FedRAMP for federal cloud systems that also serve international partners or operate under contract with organizations that require third-party certification.

For CloudVault FHX, the ISO 27001 ISMS complements and extends the FedRAMP High authorization by providing a structured risk treatment framework, a Statement of Applicability covering all 93 Annex A controls, and a management system that governs how security decisions are made, reviewed, and continuously improved.

---

## System Reference Card

| Field | Detail |
|---|---|
| System Name | CloudVault Federal Health Exchange (FHX) |
| System Type | Federally operated cloud-based health data exchange |
| Impact Level | HIGH: Confidentiality HIGH, Integrity HIGH, Availability HIGH |
| Cloud Platform | AWS GovCloud (us-gov-east-1 and us-gov-west-1) |
| ISMS Standard | ISO/IEC 27001:2022 |
| ISMS Scope | CloudVault FHX application, infrastructure, data, and personnel in scope of FedRAMP High authorization |
| Data Types | PHI, PII, CUI, FTI, PCI at HIGH sensitivity |
| Scale | 47 federal agencies, 890,000+ patient records, 12,000+ endpoints |
| System Owner | Dr. Patricia Owens, Deputy Director, Federal Health Systems |
| ISSO/ISSM | Enechi P.C. Njeze, CGRC, CISA, CISM, PMP, PMI-RMP, Security+, CHP, CSCS |
| Privacy Officer | Sandra Voss, Chief Privacy Officer |

---

## What ISO 27001 Is

ISO/IEC 27001:2022 is the international standard for Information Security Management Systems. It defines requirements for establishing, implementing, maintaining, and continually improving an ISMS. The 2022 revision restructured Annex A from 114 controls across 14 domains to 93 controls across 4 themes: Organizational (37), People (8), Physical (14), and Technological (34).

Unlike FedRAMP, which prescribes specific controls, ISO 27001 is risk-driven: the organization selects which Annex A controls apply based on its own risk assessment and documents its decisions in a Statement of Applicability (SoA). This makes ISO 27001 a more flexible, management-system-oriented framework, and it requires demonstrable commitment from senior leadership, not just an ISSO.

For federal health systems, ISO 27001 certification strengthens the trust posture with international health partners, supports business continuity program maturity, and provides an internationally recognized credential that complements the FedRAMP ATO for contract and procurement purposes.

---

## Repository Deliverables

| # | Document | Folder | ISO 27001 Clause | Status |
|---|---|---|---|---|
| 1 | ISMS Scope Statement | isms-scope/ | Clause 4.3 | In Progress |
| 2 | ISMS Context and Stakeholder Analysis | isms-scope/ | Clauses 4.1, 4.2 | In Progress |
| 3 | Information Security Risk Assessment | risk-assessment/ | Clause 6.1.2 | In Progress |
| 4 | Risk Treatment Plan | risk-assessment/ | Clause 6.1.3 | In Progress |
| 5 | Statement of Applicability (SoA) | soa/ | Clause 6.1.3d | In Progress |
| 6 | Information Security Policy Suite | policies/ | Clause 5.2 | In Progress |
| 7 | Internal Audit Program and Reports | internal-audit/ | Clause 9.2 | In Progress |
| 8 | Corrective Actions Register | corrective-actions/ | Clause 10.1 | In Progress |
| 9 | Management Review Records | management-review/ | Clause 9.3 | In Progress |
| 10 | ISMS Process Flow Diagram | diagrams/ | Multiple | In Progress |

---

## Folder Structure

```
cloudvault-iso27001/
├── isms-scope/           # ISMS scope statement, context, interested parties
├── risk-assessment/      # Information security risk assessment and risk treatment plan
├── soa/                  # Statement of Applicability: all 93 ISO 27001:2022 Annex A controls
├── policies/             # Information security policy suite aligned to Annex A
├── internal-audit/       # Internal audit program, schedules, and audit reports
├── corrective-actions/   # Nonconformities, root cause analysis, and corrective actions
├── management-review/    # Management review meeting agendas, records, and decisions
└── diagrams/             # ISMS process flow, Plan-Do-Check-Act cycle, risk treatment map
```

---

## ISO 27001:2022 Annex A Control Themes

| Theme | Controls | Description |
|---|---|---|
| Theme 5: Organizational | 37 | Policies, roles, supplier relationships, information classification, incident management |
| Theme 6: People | 8 | Screening, terms of employment, security training, disciplinary process |
| Theme 7: Physical | 14 | Physical perimeters, clear desk, equipment security, secure disposal |
| Theme 8: Technological | 34 | Access control, cryptography, network security, secure development, monitoring |
| **Total** | **93** | **Full Annex A, ISO/IEC 27001:2022** |

---

## ISO 27001 and FedRAMP Alignment

ISO 27001:2022 and NIST SP 800-53 Rev 5 share significant overlap. For CloudVault FHX, ISO 27001 ISMS implementation builds directly on the FedRAMP High control set rather than duplicating effort. Key alignment points include:

The ISO 27001 risk assessment (Clause 6.1.2) maps to NIST RA-3 and the FIPS 199 categorization methodology. The Statement of Applicability maps to the FedRAMP Control Implementation Summary and the NIST SP 800-53 control selection record. ISO 27001 Annex A Theme 8 technological controls align closely with the FedRAMP High technical control families (AC, IA, SC, SI, AU, CM). The ISO 27001 internal audit program (Clause 9.2) aligns with FedRAMP CA-7 and the annual 3PAO assessment. The management review (Clause 9.3) aligns with the AO briefing and risk posture reporting in RMF Step 6.

---

## Laws, Regulations, and Standards

| Instrument | Relevance |
|---|---|
| ISO/IEC 27001:2022 | Primary ISMS standard |
| ISO/IEC 27002:2022 | Implementation guidance for Annex A controls |
| ISO/IEC 27005:2022 | Information security risk management guidance |
| NIST SP 800-53 Rev 5 | FedRAMP control alignment |
| HIPAA Security Rule | PHI protection requirements |
| FISMA (44 U.S.C. § 3551) | Federal information security mandate |
| IRS Publication 1075 | FTI safeguarding requirements |
| GDPR (where applicable) | International data protection alignment |

---
Add README.md: cloudvault-iso27001 professional landing page## Certifications This Portfolio Showcases

| Certification | Issuing Body | Relevance |
|---|---|---|
| CGRC (Certified in Governance, Risk, and Compliance) | ISC2 | ISMS governance and risk management |
| CISA (Certified Information Systems Auditor) | ISACA | Internal audit and control assessment |
| CISM (Certified Information Security Manager) | ISACA | ISMS management and leadership |
| PMP (Project Management Professional) | PMI | ISMS implementation program management |
| PMI-RMP (Risk Management Professional) | PMI | ISO 27001 risk assessment and treatment |
| CompTIA Security+ SY0-701 | CompTIA | Technical Annex A control implementation |
| CHP (Certified HIPAA Professional) | APHP | PHI-related ISMS scope and controls |
| CSCS | - | Cloud security Annex A controls |
| CISSP (in progress) | ISC2 | Comprehensive ISMS architecture |

---

## Portfolio Status

| Component | Status |
|---|---|
| Repository created | Complete |
| README.md | Complete |
| ISMS Scope folder | In Progress |
| Risk Assessment folder | In Progress |
| Statement of Applicability folder | In Progress |
| Policies folder | In Progress |
| Internal Audit folder | In Progress |
| Corrective Actions folder | In Progress |
| Management Review folder | In Progress |
| Diagrams folder | In Progress |

---

*Prepared by: Enechi P.C. Njeze, CGRC, CISA, CISM, PMP, PMI-RMP, CompTIA Security+ SY0-701, CHP, CSCS*
*ISSO and ISSM: CloudVault Federal Health Exchange (FHX)*
*LinkedIn: [Enechi P.C. Njeze](https://www.linkedin.com/in/enechi-njeze)*
*Portfolio: [CloudVault GRC Portfolio](https://github.com/enechi-njeze)*
